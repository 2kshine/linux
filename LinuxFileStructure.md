# Linux File System Structure

### Key Concepts

> Different storage devices like hard drives, usb, network drives are mounted to a directory under **/media** or **/mnt**
> Special files represent devices or processes, like block devices **/dev/sda**, character devices **/dev/tty**

### Directory Structure

1. / (Root Directory):
   ... Top-level directory in the file system. All other files and directories are contained within it.

2. /bin:
   ... Contains essential system binary files, such as **ls, cp, and mv**.

3. /boot:
   ... Contains files needed for booting the system, including the Linux kernel and bootloader configurations.

4. /dev:
   ... Contains device files that represent hardware devices, such as /dev/sda (hard disk) and /dev/tty (terminal devices).

5. /etc:
   ... Contains system-wide configuration files, such as /etc/passwd (user information) and /etc/fstab (file system mount information).

6. /home:
   ... Contains user directories. Each user has a subdirectory here, like /home/john for the user "john".

7. /lib:
   ... Contains shared libraries required by binaries in /bin and /sbin, and modules for the kernel.

8. /media:
   ... Mount point for removable media (e.g., USB drives, CD-ROMs) that are automatically mounted.

9. /mnt:
   ... A temporary mount point for manually mounted file systems, often used for mounting external storage or network shares.

10. /opt:
    ... Contains optional software packages and third-party applications installed by the user or system administrator.

11. /proc:
    ... A virtual file system providing process and kernel information, like /proc/cpuinfo (CPU details) and /proc/meminfo (memory information).

12. /root:
    ... The home directory for the root (superuser) account.

13. /run:
    ... Contains runtime data, such as system information for processes running since the last boot.

14. /sbin:
    ... Contains system binaries for system administration tasks, usually used by the root user, such as shutdown, reboot, and ifconfig.

15. /srv:
    ... Contains data for services provided by the system, like web servers (/srv/www) or FTP servers.

16. /sys:
    ... A virtual file system providing access to kernel parameters and system information, used by both kernel and userspace processes.

17. /tmp:
    ... A directory for temporary files created by applications or the system, often cleared upon reboot.

18. /usr:
    ... Contains user-related programs and data. Subdirectories include /usr/bin (user binaries), /usr/lib (libraries), and /usr/share (shared data).

19. /var:
    ... Contains variable data files, such as log files (/var/log), mail (/var/mail), and spool files for printers and tasks.
