# /etc/fstab: static file system information.
#
# Use 'blkid' to print the universally unique identifier for a
# device; this may be used with UUID= as a more robust way to name devices
# that works even if disks are added and removed. See fstab(5).
#
# <file system> <mount point>   <type>  <options>       <dump>  <pass>
# / was on /dev/sda1 during installation
UUID=0cfc54e8-3d2c-4ba0-bf63-229b38c8d732 /               ext4    errors=remount-ro 0       1
# /boot/efi was on /dev/sdd2 during installation
UUID=54BE-F836  /boot/efi       vfat    umask=0077      0       1
# /home was on /dev/sda3 during installation
UUID=e4293c94-9f67-45c5-b8c2-1e98a8776508 /home           ext4    defaults        0       2
# swap was on /dev/sda2 during installation
UUID=cecda0c3-64dd-4c02-b6e3-a234d195f265 none            swap    sw              0       0


Linux version 5.0.0-23-generic (buildd@lgw01-amd64-030) (gcc version 7.4.0 (Ubuntu 7.4.0-1ubuntu1~18.04.1)) #24~18.04.1-Ubuntu SMP Mon Jul 29 16:12:28 UTC 2019
