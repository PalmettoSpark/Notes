
## Core Principals
- Everything is a file
- Configuration data is stored in a text file

### Kernel
Virtualizes hardware in a standard way to allow for compatibility via drivers and issues resources via scheduler to avoid the OS crashing. OS sits on top of kernel.
![[Pasted image 20240123210920.png]]

File systemis ===Filesystem Hierarchy Standard ===

*Link to complete breakdown of Linux file system*  - https://www.pathname.com/fhs/
Includes an explination of the files in each file folder ^


## Paths

- `/` = Top level,  boot files
- `/bin` = essential binaries
- `/boot` = static bootloader (kernel executable)
- `/dev` = access to devices attached to system
- `/etc` = local sys config files for installed apps
- `/home` = head of user subdirectories
- `/lib` = shared libs required for system boot
- `/media` = external removable media such as USB mounted here
- `/mnt` = temp mount point for regular filesystems
- `/opt` = optional files such as third-party tools
- `/root` = home directory for the root user
- `/sbin` = exes for system admin
- `/tmp` = os and app temp file storage, often overwritted/destroyed on boot
- `/user` = contains exe's,libs, man files, etc
- `/var` = contains var data files such as longs, email in-boxes, web app related files and more




`
`


