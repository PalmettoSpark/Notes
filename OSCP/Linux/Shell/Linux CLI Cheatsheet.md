
### General Tools
| **Command** | **Description** |
| ---- | ---- |
| `man <tool>` | Opens manual pages for the specified tool. |
| `<tool> -h` | Prints the help page of the tool. |
| `apropos <keyword>` | Searches through man pages' descriptions for instances of a given keyword. (/ˌaprəˈpō/) // find tool by keyword |
| `cat` | Concatenate and print contents of files. |
| `whoami` | Displays current username. |
| `id` | Returns users identity. |
| `hostname` | Sets or prints the name of the current host system. |
| `uname` | Prints operating system name. |
| `pwd` | Returns working directory name. |
| `ifconfig` | The `ifconfig` utility is used to assign or view an address to a network interface and/or configure network interface parameters. |
| `ip` | Ip is a utility to show or manipulate routing, network devices, interfaces, and tunnels. |
| `netstat` | Shows network status. |
| `ss` | Another utility to investigate sockets. |
| `ps` | Shows process status. |
| `who` | Displays who is logged in. |
| `env` | Prints environment or sets and executes a command. |
| `lsblk` | Lists block devices. (hard drive partitions) |
| `lsusb` | Lists USB devices. |
| `lsof` | Lists opened files. |
| `lspci` | Lists PCI devices. |
| `sudo` | Execute command as a different user. |
| `su` | The `su` utility requests appropriate user credentials via PAM and switches to that user ID (the default user is the superuser).  A shell is then executed. |
| `useradd` | Creates a new user or update default new user information. |
| `userdel` | Deletes a user account and related files. |
| `usermod` | Modifies a user account. |
| `addgroup` | Adds a group to the system. |
| `delgroup` | Removes a group from the system. |
| `passwd` | Changes user password. |
| `dpkg` | Install, remove and configure Debian-based packages. |
| `apt` | High-level package management command-line utility. |
| `aptitude` | Alternative to `apt`. |
| `snap` | Install, remove and configure snap packages. |
| `gem` | Standard package manager for Ruby. |
| `pip` | Standard package manager for Python. |
| `git` | Revision control system command-line utility. |
| `systemctl` | Command-line based service and systemd control manager. |
| `ps` | Prints a snapshot of the current processes. |
| `journalctl` | Query the systemd journal. |
| `kill` | Sends a signal to a process. |
| `bg` | Puts a process into background. |
| `jobs` | Lists all processes that are running in the background. |
| `fg` | Puts a process into the foreground. |
| `curl` | Command-line utility to transfer data from or to a server. |
| `wget` | An alternative to `curl` that downloads files from FTP or HTTP(s) server. |
| `python3 -m http.server` | Starts a Python3 web server on TCP port 8000. |
| `ls` | Lists directory contents. |
| `cd` | Changes the directory. |
| `clear` | Clears the terminal. |
| `touch` | Creates an empty file. |
| `mkdir` | Creates a directory. |
| `tree` | Lists the contents of a directory recursively. |
| `mv` | Move or rename files or directories. |
| `cp` | Copy files or directories. |
| `nano` | Terminal based text editor. |
| `which` | Returns the path to a file or link. |
| `find` | Searches for files in a directory hierarchy. |
| `updatedb` | Updates the locale database for existing contents on the system. |
| `locate` | Uses the locale database to find contents on the system. |
| `more` | Pager that is used to read STDOUT or files. |
| `less` | An alternative to `more` with more features. |
| `head` | Prints the first ten lines of STDOUT or a file. |
| `tail` | Prints the last ten lines of STDOUT or a file. |
| `sort` | Sorts the contents of STDOUT or a file. // aka sorts output in cli |
| `grep` | Searches for specific results that contain given patterns. |
| `grep - v` | Excludes pattern from results |
| `cut` | Removes sections from each line of files. |
| `tr` | Replaces certain characters. |
| `column` | Command-line based utility that formats its input into multiple columns. |
| `awk` | Pattern scanning and processing language. |
| `sed` | A stream editor for filtering and transforming text., replace a string in cli |
| `wc` | Prints newline, word, and byte counts for a given input. (input must be a file), use `-l` for simple length |
| `chmod` | Changes permission of a file or directory. |
| `chown` | Changes the owner and group of a file or directory.` |
| `<tool> --help` | Pulls from manual pages, only shows variable options |
| `ssh` \| connect with `ssh [username]@[IP address]` | Connects to other computer remotely. |

Want to know the meaning behind a tool not listed above? Use [https://explainshell.com/](https://explainshell.com/)



## Navigation

| **Command** | **Description** |
| ---- | ---- |
| `pwd` | Prints current directory |
| `ls -l` | List date and time and user created (byte sizes in block of 512) |
| `ls -la` | list all files including hidden files, with `-l` info |
| `cd -` | return to last directory |
| `.` | current directory |
| `..` | parent directory |
| `&&` | Separates two separate commands, allows you to combine multiple |
| `Ctrl + R` | Text search through command history |

## File Management

| **Command** | **Description** |
| ---- | ---- |
| `touch` | create a file/make a file |
| `mkdir -p` | create multiple parent directories at once//chain directory creation |
| `tree .` | visual//visualize directory tree of files underneath current directory eg. shell-session<br>├── info.txt<br>└── Storage<br>    └── local<br>        └── user<br>            └── documents<br> |
| `mv` | used to rename files and move them to a specified directory |
| `cp` | used to copy files to a directory |
| `tree . -t` | sorts files by last modified. See `tree . --help` for more info |
| `> <name>.txt` | redirects STDOUT to new file/ overwrites file if one exist |
| `2> <name>.txt` | redirects STERR to file |
| `>>` | appends STDOUT to file |
| `<<` | appends STIN to file |
| `\|` | redirects STDOUT |
|  |  |

## File & Directory Search

| **Command** | **Description** |  |
| ---- | ---- | ---- |
| `which` | returns path to file, used to check if a program exist on system |  |
| `find` | like which, but allows filtering |  |
| `find <> -type ` | Find a file (<>) with type, eg. `f` = file, |  |
| `find ./ -<option> <flag>` | find a file of x type in current directory |  |
| `find -name *.conf` | find all files with the .conf extension |  |
| `options for find` | `-user <>`, `-size <+xxk>` (+>-) + larger than, - Less than, `-newermt <yyyy-mm-dd>` (newer than x date), |  |
| `locate *.conf` | locates all .conf files in directory tree |  |
| `-exec ls -la {} \;` | flag for find command, `{}` are placeholder for results, `\;` escapes next character from being interpreted by shell |  |
| `2>/dev/null` | A *STDERR* aka Standard Error, redirection to the *null device*, ensures *no errors displayed in terminal* and discards all data sent to it |  |
* *with the find command, next entry needs to be directory path or file name, eg. `find / -name`, or `find vim`
* at the end of `find` command use `-exec ls -al {} \; 2>/dev/null` to properly filter results
* Its a “file descriptor” number relating to the standard outputs. At a high level there are three outputs:  
0 - Standard Input / stdin  
1 - Standard Output / stdout  
2 - Standard Error / stderr

Using `2>/dev/null` pipes any error messages to dev null but shows everything else. If you don’t use the `2`, the `>/dev/null` pipes all output to dev null, which means nothing is returned to the screen
aka removes errors from CLI window

## Filtering

| **Command** | **Description** |
| ---- | ---- |
| `grep "<>"` | only STDOUT things matching pattern in quotes |
| `cut -d":" -f<>` | separates out info at pattern in quotes, and in section f |
