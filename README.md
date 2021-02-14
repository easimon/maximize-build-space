# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This action maximizes the disk space available to your build job, by

- removing unnecessary preinstalled software
- utilizing space on an otherwise unused temp disk

The idea came up when I tried to build a Fedora Linux Kernel RPM on Github, and the Job aborted due to disk space issues.

## Caveats

- **This action is a hack, really**, and on a "works for me" basis. It has been built by reverse-enginnering undocumented parts of the Github runner setup, which might change in the future -- up to the point where this action ceases to work. For sure you're voiding the warranty on Github runners when using this. **If you are not running into disk space issues with the default runner setup, don't use it.**.
- I did not measure the speed of the disk, so I do not have numbers. But since this action uses LVM on top of loop-mounted files, expect a space/speed trade-off when using it.
- The LVM image files on the root and temp partition are created sparse, which makes the available space on the original volumes appear larger than it acutally is. You should not consider to have more space on the root volume available than specified in `root-reserve-mb`, and consider `/mnt` full, otherwise you might run into surprising "out of space" situations. While your build job will run (and consume disk space) in `$GITHUB_WORKSPACE` mostly, other parts might require additional space on `/` as well -- most notable being `/var/lib/docker` for docker images, when running docker build steps. While it would be possible to create the image non-sparse, I found only quite time-consuming ways to do so (write zeros with dd, e.g.).
- Removal of unnecessary software is currently implemented by `rm -rf` on specific folders, not by using a package manager. While this is quick and easy, it might delete dependencies that are required implicitly and so break your build (e.g. because your build job uses a .NET based tool and you removed the required runtime).

Btw: the choice of removable packages is not an expression of dislike against these -- they were just the largest folders for a single toolkit I could find quickly.

## How it works

At the time of writing, public Github runners are using [Azure DS2_v2 virtual machines](https://docs.microsoft.com/en-us/azure/virtual-machines/dv2-dsv2-series#dsv2-series), featuring a 84GB OS disk on `/` and a 14GB temp disk mounted on `/mnt`.

1. The root file system has ~29GB (of 84GB) available, the rest being consumed by the preinstalled build environment. Github runners come with a rich choice of software, see [Ubuntu 18.04.4 LTS image description](https://github.com/actions/virtual-environments/blob/ubuntu18/20200806.0/images/linux/Ubuntu1804-README.md). This is great to support a wide variety of workflows but also consumes a lot of space by providing programs that might be unused for an individual build job.
2. The temp disk hosts a 4GB swap file, leaving 10GB completely unused.

This action (optionally) removes unwanted preinstalled software, concatenates the free space on `/` and `/mnt` (the temp disk) to an LVM volume group, creates a swap partition and a build volume on that volume group, and mounts this volume back to a given path (`${GITHUB_WORKSPACE}` by default). This results in the space of the previously installed packages and the temp disk being available for your build job.

## Usage

You should most probably use this action as the first build step, even **before** `actions/checkout`. Since this action mounts a volume over the current working directory by default, the current content of the working directory will be inaccessible afterwards.

With the default configuration, you're gaining about 8-9GB of disk space. You can trade in swap space or root reserve to get more (max. ~14GB, since this is the size of the temporary disk), and remove software that is unnecessary for your build job (see [#inputs](#inputs) for the amount of space you can gain by doing so).

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

All inputs are optional and default to the following, gaining about 8-9 GB additional space.

```yaml
  root-reserve-mb:
    description: 'Space to be left free on the root filesystem, in Megabytes.'
    required: false
    default: 1024
  swap-size-mb:
    description: 'Swap space to create, in Megabytes.'
    required: false
    default: 4096
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
    description: 'Removes .NET runtime and libraries. (frees ~17 GB)'
    required: false
    default: 'false'
  remove-android:
    description: 'Removes Android SDKs and Tools. (frees ~11 GB)'
    required: false
    default: 'false'
  remove-haskell:
    description: 'Removes GHC (Haskell) artifacts. (frees ~2.7 GB)'
    required: false
    default: 'false'
```
