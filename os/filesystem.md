Motherbood has a PC BIOS part. The fundamental purposes of the BIOS are to init and test
the system hardware components, and to load a bootloader or an OS from a mass memory device.

The first sector of the hard drive is master boot record (MBR). It holds the partition table,

BIOS is going into Unified Extensible Firmware Interface (UEFI).

The partition table cannot handle more than 2TB partitions.

File system can refer to the format of the hard drive, e.g. FAT32, NTFS, EXT4, JFS, XFS, etc.
It can also refer to how an OS organizes and persistents data.

+ /bin
+ /boot: necessary stuff for bootloader
+ /cdrom: deprecated
+ /dev: all devices
+ /etc: holds all the configuration files
+ /home
+ /lib & /lib64: libraries, like DLLs.
+ /media: the storage
+ /opt: optional softwares
+ /tmp: clears out when reboot.
+ /var: logs and tmp files for the system.
+ /sbin: more binaries.
+ /root: root user's stuff.
+ /usr: universal system resources.
