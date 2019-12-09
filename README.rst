===============
raspbian-imager
===============

This is a Python script that creates an SD card image for some types of Raspberry Pi to boot into the mainline Debian installer. The created image will contain three partitions: the Raspberry Pi firmware partition (to be mounted to /boot/firmware), an EFI partition (/boot/efi) and a third partition holding the Debian installer files.

The boot process involves U-Boot, booting into Grub, booting into the Linux kernel with the Debian installer.

When installing Debian, just delete the third partition on the card and create a new partition using the rest of the available capacity on the card as the root file system.
