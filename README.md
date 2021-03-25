# Maximize available disk space for build tasks

By default, public shared Github runners come with around 25-29 GB of free disk space to be consumed by your build job.
If this is too little for you, and your build job runs out of disk space, this action might be for you.

If not: please go on, there's nothing to see here.

This action maximizes the available disk space on public shared GitHub runners, by

- Utilizing space on an otherwise unused temp disk
- Optionally removing unnecessary preinstalled software
- Optionally resizing the SWAP space

Depending on the use case, you can gain more than double the original space.

The idea came up when I tried to build a Fedora Linux Kernel RPM on Github, and the Job aborted due to disk space issues.

## Caveats

- **This action is a hack, really**, and on a "works for me" basis. It has been built by reverse-enginnering undocumented parts of the Github runner setup, which might change in the future -- up to the point where this action ceases to work. For sure you're voiding the warranty on Github runners when using this. **If you are not running into disk space issues with the default runner setup, don't use it.**.
- Since this action uses LVM on top of loop-mounted files, expect a space/speed trade-off when using it. I did not measure the speed of the disk, so I do not have numbers, but be warned.
- This action fills the whole root and temp volume with large image files. You will not have more space on the root volume available than specified in `root-reserve-mb`, similarly for `/mnt` and `temp-reserve-mb`. While your build job will usually run (and consume disk space) in `$GITHUB_WORKSPACE` mostly, other parts might require additional space in other places -- e.g. `/var/lib/docker` for docker images, when running docker build steps, but also `apt install` will install to the root volume. Increase `root-reserve-mb` or `temp-reserve-mb` accordingly in these cases -- or set `overprovision-lvm` to true.
- Removal of unnecessary software is currently implemented by `rm -rf` on specific folders, not by using a package manager or anything sophisticated. While this is quick and easy, it might delete dependencies that are required by your job and so break your build (e.g. because your build job uses a .NET based tool and you removed the required runtime).

Btw: the choice of removable packages is not an expression of dislike against these -- they were just the largest folders for a single toolkit I could find quickly.

## How it works

At the time of writing, public [Github-hosted runners](https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners) are using [Azure DS2_v2 virtual machines](https://docs.microsoft.com/en-us/azure/virtual-machines/dv2-dsv2-series#dsv2-series), featuring a 84GB OS disk on `/` and a 14GB temp disk mounted on `/mnt`.

1. The root file system has ~29GB (of 84GB) available, the rest being consumed by the preinstalled build environment. Github runners come with a rich choice of software, see the image descriptions for [Ubuntu 18.04](https://github.com/actions/virtual-environments/blob/main/images/linux/Ubuntu1804-README.md) or [Ubuntu 20.04](https://github.com/actions/virtual-environments/blob/main/images/linux/Ubuntu2004-README.md). This is great to support a wide variety of workflows out of the box, but also consumes a lot of space by providing programs that might be unnecessary for an individual build job.
1. The temp disk mainly hosts a 4GB swap file, leaving approx. 10GB completely unused.

This action does the following:

1. (Optionally) removes unwanted preinstalled software
1. Concatenates the free space on `/` and `/mnt` (the temp disk) to an LVM volume group
1. Creates a swap partition and a build volume on that volume group
1. Mounts the build volume back to a given path (`${GITHUB_WORKSPACE}` by default)

This results in the space of the previously installed packages and the temp disk being available for your build job.

## Usage

You should most probably use this action as the first build step, even **before** `actions/checkout`. Since this action mounts a volume over the current working directory by default, the current content of the working directory will be inaccessible afterwards.

With the default configuration, you're gaining about 7-8 GB of disk space. You can trade in swap space or disk reserve to get more and remove software that is unnecessary for your build job (see [this table](https://github.com/easimon/maximize-build-space/blob/test-report/README.md) for examples and the expectable amount of space.

When removing software, consider that the removal of large amounts of files (which this is) can take minutes to complete. On the upside, you'll get more than 60 GB of disk space available if you actually need it.

```yaml
name: My build action requiring more space
on: push

jobs:
  build:
    name: Build my artifact
    runs-on: ubuntu-latest
    steps:
      - name: Maximize build space
        uses: easimon/maximize-build-space@master
        with:
          root-reserve-mb: 512
          swap-size-mb: 1024
          remove-dotnet: 'true'
      - name: Checkout
        uses: actions/checkout@v2

      - name: Build
        run: |
          echo "Free space:"
          df -h
```

## Inputs

All inputs are optional and default to the following, gaining about 7-8 GB additional space.

```yaml
  root-reserve-mb:
    description: 'Space to be left free on the root filesystem, in Megabytes.'
    required: false
    default: '1024'
  temp-reserve-mb:
    description: 'Space to be left free on the temp filesystem (/mnt), in Megabytes.'
    required: false
    default: '100'
  swap-size-mb:
    description: 'Swap space to create, in Megabytes.'
    required: false
    default: '4096'
  overprovision-lvm:
    description: |
      Create the LVM disk images as sparse files, making the space required for the LVM image files *appear* unused on the
      hosting volumes until actually allocated. Use with care, this can lead to surprising out-of-disk-space situations.
      You should prefer adjusting root-reserve-mb/temp-reserve-mb over using this option.
    required: false
    default: 'false'
  build-mount-path:
    description: 'Absolute path to the mount point where the build space will be available, defaults to $GITHUB_WORKSPACE if unset.'
    required: false
  pv-loop-path:
    description: 'Absolute file path for the LVM image created on the root filesystem, the default is usually fine.'
    required: false
    default: '/pv.img'
  tmp-pv-loop-path:
    description: 'Absolute file path for the LVM image created on the temp filesystem, the default is usually fine. Must reside on /mnt'
    required: false
    default: '/mnt/tmp-pv.img'
  remove-dotnet:
    description: 'Removes .NET runtime and libraries.'
    required: false
    default: 'false'
  remove-android:
    description: 'Removes Android SDKs and Tools.'
    required: false
    default: 'false'
  remove-haskell:
    description: 'Removes GHC (Haskell) artifacts.'
    required: false
    default: 'false'
```
