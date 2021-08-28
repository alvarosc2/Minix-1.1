The disks are labelled as follows:

Disk 1: Boot Disk
Disk 2: Root File System
Disk 3: /usr
Disk 4: /user
Disk 5: Kernel, H and Include Sources
Disk 6: FS and Lib Sources
Disk 7: MM and Tools Sources
Disk 8: Commands Sources

Running Minix 1.1 in Bochs 2.7

login: ast
password: Wachtwoord

Ctrl-D to logout

If there are two floppy units available, it is possible to mount the disk 
/user by inserting it in the unit 1 and typing

/etc/mount /dev/fd1 /user
