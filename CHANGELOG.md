# Changelog

## [v4] - 2021-03-25: Do not overprovision space by default

### Added

- Configuration option of overprovisioning the build volume (`overprovision-lvm`), defaulting to `'false'`.
- Configurable temp volume reserve (`temp-reserve-mb`), defaulting to `'100'`.

### Changed

- (potentially breaking) The LVM image files are not created sparsely anymore. Previously, free disk space *appeared* free on **both** the build volume and the hosting volume, until actually allocated by writing to the build volume. Now, the space is actually consumed on volume creation -- meaning, that after creating the build volume, the root and temp volume do not have or show more space available than configured in `root-reserve-mb` and `temp-reserve-mb`. This can be reverted by setting `overprovision-lvm` to `'true'`, but surprising out-of-disk space situations might be the result.
- Temp volume reserve was fixed to 1024 KB, this defaults to a more cautious 100 MB now, and is configurable.

## [v3] - 2021-02-15: Fix running on Ubuntu 20.04

### Changed

- Includes a workaround for the temp disk being locked on Ubuntu 20.04. Instead of formatting the temp disk, the LVM volume is now created ontop of loop-mounted files on both / and /mnt, leaving the original file systems intact.

## [v2] - 2021-01-05: Fix file system permissions on logical volume

### Changed

- Change the owner of the logical volume to the runner user recursively, fixing permission issues when e.g. checking out code to the root of the logical volume. (Actually, the problem is the lost+found folder in the ext4 root, and chowning it breaks its purpose. But since the volume is temporary anyway, lost+found functionality is not really needed).

## [v1] - 2020-08-20: Initial release
