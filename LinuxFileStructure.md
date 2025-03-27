# Linux File System Structure

### Key Concepts

> Different storage devices like hard drives, usb, network drives are mounted to a directory under **/media** or **/mnt**
> Special files represent devices or processes, like block devices **/dev/sda**, character devices **/dev/tty**

### Directory Structure

/ (Root Directory):
... Top-level directory in the file system. All other files and directories are contained within it.

/bin:
... Contains essential system binary files, such as ls, cp, and mv.

/boot:
... Contains files needed for booting the system, including the Linux kernel and bootloader configurations.

/dev:
... Contains device files that represent hardware devices, such as /dev/sda (hard disk) and /dev/tty (terminal devices).

/etc:
... Contains system-wide configuration files, such as /etc/passwd (user information) and /etc/fstab (file system mount information).

/home:
... Contains user directories. Each user has a subdirectory here, like /home/john for the user "john".

/lib:
... Contains shared libraries required by binaries in /bin and /sbin, and modules for the kernel.

/media:
... Mount point for removable media (e.g., USB drives, CD-ROMs) that are automatically mounted.

/mnt:
... A temporary mount point for manually mounted file systems, often used for mounting external storage or network shares.

/opt:
... Contains optional software packages and third-party applications installed by the user or system administrator.

/proc:
... A virtual file system providing process and kernel information, like /proc/cpuinfo (CPU details) and /proc/meminfo (memory information).

/root:
... The home directory for the root (superuser) account.

/run:
... Contains runtime data, such as system information for processes running since the last boot.

/sbin:
... Contains system binaries for system administration tasks, usually used by the root user, such as shutdown, reboot, and ifconfig.

/srv:
... Contains data for services provided by the system, like web servers (/srv/www) or FTP servers.

/sys:
... A virtual file system providing access to kernel parameters and system information, used by both kernel and userspace processes.

/tmp:
... A directory for temporary files created by applications or the system, often cleared upon reboot.

/usr:
... Contains user-related programs and data. Subdirectories include /usr/bin (user binaries), /usr/lib (libraries), and /usr/share (shared data).

/var:
... Contains variable data files, such as log files (/var/log), mail (/var/mail), and spool files for printers and tasks.
