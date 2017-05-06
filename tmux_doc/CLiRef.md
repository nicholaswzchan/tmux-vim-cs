_________ _____ _______________       _____
\_   ___ \\    \\___________   \____ / ____\     ~/.bash/cliref.md
/    \  \/|    | |   ||       _/ __ \  __\    copy/paste from whatisdb
\     \___|__  |_|_  ||    |   \  __/|_ |   http://pastebin.com/yGmGiDQX
 \________  /_____ \_||____|_  /____  /_|     yunga.palatino@gmail.com
 20160515 \/ 1527 \/         \/     \/
-------------------------------------------------------------------------------


alias CLIRef.txt='curl -s "http://pastebin.com/raw/yGmGiDQX" | less -i'
alias CLIRef.md='lynx "https://gist.github.com/yunga/b036ac9749524e312fb8#file-cliref-md"'


# Content #####################################################################

[Other Documentation]    | [Getting Help]           | [Interesting Pages]
-----------------------  | -----------------------  | -----------------------
[Shells]                 | [Network]                | [Directories]
[Terminal Tools]         | [Wireless]               | [Files]
.                        | [Network Monitor]        | [Pipes]
[Setup]                  | [Network Tunnels]        | [File Attributes]
[System]                 | [Network Scan]           | [File Find]
[Kernel]                 | [Network Capture]        | [File Compare]
[Init and Runlevels]     | [Network Filesystems]    | [Binary Information]
[Hardware]               | [Network Apps]           | [File Managers]
[Filesystem Tools]       | [Modem/Fax/GSM]          | [Viewers]
[Quotas]                 | [Network File Transfer]  | [Editors]
[Processes]              | [Browser]                | [Text Utilities]
[Performances]           | [RSS Reader]             | [Print]
[User Management]        | [Podcast]                | [Compression]
[User Information]       | [Chat]                   | [Encryption]
[Environment]            | [EMail]                  | [Backup]
[Security Context]       | [Newsgroups]             | [CD/DVD/BluRay]
.                        | [Websites]               | .
.                        | .                        | .
[Development]            | [ASCII Art]              | [Numbers and Math]
[Debugging]              | [Images]                 | [Date and Time]
[Revision Control]       | [Vector Graphics]        | [Schedule]
[Database]               | [3D]                     | [Office]
.                        | [Videos]                 | [Spelling]
[Games]                  | [Audio and Music]        | [Publishing]
[Screensavers]           | [Audio Players]          | [Task Managers]
[Other]                  | [Audio Editing]          | [Conversion]
[X Windows]              | [Midi]                   | .
[Funny]                  | [Text to Speech]         | .


# Other Documentation #########################################################


## Local directories

manpages       /usr/man/                      /usr/share/man/
infopages      /usr/info/                     /usr/share/info/
packages       /usr/doc/                      /usr/share/doc/
linux doc prj  /usr/doc/ldp/                  /usr/share/doc/ldp/
howtos         /usr/doc/howto/                /usr/share/doc/howto/
mini howtos    /usr/doc/howto/mini/           /usr/share/doc/howto/mini/
kernel         /usr/src/linux/documentation/
x window       /usr/x11r6/lib/x11/doc/
apache         /home/httpd/html/manual/       /var/www/html/manual/
latex doc      /usr/share/texmf/doc/latex/latex2e-html/
tex            /usr/share/texmf/doc/


## On the Web

- [The Linux man-pages project]  (https://www.kernel.org/doc/man-pages/)
- [Linux Manpages Online]        (http://man.cx/)
- [Ubuntu Manpage Repository]    (http://manpages.ubuntu.com/)
- [ArchWiki]                     (https://wiki.archlinux.org/)
- [Debian Wiki]                  (https://wiki.debian.org/)
- [Debian Admin's Handbook]      (https://debian-handbook.info/browse/stable/)
- [The Linux Documentation Project]      (http://tldp.org/)
- [GreyCat's wiki]               (http://mywiki.wooledge.org/)
- [Bash Hackers Wiki]            (http://wiki.bash-hackers.org/)
- [Rosetta Stone for Unix]       (http://bhami.com/rosetta.html)
- [Unix Toolbox]                 (http://cb.vu/unixtoolbox.xhtml)
- [Inconsolation]                (https://inconsolation.wordpress.com/)
- [Command Line Kung Fu]         (http://blog.commandlinekungfu.com/)
- [CommandLineFu]                (http://www.commandlinefu.com/)
- [Unix Mages]                   (http://unixmages.com/)
- [SuperUser]                    (https://superuser.com/)
- [Ask Ubuntu]                   (https://askubuntu.com/)
- [Unix on StackExchange]        (https://unix.stackexchange.com/)
- [Shell subreddits]
(https://www.reddit.com/r/bash+bashtricks+commandline+scriptswap+shell+zsh)


Tools:

- [ShellCheck]     (http://www.shellcheck.net/)
- [ExplainShell]   (http://explainshell.com/)
- [Coding Ground]  (http://www.tutorialspoint.com/codingground.htm)


## Manpages Sections on various platforms

Section  | General use on various unix platforms
--------- | ----------------------------------------------------------
0      | c library header files
1      | general commands
1c     | communications
1g     | graphics
1m     | maintenance, system administration commands and daemons
2      | system calls
3      | library functions, in particular the c standard library
3c     | c programming language
3f     | fortran programming language
3m     | miscellaneous programming routines
4      | special files, devices, drivers, formats and conventions
5      | file formats and conventions miscellanea
6      | games and screensavers
7      | miscellanea, special files, devices and drivers
8      | system administration commands and daemons
9      | kernel routines
l      | local, some programs install pages here instead of (1)
n      | tcl/tk keywords
x      | the x window system
?p     | perl scripts man pages
?posix | posix man pages
?fun   | funny command lines


# Getting Help ################################################################

Command            | Description
------------------- | -------------------------------------------------------
[man]              | an interface to the on-line reference manuals
[apropos]          | search the manual page names and descriptions
[whatis]           | display manual page descriptions
[whichman]         | search for a man page using a fault tolerant search
[info]             | read info documents
[help]             | shell built-in help
[debmany]          | show documentation from installed packages
[debian-reference] | open the post-installation user's guide in browser
[type]             | display information about command type
[konqueror]        | browse man:/info:/perldoc:/etc. thanks to kio
[popbugs]          | find release critical bugs in packages you use


# Interesting Pages ###########################################################

Manpage          | Description
----------------- | ---------------------------------------------------------
[intro.1]        | user commands
[intro.2]        | system calls
[intro.3]        | library functions
[intro.4]        | special files
[intro.5]        | file formats
[intro.6]        | games
[intro.7]        | overview/conventions/miscellany section
[intro.8]        | administration and privileged commands
[undocumented.7] | no manpage for this program, utility or function
[missing]        | missing manual pages
[LDP]            | linux documentation project with help and guides
[man-pages]      | conventions for writing linux man pages
[environ]        | user environment
[hier]           | description of the filesystem hierarchy
[file-hierarchy] | file system hierarchy overview
[capabilities]   | overview of linux capabilities
[signal]         | overview of signals
[standards]      | standards - c and unix standards
[units.7]        | units, kilo/kibi/mega, decimal and binary prefixes
[libc]           | overview of standard c libraries on linux
[posixoptions]   | optional parts of the posix standard
[errno]          | look up errno names and descriptions
[errno.3]        | number of last error
[undocumented.3] | undocumented library functions
[printf]         | formatted output conversion
[strftime]       | format date and time
[acl]            | access control lists
[ascii]          | report character aliases
[ascii.7]        | ascii characters in octal, decimal, and hexadecimal
[unicode]        | universal character set
[locale.7]       | description of multilanguage support
[readline]       | get a line from a user with editing (inputrc)
[terminfo]       | terminal capability data base
[bash]           | gnu bourne-again shell
[zsh]            | the z shell
[glob]           | globbing pathnames
[regex]          | posix.2 regular expressions
[pcrepattern]    | pcre - perl-compatible regular expressions
[pcresyntax]     | pcre - perl-compatible regex syntax summary
[perlintro]      | brief introduction and overview of perl
[perlcheat]      | perl 5 cheat sheet
[gittutorial]    | a tutorial introduction to git
[random]         | kernel random number source devices


# Shells ######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[sh]           | shell, the standard command language interpreter
[bash]         | gnu bourne-again shell
[fish]         | the friendly interactive shell
[zsh]          | the z shell
[fizsh]        | friendly interactive zshell
[ksh]          | kornshell, a command and programming language
[pdksh]        | legacy kornshell built on mksh
[mksh]         | mirbsd kornshell
[csh]          | a shell with c-like syntax
[tcsh]         | c shell with file name completion and cli editing
[ash]          | the almquist shell
[dash]         | the debian almquist shell
[rc]           | a shell for plan 9 and unix systems
[git-sh]       | a git shell (bash)
[shellcheck]   | analyzes shell scripts and points out typical issues


# Terminal Tools ##############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[screen]       | screen manager with vt100/ansi terminal emulation
[tmux]         | terminal multiplexer
[byobu]        | wrapper script for seeding configuration to screen/tmux
[dvtm]         | dynamic virtual terminal manager
[twin]         | textmode window environment
[dtach]        | program that emulates the detach feature of screen
[reptyr]       | reparent a running program to a new terminal/screen
[kibitz]       | allow two people to interact with one shell
[script]       | make typescript of terminal session
[scriptreplay] | play back typescripts, using timing information
[ttyrec]       | a tty recorder
[ttyplay]      | player of the tty session recorded by ttyrec
[clear]        | clear the screen
[reset]        | terminal initialization
[openvt]       | start a program on a new virtual terminal (vt)
[chvt]         | change foreground virtual terminal
[deallocvt]    | deallocate unused virtual terminals
[tty]          | display the name of the terminal connected to stdin
[stty]         | change and print terminal line settings
[tabs]         | set terminal tabs
[setterm]      | set terminal attributes
[tput]         | change terminal characteristics
[tic]          | the terminfo entry-description compiler
[toe]          | table of (terminfo) entries
[infocmp]      | compare or print out terminfo descriptions
[captoinfo]    | convert a termcap description into terminfo description
[infotocap]    | convert a terminfo description into termcap description


# Setup #######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[apt-get]      | apt package handling utility (debian)
[apt-config]   | apt configuration query program
[apt-cache]    | query the apt cache
[apt-file]     | apt package searching utility
[dlocate]      | program to view debian package information
[whohas]       | find packages in various distributions repositories
[apt-mark]     | mark/unmark a package as being automatically-installed
[debfoster]    | weed unnecessary debian packages
[deborphan]    | orphaned package finder
[dgrep]        | grep through files belonging to an installed package
[dglob]        | expand package names or files matching a pattern
[dpigs]        | show which installed packages occupy the most space
[popularity-contest]      | list the most popular packages on the system
[popcon-largest-unused]   | list size of unused packages on the system
[popbugs]                 | find release critical bugs in packages used
[which-pkg-broke]         | find which package might have broken another
[dpkg]                    | package manager for debian
[dpkg-reconfigure]        | reconfigure an already installed package
[debconf]                 | run a debconf-using program
[debconf-get-selections]  | output contents of debconf database
[debconf-set-selections]  | insert new values into the debconf database
[update-alternatives]     | maintain symlinks for default commands
[update-manager]          | graphical management of software updates
[dselect]      | debian package management frontend
[aptitude]     | high-level interface to the package manager
[synaptic]     | graphical management of software packages (xwindows)
[alien]        | convert or install an alien binary package (rpm, deb)
[smart]        | the smart package manager (apt/rpm/yum/etc)
[yum]          | yellowdog updater modified (redhat)
[rpm]          | rpm package manager (redhat)
[urpmi]        | rpm downloader/installer/dependency solver (mandriva)
[zypper]       | interface to zypp system management (opensuse)
[pacman]       | package manager utility (archlinux)
[yaourt]       | more than a frontend to pacman (archlinux)
[stow]         | software package installation manager (with symlinks)
[checkrestart] | check which processes need a restart after an upgrade


# System ######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[inxi]         | lists kernel/drivers/cpu/ram/gcc/xorg/desktop/etc.
[nmon]         | systems administrator, tuner, benchmark tool
[collectl]     | collects data that describes the current system status
[binstats]     | display statistics about programs and libraries
[uptime]       | view the system load and how long it has been running
[times]        | show process times for the shell and its child
[lsb_release]  | print distribution-specific information
[uname]        | print system/kernel information
[arch]         | print machine hardware name (same as uname -m)
[nproc]        | print the number of processing units available
[procinfo]     | display system statistics gathered from /proc
[mpstat]       | report processors related statistics
[saidar]       | a curses-based tool for viewing system statistics
[perf-top]     | system profiling tool
[lmbench]      | system benchmarks
[sysbench]     | a modular, multi-threaded benchmark tool
[sar]          | collect, report, or save system activity information
[hostid]       | print the numeric identifier for the current host
[free]         | display amount of free/used/swap memory in the system
[swapon]       | enable device and file for paging and swapping
[swapoff]      | disable devices and files for paging and swapping
[vmstat]       | report virtual memory statistics
[dstat]        | versatile tool for generating system resource stats
[iostat]       | report cpu and io statistics for dev, part and nfs
[iotop]        | simple top-like i/o monitor
[fio]          | flexible i/o tester
[blktrace]     | generate traces of the i/o traffic on block devices
[blockdev]     | call block device ioctls from the command line
[slabtop]      | display kernel slab cache information in real time
[tload]        | graphic representation of system load average
[logger]       | a shell interface to the syslog system log module
[logwatch]     | system log analyzer and reporter
[swatch]       | simple watcher
[imvirt]       | detects several virtualizations


# Kernel ######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[lsmod]        | program to show the status of modules in linux kernel
[insmod]       | simple program to insert a module into the linux kernel
[rmmod]        | simple program to remove a module from the linux kernel
[modinfo]      | program to show information about a linux kernel module
[modprobe]     | program to add and remove modules from the linux kernel
[modconf]      | a module configuration utility
[depmod]       | program to generate modules.dep and map files
[sysctl]       | configure kernel parameters at runtime


# Init and Runlevels ##########################################################

Command        | Description
--------------- | -----------------------------------------------------------
[initctl]      | upstart service configuration
[start]        | init daemon control tool
[stop]         | init daemon control tool
[status]       | init daemon control tool
[chkconfig]    | enable or disable system services
[service]      | run a system v init script
[sysv-rc-conf] | run-level configuration for sysv like init script links
[runlevel]     | output previous and current runlevel
[telinit]      | change system runlevel
[checkrestart] | check which processes need a restart after an upgrade
[systemctl]    | control the systemd system and service manager
[journalctl]   | query the systemd journal
[loginctl]     | control the systemd login manager
[halt]         | reboot or stop the system
[reboot]       | reboot or stop the system
[shutdown]     | shutdown or restart the system
[poweroff]     | reboot or stop the system


# Hardware ####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[x86info]      | display x86 cpu diagnostics
[dmesg]        | print kernel and driver messages
[hdparm]       | get/set sata/ide device parameters
[smartctl]     | control and monitor utility for smart disks
[badblocks]    | search a device for bad blocks
[setserial]    | get/set linux serial port information
[wvdial]       | ppp dialer with built-in intelligence
[lshw]         | list hardware
[lshal]        | lists all devices the hardware abstraction layer knows
[lsdev]        | display information about installed hardware
[lsblk]        | list block devices
[lsusb]        | list usb devices
[lspci]        | list all pci devices
[setpci]       | configure pci devices
[pnpdump]      | dump isa plug-and-play devices resource information
[isadump]      | examine isa registers
[scsiinfo]     | query information from a scsi device
[sginfo]       | access mode page information for a scsi/atapi device
[sg_map]       | displays mapping between linux sg and scsi devices
[udevadm]      | udev management tool
[ethtool]      | query or control network driver and hardware settings
[mii-tool]     | view, manipulate media-independent interface status
[dmidecode]    | dmi table decoder
[hwinfo]       | probe for hardware
[acpitool]     | acpi client, allowing you to query or set acpi values
[apm]          | interface with the apm subsystem
[alsamixer]    | soundcard mixer for alsa driver
[aumix]        | adjust audio mixer
[pactl]        | control a running pulseaudio sound server
[rexima]       | a curses-based (and command-line) mixer
[alsactl]      | advanced controls for alsa soundcard driver
[showkey]      | examine the codes sent by the keyboard
[loadkeys]     | load keyboard translation tables
[dumpkeys]     | dump keyboard translation tables
[setleds]      | set the keyboard leds
[imvirt]       | detects several virtualizations


# Filesystem Tools ############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[df]           | report file system disk space usage
[discus]       | print a report of disk space usage
[mount]        | mount a filesystem
[umount]       | unmount file systems
[mhddfs]       | combines a several mount points into a single one
[fusermount]   | mount and unmount fuse filesystems
[findmnt]      | find a filesystem
[mountpoint]   | see if a directory is a mountpoint
[sync]         | flush disk caches
[mkfs]         | build a linux file system
[tune2fs]      | adjust tunable filesystem parameters on ext2/ext3/ext4
[fsck]         | check and repair a linux file system
[badblocks]    | search a device for bad blocks
[debugfs]      | ext2/ext3/ext4 file system debugger
[fdisk]        | partition table manipulator for linux
[cfdisk]       | curses/slang based disk partition table manipulator
[parted]       | a partition manipulation program
[fdformat]     | low-level format a floppy disk
[mtools]       | utilities to access dos disks in unix
[lilo]         | install linux boot loader
[grub]         | install grand unified bootloader
[dd]           | convert/copy a file, write disk headers, boot records
[ddrescue]     | data recovery tool
[dcfldd]       | enhanced version of dd for forensics and security
[foremost]     | recover files using their headers/footers/structures
[photorec]     | recover lost files from hdisk, digital camera and cdrom
[safecopy]     | data recovery tool


# Quotas ######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[quota]        | display disk usage and limits
[repquota]     | summarize quotas for a filesystem
[setquota]     | set disk quotas
[edquota]      | edit user quotas
[quotaon]      | turn filesystem quotas on
[quotaoff]     | turn filesystem quotas off
[quotacheck]   | scan for disk usage, create, check, repair quota files
[convertquota] | convert quota from old file format to new one


# Processes ###################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[ps]           | report a snapshot of the current processes
[w]            | show who is logged on and what they are doing
[top]          | monitor processes
[htop]         | interactive process viewer
[atop]         | at computing system & process monitor
[gitps]        | a visual process viewer/killer (gnu interactive tools)
[glances]      | a cross-platform curses-based system monitoring tool
[pidstat]      | report statistics for linux tasks
[powertop]     | program to analyze power consumption on intel laptops
[prtstat]      | print statistics of a process
[pstree]       | display a tree of processes
[whowatch]     | console, interactive, process and users monitoring tool
[kill]         | send a signal to a process
[killall]      | kill all processes named proc
[pidof]        | find the process id of a running program
[pkill]        | signal processes based on name and other attributes
[pgrep]        | lookup processes based on name and other attributes
[skill]        | send a signal or report process status
[snice]        | send a signal or report process status
[nice]         | set/run a program with modified scheduling priority
[renice]       | alter priority of running processes
[ionice]       | set or get process i/o scheduling class and priority
[cpulimit]     | limits the cpu usage of a process
[taskset]      | retrieve or set a process cpu affinity
[setuid]       | run a command with a different uid
[setsid]       | run a program in a new session
[nohup]        | runs a command immune to hangups, outputs to a non-tty
[disown]       | shell built-in, removes each jobs from shell
[jobs]         | lists the active jobs
[bg]           | lists stopped or background jobs, resume a stopped job
[fg]           | brings the most recent job to foreground
[time]         | time a simple command
[timeout]      | run a command with a time limit
[uux]          | remote command execution
[uustat]       | uucp status inquiry and job control
[ipcs]         | report interprocess communication facilities status
[ipcrm]        | remove message, semaphore, or shared memory identifier


# Performances ################################################################

See Brendan D. Gregg [Linux Perf page]
(http://www.brendangregg.com/linuxperf.html)

Command        | Description
--------------- | -----------------------------------------------------------
[collectl]     | collects data that describes the current system status
[glances]      | a cross-platform curses-based system monitoring tool
[uptime]       | view the system load and how long it has been running
[mpstat]       | report processors related statistics
[lmbench]      | system benchmarks
[sysbench]     | a modular, multi-threaded benchmark tool
[sar]          | collect, report, or save system activity information
[free]         | display amount of free/used/swap memory in the system
[swapon]       | enable/disable device and file for paging and swapping
[vmstat]       | report virtual memory statistics
[dstat]        | versatile tool for generating system resource stats
[iostat]       | report cpu and io statistics for dev, part and nfs
[iotop]        | simple top-like i/o monitor
[fio]          | flexible i/o tester
[blktrace]     | generate traces of the i/o traffic on block devices
[slabtop]      | display kernel slab cache information in real time
[sysctl]       | configure kernel parameters at runtime
[hdparm]       | get/set sata/ide device parameters
[ps]           | report a snapshot of the current processes
[top]          | monitor processes
[htop]         | interactive process viewer
[pidstat]      | report statistics for linux tasks
[nice]         | set/run a program with modified scheduling priority
[renice]       | alter priority of running processes
[ionice]       | set or get process i/o scheduling class and priority
[taskset]      | retrieve or set a process cpu affinity
[sysdig]       | a system-level exploration and troubleshooting tool
[ltrace]       | a library call tracer
[strace]       | trace system calls and signals
[errno]        | look up errno names and descriptions
[explain]      | explain system call error messages
[stap]         | systemtap script translator driver
[ktap]         | lightweight script-based dynamic tracing tool for linux
[llttng]       | tracer control command line tool
[perf]         | performance analysis tools for linux
[tiptop]       | display hardware performance counters for linux tasks
[ethtool]      | query or control network driver and hardware settings
[iperf]        | perform network throughput tests
[pchar]        | perform network measurements along an internet path
[ping]         | check if host is reachable
[hping3]       | send (almost) arbitrary tcp/ip packets to network hosts
[traceroute]   | print the route packets trace to network host (see mtr)
[mtr]          | traceroute and ping programs diagnostic tool
[nicstat]      | print network traffic statistics
[netstat]      | print connections, routing, masquerade, multicast stats
[ss]           | another utility to investigate sockets
[socklist]     | display list of open sockets
[sockstat]     | list open sockets
[iptraf]       | interactive colorful ip lan monitor
[tcpdump]      | dump traffic on a network
[darkstat]     | network statistics gatherer
[justniffer]   | an extensive tcp flow sniffer
[snmpget]      | communicates with a network using snmp get requests
[lldptool]     | manage the lldp settings and status of lldpad
[tune2fs]      | adjust tunable filesystem parameters on ext2/ext3/ext4
[dd]           | convert/copy a file, write disk headers, boot records
[siege]        | an http/https stress tester
[tsung]        | distributed multi-protocol load testing tool


# User Management #############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[adduser]      | add a user or group to the system
[useradd]      | create a new user or update default user information
[userdel]      | delete a user account and related files
[usermod]      | modify a user account
[newusers]     | update and create new users in batch
[groupadd]     | create a new group
[groupdel]     | delete a group
[groupmod]     | modify a group definition on the system
[newgrp]       | log in to a new group
[chage]        | change user password expiry information
[chfn]         | change real user name and information
[chsh]         | change login shell
[passwd]       | change user password


# User Information ############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[id]           | print real and effective user and group ids
[groups]       | print group names a user is in
[sa]           | summarizes accounting information
[ac]           | print statistics about users connect time
[who]          | print all usernames currently logged in
[whowatch]     | console, interactive, process and users monitoring tool
[whoami]       | print effective userid
[rwho]         | determine all users logged on your local network
[w]            | show who is logged on and what they are doing
[last]         | show listing of last logged in users
[lastb]        | show listing of bad loggin attemps
[lastlog]      | reports recent login of all users or of a given user
[lastcomm]     | print information about previously executed commands
[users]        | print the user names of users currently logged in
[logname]      | print the login name of a user
[talk]         | talk to another user
[ytalk]        | multi-user chat program
[write]        | send a message to another user
[wall]         | write a message to users
[mesg]         | control write access to your terminal


# Environment #################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[printenv]     | print all or part of environment
[env]          | run a program in a modified environment
[locale]       | get locale-specific information
[localedef]    | compile locale definition files


# Security Context ############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[su]           | change user id or become superuser
[sudo]         | execute a command as another user
[sudoedit]     | edit one or more files as another user
[op]           | grant trusted users access to certain root operations
[runcon]       | run command with specified security context (selinux)
[chcon]        | change file security context (selinux)
[chroot]       | run command or interactive shell with special root dir
[schroot]      | securely enter a chroot environment
[rarun2]       | run programs with different env/args/perms/dirs/etc


# Development #################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[perl]         | the perl language interpreter
[perldoc]      | look up perl documentation in pod format
[perltidy]     | a perl script indenter and reformatter
[perlcritic]   | command-line interface to critique perl source
[perlbug]      | how to submit bug reports on perl
[cpan]         | easily interact with cpan from the command line
[txt2regex]    | a regular expression wizard
[ruby]         | interpreted object-oriented scripting language
[irb]          | interactive ruby
[gem]          | the front end to rubygems
[python]       | an interpreted, object-oriented programming language
[pydoc]        | the python documentation tool
[pycompile]    | byte compile python source files
[pychecker]    | program to check python scripts for common mistakes
[ghc]          | the glasgow haskell compiler
[ghci]         | the glasgow haskell compiler
[lua]          | lua interpreter
[luac]         | lua compiler
[luadoc]       | generate documentation from files
[luarocks]     | module deployment system for lua
[node]         | server-side javascript
[js_beautify]  | command tool to beautify your javascript files
[jq]           | command-line json processor
[jsoncat]      | display json data
[jsonlint]     | json syntax validator and formatter tool
[java]         | the java application launcher
[javac]        | java programming language compiler
[javadoc]      | the java api documentation generator
[jardiff]      | visualise api differences between two jar files
[php]          | php command line interface cli
[clisp]        | ansi common lisp compiler, interpreter and debugger
[fort77]       | fortran compiler
[f2c]          | convert fortran 77 to c or c++
[fc]           | frontend script to the f2c fortran compiler
[nasm]         | the netwide assembler, a portable 80x86 assembler
[yasm]         | the yasm modular assembler
[as]           | the portable gnu assembler
[rasm2]        | assemble and disassemble files or hexpair strings
[gcc]          | gnu project c and c++ compiler
[gprof]        | display call graph profile data
[ld]           | the gnu linker
[c99]          | compile standard ansi c programs
[cpp]          | the c preprocessor
[make]         | gnu make utility to maintain groups of programs
[dmake]        | maintain program groups, or interdependent files
[cmake]        | cross-platform makefile generator
[cxref]        | generate a c-language program cross-reference table
[ctags]        | generate tag file for emacs, vi
[cflow]        | generate a c-language flowgraph
[cscope]       | interactively examine a c program
[sloccount]    | count source lines of code (sloc)
[cloc]         | count lines of source code and comments
[pepper]       | repository statistics and report tool
[astyle]       | indentation and reformatting filters c, c++, c#, java
[indent]       | reformat a c program, inserting or deleting whitespace
[bcpp]         | make c++ beautifier
[uncrustify]   | c, c++, c#, d, java and pawn source code beautifier
[xmlstarlet]   | command line xml/xslt toolkit
[xmllint]      | command line xml tool
[xgrep]        | search content of xml file via xpath or curstom search
[xmlcatalog]   | parse and manipulate xml or sgml catalog files
[xalan]        | process xml documents with xslt stylesheets
[xmlindent]    | xml stream reformatter
[tidy]         | validate, correct, and pretty-print html files
[csstidy]      | css parser and optimiser
[highlight]    | universal code highlighter converter (html, rtf, ...)
[lex]          | generate programs for lexical tasks
[strip]        | remove unnecessary information from executable files
[m4]           | macro processor
[yacc]         | yet another compiler compiler
[flex]         | lexical analyser, generates code for pattern-matching
[gencat]       | generate a formatted message catalog
[getconf]      | get configuration values
[errno]        | look up errno names and descriptions
[explain]      | explain system call error messages


# Debugging ###################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[gdb]          | the gnu debugger
[r2]           | advanced hexadecimal editor, disassembler and debugger
[elfsh]        | the elsf shell
[e2dbg]        | the embedded elf debugger
[readelf]      | displays information about elf files
[rabin2]       | get information about elf/pe/mz/class
[objdump]      | display information from object files
[objcopy]      | copy and translate object files
[nm]           | list symbols from object files
[lsof]         | list open files/streams/sockets/etc
[lslk]         | list local locks
[fuser]        | identify processes using files or sockets
[trace-cmd]    | interacts with ftrace linux kernel internal tracer
[trace-cmd-list] | list available plugins, events or options for ftrace
[pstack]       | print a stack trace of running processes
[dtrace]       | tune and troubleshoot programs and system (systemtap)
[sysdig]       | a system-level exploration and troubleshooting tool
[etrace]       | the embedded elf tracer
[eresi]        | the eresi reverse engineering software interface
[errno]        | look up errno names and descriptions
[explain]      | explain system call error messages
[strace]       | trace system calls and signals
[ltrace]       | a library call tracer
[mtrace]       | interpret output from malloc_trace
[xtrace]       | trace communication between x11 client and server
[stap]         | systemtap script translator driver
[ktap]         | lightweight script-based dynamic tracing tool for linux
[llttng]       | tracer control command line tool
[perf]         | performance analysis tools for linux
[perf-stat]    | run a command and gather performance counter statistics
[perf-list]    | list all symbolic event types
[tiptop]       | display hardware performance counters for linux tasks
[babeltrace]   | babeltrace trace viewer and converter for (ctf)
[memdump]      | memory dumper
[scanmem]      | locate and modify a variable in an executing process
[crash]        | analyze linux crash dump data or a live system
[binwalk]      | binary image search tool
[strings]      | extract printable strings
[ident]        | identify rcs keyword strings in files
[pmap]         | report memory map of a process
[ldd]          | print shared library dependencies
[ldconfig]     | configure dynamic linker run-time bindings
[ld.so]                        | dynamic linker-loader
[/lib/ld-linux.so.2]           | dynamic linker-loader
[/lib64/ld-linux-x86-64.so.2]  | dynamic linker-loader


# Revision Control ############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[rcs]          | change rcs file attributes
[ci]           | check in rcs revisions
[co]           | check out rcs revisions
[git]          | the stupid content tracker
[tig]          | text-mode interface for git
[bzr]          | bazaar next-generation distributed version control
[cvs]          | concurrent versions system
[darcs]        | an advanced revision control system
[hg]           | mercurial source code management system
[svn]          | subversion command line client tool


# Database ####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[sqlite3]      | command line interface for sqlite version 3
[sqlite]       | a command line interface for sqlite
[psql]         | postgresql interactive terminal
[mysql]        | the mysql command-line tool
[sql]          | execute a command on a database determined by a dburl
[rrdtool]      | round robin database tool and grapher


# Network #####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[ip]           | show/manip routing, devices, policy routing and tunnels
[tc]           | show/manipulate traffic control settings
[ifconfig]     | set/display network information
[ifdata]       | get network interface info without ifconfig parsing
[ifstat]       | report interface statistics
[ifdown]       | stop a network interface
[ifup]         | bring a network interface up
[ethtool]      | query or control network driver and hardware settings
[mii-tool]     | view, manipulate media-independent interface status
[nmcli]        | command-line tool for controlling networkmanager
[nmtui]        | text user interface for controlling networkmanager
[nm-tool]      | utility to report networkmanager state and devices
[iperf]        | perform network throughput tests
[nuttcp]       | network performance measurement tool
[pchar]        | perform network measurements along an internet path
[route]        | show/manipulate the ip routing table
[hostname]     | print the system hostname
[domainname]   | show or set the system nis/yp domain name
[dnsdomainname]| show the system dns domain name
[nisdomainname]| show or set the system's nis domain name
[ypdomainname] | show or set the system's yp domain name
[whois]        | client for the whois directory service
[dnstracer]    | trace a chain of DNS servers to the source
[ping]         | check if host is reachable
[hping3]       | send (almost) arbitrary tcp/ip packets to network hosts
[traceroute]   | print the route packets trace to network host (see mtr)
[tracepath]    | traces path to a network host, discovering mtu along
[mtr]          | traceroute and ping programs diagnostic tool
[netstat]      | print connections, routing, masquerade, multicast stats
[lsof]         | list open files/streams/sockets/etc
[ss]           | another utility to investigate sockets
[host]         | dns lookup utility
[dig]          | dns lookup utility
[nslookup]     | query internet name servers interactively
[zonecheck]    | dns zone checking tool
[nc]           | netcat, arbitrary tcp and udp connections and listens
[cryptcat]     | twofish encryption enabled version of nc
[ncat]         | concatenate and redirect sockets
[socat]        | multipurpose relay (socket cat)
[faucet]       | a fixture for a bsd network pipe (netpipes)
[hose]         | the client end of a bsd network pipe (netpipes)
[arping]       | arp find out ethernet address by first arping then arp
[arp]          | manipulate the system arp cache
[arpwatch]     | keep track of ethernet/ip address pairings
[arpspoof]     | intercept packets on a switched lan
[rarp]         | manipulate the system rarp table
[ufw]          | program for managing a netfilter firewall
[iptables]           | administration tool for ipv4 filtering and nat
[ip6tables]          | ipv6 packet filter administration
[iptables-save]      | dump iptables rules to stdout
[ip6tables-save]     | dump iptables rules to stdout
[iptables-restore]   | restore ip tables
[ip6tables-restore]  | restore ipv6 tables
[iptstate]           | top-like display of ip tables state table entries
[ipchains]     | control the packet filter/firewall (see iptables)
[ipcalc]       | ipv4 netmask/broadcast/etc calculator
[ipv6calc]     | a small utility to manipulate ipv6 addresses
[sipcalc]      | ip subnet calculator
[subnetcalc]   | ipv4/ipv6 subnet calculator
[tcpkill]      | kill tcp connections on a lan
[tcpnice]      | slow down tcp connections on a lan
[sshow]        | ssh traffic analysis tool
[sshmitm]      | ssh monkey-in-the-middle
[smbclient]    | ftp-like client to access smb/cifs resources on servers
[ntptrace]     | trace a chain of ntp servers back to the primary source
[snmpget]      | communicates with a network using snmp get requests
[snmpwalk]     | retrieve a management values subtree using snmp getnext
[snmpcmd]      | behaviour common to most of the net-snmp commands
[lldpad]       | link layer discovery protocol (lldp) agent daemon
[lldptool]     | manage the lldp settings and status of lldpad
[suricata]     | next generation intrusion detection and prevention tool


# Wireless ####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[iw]           | show/manipulate wireless devices and configuration
[iwconfig]     | configure a wireless network interface
[iwlist]       | detailed information about a wireless interface
[iwevent]      | show wireless events generated by drivers and hardware
[iwgetid]      | report essid, nwid, ap/cell address of wireless network
[wavemon]      | a wireless network monitor
[kismet]       | wireless sniffing and monitoring


# Network Monitor #############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[ntop]         | display top network users
[ntopng]       | display top network users
[nload]        | displays the current network usage
[cbm]          | display the current traffic on all network devices
[sntop]        | top-like console network status tool
[iftop]        | display bandwidth usage on an interface by host
[jnettop]      | view hosts/ports taking up the most network traffic
[bmon]         | bandwidth monitor and rate estimator
[bwn-ng]       | a live monitor for network and disk io
[speedometer]  | display the rate of data across a network connection
[netload]      | network device load monitor
[nethogs]      | a small net top tool, displays usage per process
[slurm]        | yet another network load monitor
[vnstat]       | a console-based network traffic monitor
[nicstat]      | print network traffic statistics
[pktstat]      | display packet activity
[iptraf]       | interactive colorful ip lan monitor
[netwatch]     | ethernet internet protocol monitor
[trafshow]     | full screen show network traffic
[tcptrack]     | monitor tcp connections on the network
[tcpreen]      | tcp stream monitoring tool
[wavemon]      | a wireless network monitor


# Network Tunnels #############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[ip]           | show/manip routing, devices, policy routing and tunnels
[ip-tunnel]    | tunnel configuration
[stunnel]      | universal ssl tunnel
[ptunnel]      | tunnel tcp connections over icmp packets
[udptunnel]    | tunnel udp packets over a tcp connection


# Network Scan ################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[nmap]         | network exploration tool and security / port scanner
[ndiff]        | utility to compare the results of nmap scans
[scapy]        | interactive packet manipulation tool
[nping]        | network packet generation tool / ping utility
[arp-scan]     | the arp scanner
[sslscan]      | fast ssl scanner
[xprobe2]      | a remote active operating system fingerprinting tool
[p0f]          | identify remote systems passively


# Network Capture #############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[wireshark]    | interactively dump and analyze network traffic
[tshark]       | dump and analyze network traffic
[scapy]        | interactive packet manipulation tool
[dumpcap]      | dump network traffic
[tcpspy]       | tcp/ip connection monitor
[tcpdump]      | dump traffic on a network
[tcptrace]     | a tcp connection analysis tool
[tcpick]       | tcp stream sniffer and connection tracker
[tcpflow]      | tcp flow recorder
[snort]        | packet sniffer/logger and intrusion detection system
[pcapdump]     | dedicated packet capture utility
[pcapip]       | filter a pcap for ip addresses
[pcappick]     | pick specific frames out of a pcap file by number
[pcapuc]       | filter a pcap for ip addresses
[ettercap]     | sniffer/content filter for man in the middle attacks
[ngrep]        | network grep
[tetheral]     | dump and analyze network traffic
[sniffit]      | packet sniffer and monitoring tool
[httpry]       | http logging and information retrieval tool
[dsniff]       | password sniffer (lots of protocols)
[kismet]       | wireless sniffing and monitoring

# Network Filesystems #########################################################

Command        | Description
--------------- | -----------------------------------------------------------
[exportfs]     | maintain table of exported nfs file systems
[showmount]    | show mount information for an NFS server
[nfsstat]      | list nfs statistics
[nfsiostat]    | report input/output statistics for nfs
[sshfs]        | filesystem client based on ssh
[curlftpfs]    | mount a ftp host as a local directory
[flickrfs]     | virtual filesystem for flickr photosharing service


# Network Apps ################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[ssh]          | openssh ssh client (remote login program)
[cssh]         | cluster admin tool, multiple ssh connection
[ssh-copy-id]  | install public key in a remote machine authorized_keys
[ssh-keygen]   | authkey generation, management and conversion
[rsh]          | remote shell
[crsh]         | cluster admin tool, multiple rsh connection
[rlogin]       | openssh ssh client (remote login program)
[telnet]       | log into remote hosts
[ctel]         | cluster admin tool, multiple telnet connection
[ccon]         | cluster admin tool, multiple console connection
[uux]          | remote command execution
[uustat]       | uucp status inquiry and job control
[finger]       | user information lookup program


# Modem/Fax/GSM ###############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[minicom]      | friendly serial communication program
[efax]         | send/receive faxes with class 1, 2 or 2.0 fax modem
[mgetty]       | smart data/fax modem getty
[fax]          | fax sending and receiving with mgetty+sendfax
[sendfax]      | submit a facsimile job for transmission
[sendpage]     | submit a pager job for transmission
[faxstat]      | for hylafax facsimile server status
[faxspool]     | queue and convert files for faxing with sendfax
[faxq]         | display fax jobs queued by faxspool
[faxrunq]      | send fax jobs queued by faxspool
[faxrm]        | remove fax jobs queued by faxspool
[faxalter]     | alter parameters of a queued hylafax job
[fax2ps]       | convert a tiff facsimile to compressed postscript
[faxcover]     | generate postscript cover page for outgoing facsimile
[faxmail]      | hylafax mail-to-fax (postscript) gateway application
[textfmt]      | convert ascii text to postscript for facsimile
[gammu]        | does some neat things with your cellular phone or modem


# Network File Transfer #######################################################

Command        | Description
--------------- | -----------------------------------------------------------
[curl]         | transfer a url (swiss army tool)
[wget]         | the non-interactive network downloader
[httrack]      | offline browser : copy websites to a local directory
[linkchecker]  | check html documents and websites for broken links
[woof]         | a small, simple, stupid webserver to share files
[wput]         | wget-like ftp-uploader
[sftp]         | secure file transfer program
[ncftp]        | browser program for the file transfer protocol
[ncftpget]     | internet file transfer program for scripts
[ncftpput]     | internet file transfer program for scripts
[ftp]          | copy files between hosts
[lftp]         | sophisticated file transfer program
[scp]          | securely copy files between hosts
[rcp]          | remote file copy
[uucp]         | system-to-system copy
[mulk]         | parallel network downloader with filtering and metalink
[axel]         | light download accelerator (best imo)
[aria]         | fast download utility (http, ftp, bittorrent, metalink)
[aria2c]       | the ultra fast download utility http/ftp/bt/metalink
[ctorrent]     | download bittorrent files from command line
[rtorrent]     | a bittorrent client for ncurses
[mktorrent]    | simple bittorrent metainfo file creator
[bittorrent-downloader] | download files using a scatter-gather network
[btdownloadcurses]      | download files using a scatter-gather network
[amulecmd]              | console-based program to control amule
[get_flash_videos]      | downloader for flash-based video sites
[rmtpdump]     | rtmp streaming media client
[youtube-dl]   | download video from youtube or other video platforms
[quvi]         | query media tool for parsing flash streams url
[cclive]       | downloading media streams from youtube and similars
[nc]           | netcat, arbitrary tcp and udp connections and listens
[cryptcat]     | twofish encryption enabled version of nc
[ncat]         | concatenate and redirect sockets
[socat]        | multipurpose relay (socket cat)
[faucet]       | a fixture for a bsd network pipe (netpipes)
[hose]         | the client end of a bsd network pipe (netpipes)
[trickle]      | a lightweight userspace bandwidth shaper


# Browser #####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[lynx]         | a general purpose, text-only browser for the www
[links]        | lynx-like alternative character mode www browser
[links2]       | lynx-like alternative character mode www browser
[elinks]       | lynx-like alternative character mode www browser
[netrik]       | the antrik internet browser
[w3m]          | a text based web browser and pager
[edbrowse]     | text editor and web browser
[httrack]      | offline browser : copy websites to a local directory
[surfraw]      | fast search/bookmarks access to various www clients
[gopher]       | connect to gopher document server


# RSS Reader ##################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[newsbeuter]   | an rss feed reader for text terminals
[rsstail]      | console based rss news reader
[canto]        | an ncurses rss reader
[raggle]       | console rss aggregator
[olive]        | console rss reader
[rawdog]       | rss aggregator without delusions of grandeur
[nrss]         | an ncurses rss reader
[snownews]     | console rss newsreader


# Podcast #####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[hpodder]      | scan and download podcasts
[podget]       | simple tool to automate downloading of podcasts
[podracer]     | a podcast aggregator with bittorrent support


# Chat ########################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[centerim]     | text mode based im client for linux
[finch]        | instant messaging client (frontend to libpurple)
[pork]         | console-based aol instant messenger & irc client
[freetalk]     | a console based jabber client
[mcabber]      | a simple jabber console client
[ekg]          | gadu-gadu compatible client
[BitchX]       | an advanced internet relay chat client
[irssi]        | a modular irc client for unix
[weechat]      | wee enhanced environment for chat
[bitlbee]      | irc gateway to im chat networks
[epic5]        | internet relay chat client for unix like systems
[tinyirc]      | basic irc commands and an curses-based interface
[ii]           |  a minimalistic fifo and filesystem based irc client
[sic]          | an extremly fast, small and simple irc client
[tircd]        | an ircd proxy to the twitter api
[talk]         | talk to another user
[ytalk]        | multi-user chat program
[write]        | send a message to another user
[wall]         | write a message to users
[mesg]         | control write access to your terminal


# EMail #######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[mail]         | minimal client to send and receive mail
[mailx]        | send and receive internet mail
[msmtp]        | an smtp client
[mutt]         | text-based email client
[alpine]       | internet news and email
[notmuch]      | thread-based email index, search, and tagging
[cone]         | read and send e-mail messages
[elmo]         | the electronic mail operator
[fetchyahoo]   | retrieve mail from yahoo webmail service
[urlscan]      | browse the urls in an email message from a terminal


# Newsgroups ##################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[slrn]         | an easy to use nntp / spool based newsreader
[trn]          | threaded read news program
[tin]          | usenet newsreader
[nn]           | efficient net news interface (no news is good news)


# Websites ####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[shell-fm]     | console-based player for last.fm radio streams
[google]       | command-line access to (some) google services
[gcalcli]      | google calendar command line interface
[episoder]     | tv show reminder from epguides.com and thetvdb.com
[youtube-dl]   | download video from youtube or other video platforms
[get_flash_videos] | downloader for various flash-based video sites
[quvi]         | query media tool for parsing flash streams url
[cclive]       | downloading media streams from youtube and similars
[twyt]         | command line twitter client
[bti]          | send a tweet to twitter.com from the command line
[tircd]        | an ircd proxy to the twitter api
[twidge]       | microblogging client for twitter, identica
[weather]      | obtain weather conditions and forecasts


# Directories #################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[cd]           | change directory
[pwd]          | print name of current/working directory
[mkdir]        | make directories
[rmdir]        | remove empty directories
[tree]         | list contents of directories in a tree-like format
[dirdiff]      | display diff and merge changes between directories
[pushd]        | sh: add directories to stack
[popd]         | sh: remove dir from stack, changes to the new top dir
[dirs]         | display directory stack (pushd/popd)


# Files #######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[ls]           | list directory contents and files
[dir]          | briefly list files
[vdir]         | verbosely list directory contents
[tree]         | list contents of directories in a tree-like format
[dircolors]    | color setup for ls
[df]           | report file system disk space usage
[dfc]          | display file system space usage using graphs and colors
[pydf]         | report colourised filesystem disk space usage
[du]           | estimate file space usage
[ncdu]         | ncurses disk usage
[agedu]        | correlate disk usage and last-access times
[touch]        | create file, change file timestamps
[fallocate]    | preallocate or deallocate space to a file
[truncate]     | shrink or extend the size of a file
[dd]           | convert/copy a file, write disk headers, boot records
[cp]           | copy files and directories
[mcp]          | copy files by wildcard patterns
[qcp]          | copy files editing the names in a text editor
[install]      | copy files and set attributes
[mv]           | move (rename) files
[mmv]          | move files by wildcard patterns
[rename]       | rename files by replacing expressions
[prename]      | renames multiple files with perl expression
[qmv]          | rename files editing the names in a text editor
[convmv]       | converts filenames from one encoding to another
[vidir]        | edit a directory in your text editor
[detox]        | clean up filenames
[rm]           | remove files or directories
[unlink]       | call the unlink function to remove the specified file
[shred]        | overwrite a file to hide its contents, and  delete it
[wipe]         | securely erase files from magnetic media
[gitwipe]      | an utility for wiping files (gnu interactive tools)
[ln]           | make filesystem links
[mln]          | link files by wildcard patterns
[sln]          | link files (statically linked)
[link]         | create a hard link to a file
[readlink]     | print value of a symbolic link or canonical file name
[cleanlinks]   | remove dangling symbolic links and empty directories
[hardlink]     | Hardinks multiple copies of a file
[stow]         | software package installation manager (with symlinks)
[mkfifo]       | create named pipe
[mknod]        | make block or character special files
[mktemp]       | create a temporary file or directory
[flock]        | manage locks from shell scripts
[basename]     | strip directory and suffix from filenames
[dirname]      | convert a full pathname to just a path
[realpath]     | print the resolved path
[pathchk]      | check whether file names are valid or portable
[inotifywatch] | gather filesystem access statistics using inotify
[inotifywait]  | wait for changes to files using inotify
[trash]        | trash utility compliant with freedesktop.org
[trash-list]   | list trashed files
[trash-restore]| restore for command line trash utility
[trash-empty]  | empty for command line trash utility


# Pipes #######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[tee]          | read from stdin, write to stdout and files
[multitee]     | send multiple inputs to multiple outputs
[pee]          | tee standard input to pipes
[xargs]        | build and execute command lines from standard input
[parallel]     | run programs in parallel
[mispipe]      | pipe two commands returning the exit status of the first
[pv]           | monitor the progress of data through a pipe
[sponge]       | soaks up all standard input and write to a file after
[stdbuf]       | run command with modified buffering for its stdstreams
[ifne]         | run command if the standard input is not empty
[ts]           | timestamp input
[vipe]         | insert a text editor into a pipe


# File Attributes #############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[umask]        | set default file protections
[stat]         | display file attributes or file system status
[touch]        | change file timestamps
[chown]        | change file owner and group
[chgrp]        | change group ownership
[chmod]        | change file mode bits
[chattr]       | change advanced file attributes on a linux file system
[lsattr]       | list advanced file attributes on a ext file system
[getfattr]     | get extended attributes of filesystem objects
[setfattr]     | set extended attributes of filesystem objects
[getfacl]      | get file access control lists
[setfacl]      | set file access control lists
[test]         | check file types and compare values


# File Find ###################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[find]         | search for files in a directory hierarchy
[ftff]         | fault tolerant file find utility
[updatedb]     | update a database for m/slocate
[locate]       | locate files via index (m/slocate)
[doodle]       | a tool to search the meta-data in your files
[which]        | locate a command
[whereis]      | locate binary, source, and manual page for a command
[fdupes]         | finds duplicate files in a given set of directories
[rdfind]         | finds duplicate files
[findimagedupes] | finds visually similar or duplicate images
[hardlink]       | Hardinks multiple copies of a file


# File Compare ################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[diff]         | compare files line by line
[zdiff]        | compare compressed files
[bzdiff]       | compare compressed files
[diff3]        | compare three files line by line
[diffstat]     | make histogram from diff-output
[rfcdiff]      | compare rfcs or internet drafts or any other text files
[merge]        | three-way file merge
[wdiff]        | display word differences between text files
[sdiff]        | side-by-side merge of file differences
[mcdiff]       | visual shell for unix-like systems
[ndiff]        | utility to compare the results of nmap scans
[bsdiff]       | generate a patch between two binary files
[rdiff]        | binary diff tool for signature-based differences
[quilt]        | tool to manage series of patches
[bspatch]      | apply a patch built with bsdiff
[patch]        | apply a diff file to an original
[unify]        | transforms context diffs into unidiffs, or vice-versa
[combine]      | combine lines from two files using boolean operations
[comm]         | compare two sorted files line by line
[cmp]          | compare two files byte by byte
[zcmp]         | compare compressed files
[bzcmp]        | compare compressed files
[cksum]        | checksum and count the bytes in a file
[sum]          | checksum and count the blocks in a file
[md5sum]       | compute and check md5 message digest
[md5pass]      | create an md5 password hash
[shasum]       | print or check sha checksums
[rhash]        | print or check ed2k, bittorrent, dc++, and other hashes
[rahash2]      | block based hashing utility


# Binary Information ##########################################################

Command        | Description
--------------- | -----------------------------------------------------------
[file]         | determine file type
[mimetype]     | identify file types
[mimeopen]     | open files by mimetype
[mediainfo]    | display information about audio/video files
[rifle]        | ranger's file opener with special file type checking
[extract]      | determine meta-information about a file
[od]           | dump files in octal and other formats
[xxd]          | make a hexdump or do the reverse (patch)
[hexdump]      | ascii, decimal, hexadecimal, octal dump
[mcview]       | midnight commander internal file viewer (ascii/hex)
[dhex]         | hex editor with a diff mode
[hexedit]      | view and edit files in hexadecimal or in ascii
[tweak]        | efficient hex editor
[hte]          | executable's editor
[bsdiff]       | generate a patch between two binary files
[bspatch]      | apply a patch built with bsdiff
[rafind2]      | find byte patterns into files
[rahash2]      | block based hashing utility
[radiff2]      | unified binary diffing utility
[hexdiff]      | hexadecimal visual diff for binary files
[bbe]          | sed-like editor for binary files
[dd]           | convert/copy a file, write disk headers, boot records
[ddrescue]     | data recovery tool
[foremost]     | recover files using their headers/footers/structures


# File Managers ###############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[mc]           | midnight commander, visual shell for unix-like systems
[gitfm]        | gnu interactive tools file manager
[ranger]       | visual file manager
[vifm]         | a ncurses based file manager with vi like keybindings
[clex]         | file manager
[vfu]          | text-mode file manager for unix/linux
[pilot]        | simple file browser in the style of the alpine composer


# Viewers #####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[mcview]       | midnight commander internal file viewer (ascii/hex)
[gitview]      | an ascii/hex file viewer (gnu interactive tools)
[cat]          | concatenate files and print on the standard output
[mad]          | append files by wildcard patterns
[tac]          | concatenate and print files in reverse
[rev]          | reverse characters of lines in file or files
[spc]          | colorizes text for terminals and html (supercat)
[lolcat]       | rainbow coloring for text
[tac]          | concatenate and print files in reverse
[combine]      | combine lines from two files using boolean operations
[lnav]         | ncurses-based log file viewer
[ccze]         | a robust log colorizer
[zcat]         | expand and concatenate data (gz)
[bzcat]        | decompresses files to stdout (bz2)
[xzcat]        | decompresses files to stdout (xz, lzma)
[less]         | opposite of more
[zless]        | file perusal filter for crt viewing of compressed text
[bzless]       | file perusal filter for crt viewing of bzip2
[most]         | browse or page through a text file
[more]         | file perusal filter for viewing
[zmore]        | file perusal filter for crt viewing of compressed text
[bzmore]       | file perusal filter for crt viewing of bzip2
[pg]           | browse pagewise through text files


# Editors #####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[mcedit]       | internal file editor of gnu midnight commander
[vi]           | text editor
[vim]          | text editor
[cream]        | set of macros making vim easier to use for beginners
[emacs]        | gnu project emacs text editor
[nano]         | a small and friendly text editor
[jed]          | programmers editor
[aee]          | another easy editor
[diakonos]     | a customizable, usable console-based text editor
[pico]         | simple text editor in the style of the alpine composer
[zile]         | zile is lossy emacs


# Text Utilities ##############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[truncate]     | shrink/extend the size of a file to the specified size
[head]         | output the first 10 lines of file
[tail]         | output the last 10 lines of file
[multitail]    | browse through several files at once
[since]        | display content of a file since the last time
[split]        | split a file into fixed-size pieces
[lxsplit]      | a simple tool for splitting and joining split files
[nl]           | number lines of files
[wc]           | print newline, word, and byte counts for each file
[ex]           | text editor
[ed]           | the standard text editor
[red]          | line-oriented text editor
[edbrowse]     | text editor and web browser
[look]         | display lines beginning with a given string
[grep]         | search files for lines of text matching a pattern
[egrep]        | print lines matching a pattern (-e)
[fgrep]        | search files for lines that match a fixed string (-f)
[rgrep]        | print lines matching a pattern recursively (-r)
[agrep]        | search a file for a string with approximate matching
[sgrep]        | search a file for a structured pattern
[zgrep]        | search compressed files for a regular expression
[bzgrep]       | search bzip2 compressed files for a regular expression
[ack]          | ack-grep is designed as a replacement for grep
[ag]           | the silver searcher - like ack, but faster
[urlview]      | url extractor/launcher (see urlscan for mails)
[awk]          | pattern scanning and processing language
[gawk]         | pattern scanning and processing language
[mawk]         | pattern scanning and processing language
[sed]          | stream editor for filtering and transforming text
[psed]         | a stream editor
[a2p]          | awk to perl translator
[s2p]          | sed to perl translator
[cut]          | extract columns from files
[join]         | join lines of two files on a common field
[combine]      | combine lines from two files using boolean operations
[column]       | columnate lists
[colrm]        | remove columns from a file
[rs]           | reshape a data array
[csplit]       | split a file into context-determined pieces
[paste]        | append/merge columns
[tr]           | translate, squeeze or delete characters
[sort]         | sort lines of text files
[msort]        | sort records in complex ways
[tsort]        | perform topological sort
[shuf]         | write a random permutation of the input lines to stdout
[unsort]       | reorder lines in a file in semirandom ways
[tac]          | concatenate and print files in reverse
[rev]          | reverse characters of lines in file or files
[uniq]         | report or omit repeated lines
[tee]          | copy stdin to a file and to stdout simultaneously
[multitee]     | send multiple inputs to multiple outputs
[pr]           | convert text files for printing
[fmt]          | optimally reformat text
[par]          | filter for reformatting paragraphs
[fold]         | wrap each input line to fit in specified width
[expand]       | convert tabs to spaces
[unexpand]     | convert spaces to tabs
[uchardet]     | universalchardet (Universal Charset Detector)
[recode]       | converts files between character sets
[iconv]        | convert encoding of given files
[unaccent]     | remove accents from input stream or a string
[sq]           | squeeze a sorted word list
[unsq]         | unsqueeze a sorted word list
[csvtool]      | tool for performing manipulations on csv files
[xmlstarlet]   | command line xml/xslt toolkit


# Print #######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[lp]           | send files to a printer
[lpr]          | print files
[lpq]          | show printer queue status
[lpstat]       | print cups status information
[lprm]         | remove print jobs
[lpmove]       | move a job or all jobs to a new destination
[cancel]       | cancel cups print jobs
[lpc]          | line printer control program
[ink]          | tool for checking the ink level of your printers
[lpadmin]      | configure cups printers and classes
[lpoptions]    | display or set cups printer options and defaults
[cupsaccept]   | accept jobs sent to a destination
[cupsreject]   | reject jobs sent to a destination
[cupsdisable]  | stop printers and classes
[cupsenable]   | start printers and classes
[paperconfig]  | configure the system default paper size


# Compression #################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[dtrx]         | cleanly extract many archive types
[atool]        | a script for managing file archives of various types
[patool]       | portable archive file manager
[gitunpack]    | gnu interactive tools - unified archive unpacking
[ar]           | create, modify, and extract from archives
[tar]          | the gnu version of the tar archiving utility
[cpio]         | copy files to and from archives
[7z]           | a file archiver with highest compression ratio
[gzip]         | compress files (gnu zip)
[pigz]         | parallel compress files (gnu zip)
[bzip2]        | a block-sorting file compressor
[lz]           | provides a listing of a  tar.gz archive
[gunzip]       | expand files (gnu zip)
[unpigz]       | parallel decompress files (gnu zip)
[bunzip2]      | a block-sorting file decompressor
[gzexe]        | compress executable files in place
[bzexe]        | compress executable files in place
[compress]     | compress and expand data
[pbzip2]       | parallel bzip2 file compressor
[lzip]         | reduces the size of files
[pax]          | portable archive interchange
[rar]          | archive files with compression
[unrar]        | extract files from rar archives
[compress]     | compress data
[uncompress]   | expand files
[shar]         | create shell archives
[unshar]       | unpack a shar file
[unace]        | extract, test and view ace archives
[uuencode]     | encode a binary file
[uudecode]     | decode a file created by uuencode
[base64]       | encode/decode data and print to standard output
[xz]           | compress or decompress xz and lzma files
[lzma]         | lzma compression and decompression tool
[lzma2]        | lzma compression and decompression tool
[zoo]          | manipulate archives of files in compressed form
[pxz]          | parallel lzma compressor compatible with xz
[zip]          | compress files (windows zip)
[cabextract]   | extract files from microsoft cabinet (cab)
[zrun]         | automatically uncompress arguments to command


# Encryption ##################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[gpg]          | openpgp encryption and signing tool
[gpgv]         | verify openpgp signatures
[crypt]        | encrypt or decrypt files (wrapper for mcrypt)
[mcrypt]       | encrypt files, several algorythms
[bcrypt]       | blowfish file encryption
[ccrypt]       | encrypt and decrypt using rijndael block cipher (aes)
[scrypt]       | encrypt or decrypt files
[aespipe]      | aes encrypting or decrypting pipe
[openssl]      | openssl command line tool
[enc]          | symmetric cipher routines
[stunnel]      | universal ssl tunnel
[cryptcat]     | twofish encryption enabled version of nc
[rsyncrypto]   | rsync friendly encryption
[encfs]        | mounts or creates an encrypted virtual filesystem
[encfsctl]     | administrative tool for working with encfs filesystems
[stegdetect]   | finds image files with steganographic content
[stegbreak]    | launches brute-force dictionary attacks on jpg image
[steghide]     | a steganography program


# Backup ######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[mt]           | control magnetic tape drive operation
[dump]         | ext2/3/4 filesystem backup
[restore]      | restore files or filesystem from backups made with dump
[tar]          | read write tape archives
[par2]         | par 2.0 compatible file verification and repair tool
[unison]       | user level file-synchronization tool
[rsync]        | a fast, versatile, remote (and local) file-copying tool
[rsyncrypto]   | rsync friendly encryption
[duplicity]    | encrypted incremental backup to local or remote storage
[backup-manager]| an easy to use backup tool for your linux box
[rdist]        | remote file distribution client program
[rdup]         | generate a file list suitable for making backups
[tarsnap]      | manipulate remote encrypted backups
[vbackup]      | a modular backup program
[venti]        | client for sha1-addressed block storage server
[bbackupctl]   | control the box backup client daemon


# CD/DVD/BluRay ###############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[mkisofs]      | create an hybrid iso9660 joliet hfs filesystem
[genisoimage]  | create iso9660/joliet/hfs filesystem
[growisofs]    | combined frontend to cd/dvd/bluray recording program
[cdw]          | frontend to cdrecord/mkisofs/growisofs and other tools
[cdrdao]       | reads and writes cds in disc-at-once mode
[cdrecord]     | burn a cd
[xorriso]      | creates and manipulates iso filesystem with rockridge
[bchunk]       | cd image format conversion from bin/cue to iso/cdr
[burn]         | record from various sources to optical media (cd, dvd)
[mp3burn]      | burn audio cds from mp3, ogg vorbis, or flac files
[bashburn]     | a bash script cd burner writer
[mybashburn]   | burn data cds/dvds and create mp3/ogg/flac
[dvdauthor]    | assembles multiple mpeg into a suitable dvd filesystem
[cdparanoia]   | cdda reading tool with extra data verification features
[abcde]        | a better cd encoder, grabs cd to ogg/speex/mp3/flac/etc
[crip]         | a terminal-based ripper/encoder/tagger tool
[jack]         |  rip and encode cds with one command
[cdda2ogg]     | extract audio cd audio tracks and encode them in ogg
[cdda2mp3]     | extract audio cd audio tracks and encode them in mp3
[ripit]        | make flac/ogg/mp3/m4a/aac/als/mp4/mpc/wv/etc from cd
[ocp]          | open cubic music player
[cdcd]         | command driven cd player
[cplay]        | a front-end for various audio players
[mcdp]         | a small cdplayer for linux
[workbone]     | interactive text-mode program for playing audio cd
[cdctrl]       | command line cdrom control
[cdeject]      | ejects the current compact disc
[cdclose]      | closes the cdrom tray
[cdir]         | lists infos about the currently loaded audio cd
[cdinfo]       | print out the audiostatus (playing, etc)
[cdpause]      | pauses/resumes the currently playing compact disc
[cdplay]       | plays the compact disc
[cdstop]       | stops the compact disc
[cdvolume]     | sets the output volume level of the cd player (0-255)
[cdshuffle]    | plays the audio tracks on the disc in random order
[cdadd]        | add information for a new cd to .cdtooldb
[cdown]        | query cddb database for info on a disc

# Numbers and Math ############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[qalc]         | powerful and easy to use command line calculator
[bc]           | an arbitrary precision calculator language
[dc]           | an arbitrary precision calculator
[calc]         | arbitrary precision calculator
[mathomatic]   | a computer algebra system
[wcalc]        | a natural-expression command-line calculator
[numfmt]       | convert numbers from/to human-readable strings
[rax2]         | convert between (signed) int, float, oct, bin and hex
[units]        | convert units from one scale to another
[numgrep]      | the numeric equivilent of the grep utility
[numprocess]   | this program mutates numbers as it encounters them
[numsum]       | take the first numbers on stdin and return the sum
[numaverage]   | find the average of a set of numbers
[numbound]     | find boundary numbers in files or stdin
[numnormalize] | normalize a set of numbers, by default between 0 and 1
[numinterval]  | show the numeric intervals between each line in a file
[numround]     | rounds off numbers it encounters.
[seq]          | print a sequence of numbers
[numrange]     | print out a range of numbers for use in for loops
[jot]          | print sequential or random data
[ent]          | pseudorandom number sequence test
[numrandom]    | print out a random number
[factor]       | factor numbers
[primes]       | display all primes (primes.pl)
[primes.6]     | generate primes
[sc]           | spreadsheet calculator
[gnuplot]      | an interactive plotting program
[maxima]       | common lisp version of macsyma symbolic mathematics
[octave]       | matlab like language for numerical computations
[R]            | a language for data analysis and graphics


# Date and Time ###############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[date]         | print or set the system date and time
[cal]          | displays a calendar and the date of easter
[ncal]         | cal with an alternative layout
[gcal]         | a program for calculating and printing calendars
[gcalcli]      | google calendar command line interface
[ddate]        | convert gregorian dates to discordian dates
[pcal]         | generate postscript or html calendars
[saydate]      | audio date/uptime check
[saytime]      | audio time check


# Schedule ####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[sleep]        | wait for some time
[watch]        | execute a program periodically, showing output
[chronic]      | runs a command quietly unless it fails
[wait]         | await process completion
[flock]        | manage locks from shell scripts
[lckdo]        | run a program with a lock held
[shush]        | run a command and optionally report its output by mail
[inotifywait]  | wait for changes to files using inotify
[entr]         | run arbitrary commands when files change
[fsniper]      | watch directories and apply rules to created files
[timeout]      | run a command with a time limit
[crontab]      | maintain crontab files for individual users
[at]           | executes commands at a specified time
[atq]          | lists the user pending jobs
[atrm]         | remove jobs fom the later execution queue
[batch]        | executes commands when system load levels permit


# Office ######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[wordgrinder]  | console-based word processor
[antiword]     | show the text and images of ms word documents
[abook]        | text-based address book program
[hnb]          | hierarchical notebook
[worklog]      | keeping track of time spent on different projects
[tpp]          | text presentation program
[xsw]          | slide show presentation tool
[ledger]       | command-line accounting
[sc]           | spreadsheet calculator
[slsc]         | s-langauge port of the sc spreadsheet
[teapot]       | table editor and planner
[oleo]         | the gnu spreadsheet program
[ssconvert]    | a command line spreadsheet format converter
[ssindex]      | generate index data for spreadsheet files
[ssgrep]       | search spreadsheets for strings
[ssdiff]       | compare two spreadsheets
[dbview]       | view dbase 3 files
[gv]           | postscript and pdf viewer
[xdvi]         | dvi previewer for the x window system

For note-taking, you might also want to have a look at:
- [org-mode](http://orgmode.org)
- [vimoutliner](https://github.com/vimoutliner/vimoutliner)


# Spelling ####################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[spell]        | check spelling in batch
[aspell]       | check spelling interactively
[ispell]       | check spelling in batch or interactively
[goldendict]   | a feature-rich dictionary lookup program
[dict]         | dict protocol client
[sdcv]         | console version of stardict program
[aiksaurus]    | english-language thesaurus
[wtf]          | translates acronyms for you
[an]           | anagram generator
[wordplay]     | anagram finder


# Publishing ##################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[gs]           | ghostscript, a postscript and pdf interpreter/previewer
[fbgs]         | postscript/pdf viewer for the framebuffer console
[latex]        | structured text formatting and typesetting
[tex]          | text formatting and typesetting
[etex]         | extended tex
[latexdiff]    | determine and markup differences between two latex files
[latexmk]      | generate latex document
[dblatex]      | convert docbook to latex, dvi, postscript, and pdf
[psselect]     | select pages from a postscript file
[mf]           | metafont, a language for font and logo design
[pdftex]       | pdf output from tex
[mutool]       | all purpose tool for dealing with pdf files
[pdfjam]       | a shell script for manipulating pdf files
[pdftk]        | a handy tool for manipulating pdf
[pdfunite]     | pdf page merger
[pdffonts]     | pdf font analyzer
[pdfimages]    | pdf image extractor
[pdfinfo]      | pdf document information extractor
[pdfseparate]  | pdf page extractor
[pdftocairo]   | pdf to png/jpeg/pdf/ps/eps/svg using cairo
[pdftohtml]    | program to convert pdf files into html, xml and png
[pdftoppm]     | pdf to portable pixmap (ppm) converter
[pdftops]      | pdf to postscript converter
[pdftotext]    | pdf to text converter
[diffpdf]      | compare two pdf files textually or visually


# Task Managers ###############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[task]         | taskwarrior, a command line todo manager
[tudu]         | command line hierarchical todo list
[remind]       | a sophisticated reminder service
[wyrd]         | front-end to remind
[gcalcli]      | google calendar command line interface
[calcurse]     | text-based organizer
[pal]          | calendar with events
[when]         | a minimalistic personal calendar program
[devtodo]      | a reminder/task program aimed at developers
[tdl]          | to do list manager
[todo.sh]      | minimal, todo.txt focused task manager
[w2do]         | a simple text-based todo manager
[yokadi]       | commandline todo system
[episoder]     | tv show reminder from epguides.com and thetvdb.com


# Conversion ##################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[dos2unix]     | dos/mac to unix text file format converter
[isutf8]       | check whether files are valid utf-8
[iconv]        | convert encoding of given files
[recode]       | converts files between character sets
[utf8tolatin1] | reads utf-8 encoded text and writes latin1
[groff]        | front-end for the groff document formatting system
[troff]        | the troff processor of the groff text formatting system
[nroff]        | emulate nroff command with groff
[deroff]       | remove roff and preprocessor constructs
[eqn]          | format equations for troff or mathml
[neqn]         | format equations for ascii output
[tbl]          | format tables for troff
[col]          | filter reverse line feeds from input
[catdvi]       | dvi to plain text converter
[gv]           | postscript and pdf viewer
[odt2txt]      | a simple converter from opendocument text to plain text
[o3read]       | dump of an openoffice.org document parse tree
[o3tohtml]     | convert files in openoffice.org format to html
[o3totxt]      | convert files in openoffice.org format to text
[catdoc]       | outputs word doc file content as plain text
[docx2txt]     | convert microsoft ooxml files to plain text
[abiword]      | flexible word processor documents converter
[antiword]     | show the text and images of ms word documents
[xls2csv]      | output ms-excel file as comma-separated values
[xlsx2csv]     | convert xslx xml files to csv format
[xlhtml]       | convert excel xls files to html
[ssconvert]    | spreadsheet format converter (gnumeric)
[ppthtml]      | convert powerpoint ppt files to html
[stx2any]      | converter from structured text to multiple formats
[pandoc]       | general markup converter
[unhtml]       | strip the html formatting
[html2text]    | an advanced html-to-text converter
[html2markdown]| converts html to markdown-formatted text
[asciidoc]     | converts an asciidoc text file to html or docbook
[markdown]     | convert markdown syntax to (x)html
[ttm]          | tex/latex to mathml converter
[txt2tags]     | text formatting and conversion tool
[txt2man]      | convert flat ascii text to man page format
[txt2html]     | convert plain text file to html
[textfmt]      | convert ascii text to postscript for facsimile
[txt2pdbdoc]   | text to doc file converter for palm pilots
[img2txt]      | convert images to various text-based coloured files
[cacaview]     | ascii image browser
[asciiview]    | a high quality ascii art image viewer
[gnuhtml2latex]| html to latex converter
[csv2latex]    | convert a csv file into a latex document
[sgml2latex]   | create latex, dvi, ps or pdf output from an sgml file
[chm2pdf]      | a tool convert chm to pdf format
[unoconv]      | convert documents from/to libreoffice format
[jodconverter] | import/export documents using the libreoffice filters
[ps2ascii]     | ghostscript translator from postscript or pdf to ascii
[ps2pdf]       | convert postscript to pdf using ghostscript
[vilistextum]  | html to ascii converter
[wvWare]       | convert msword documents
[rst2pdf]      | convert restructuredtext documents to pdf


# ASCII Art ###################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[figlet]       | display text with an ascii art charset
[toilet]       | display large colourful characters
[cowsay]       | configurable speaking/thinking cow (and a bit more)
[cadubi]       | creative ascii drawing utility
[lolcat]       | rainbow coloring for text
[cacaview]     | ascii image browser
[asciiview]    | a high quality ascii art image viewer
[linux_logo]   | color ansi penguin logo with system information
[screenfetch]  | the bash screenshot information tool


# Images ######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[fbi]          |  framebuffer imageviewer
[fim]          | fbi (linux framebuffer imageviewer) improved
[findimagedupes]| finds visually similar or duplicate images
[identify]     | describes the format and characteristics of images
[fbgrab]       | takes a screenshot using the framebuffer device
[gifsicle]     | manipulates gif images and animations
[pngcrush]     | optimizes, or modifies, png files
[optipng]      | advanced optimization program for
[gm]           | graphicsmagick is a set of tools to manipulate images
[convert]      | convert/resize/blur/crop/despeckle/dither/etc image
[mogrify]      | inplace convert/edit/resize/blur/crop/etc an image
[icotool]      | convert and create win32 icon and cursor files
[rdjpgcom]     | display text comments from a jpeg file
[wrjpgcom]     | insert text comments into a jpeg file
[cjpeg]        | compress an image file to a jpeg file
[djpeg]        | decompress a jpeg file to an image file
[jpegtran]     | lossless transformation of jpeg files
[jp2a]         | convert jpeg images to ascii
[exif]         | shows exif information in jpeg files
[exiftool]     | read and write meta information in media files
[exiftran]     | transform/rotate digital camera jpeg images
[exifcom]      | set/display user comment tag contained in a jpeg exif
[exiftags]     | output the properties contained in a jpeg exif section
[exiftime]     | display/adjust the date and time exif tags
[exifprobe]    | probe and report exif structure and metadata content
[exifgrep]     | select and reformat the output of exifprobe
[jhead]        | digicam jpeg exif header manipulation tool
[gle]          | graphics layout engine
[simple-scan]  | scanning utility
[scanimage]    | scan an image
[gocr]         | command line text recognition tool
[tesseract]    | command-line ocr engine
[album]        | themable html photo album generator
[gphotofs]     | filesystem to mount digital cameras
[qrencode]     | encode  data  in a qr code as a png or eps image


# Vector Graphics #############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[dot]          | filter for drawing directed graphs
[neato]        | filter for drawing undirected graphs
[twopi]        | filter for radial layouts of graphs
[circo]        | filter for circular layout of graphs
[fdp]          | filter for drawing undirected graphs
[sfdp]         | filter for drawing large undirected graphs
[patchwork]    | filter for tree maps
[asy]          | asymptote: a script-based vector graphics language
[inkscape]     | svg (scalable vector graphics) editing program
[rasterizer]   | svg conversion to png, jpeg and pdf
[potrace]      | transform bitmaps into vector graphics


# 3D ##########################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[aqsis]        | aqsis renderer adhering to the renderman standard
[povray]       | the persistence of vision ray tracer


# Videos ######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[mplayer]      | video/audio player/streamer
[mencoder]     | video decoding, encoding and filtering tool
[vlc]          | video lan client, a media player/streamer/transcoder
[xine]         | a free video player
[xine-remote]  | a small tool to connect xine remote control server
[avplay]       | avplay media player
[avconv]       | avconv video converter
[avprobe]      | avprobe media prober
[avidemux]     | a free video editor
[mpgtx]        | manipulate mpeg files
[mplex]        | mpeg 1/2 program/system stream multiplexer
[ffmpeg]       | ffmpeg video converter
[mediainfo]    | display information about audio/video files
[imdb]         | calls any of the imdb functions
[imdb-get]     | looks up imdb data for a film
[imdb-link]    | links films based on their genre
[imdb-rename]  | renames files based on their title
[imdb-fxd]     | creates fxd files from the imdb cache for freevo
[imdb-update-cache] | updates the imdb cache for a given directory


# Audio and Music #############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[mplayer]      | video/audio player/streamer
[vlc]          | video lan client, a media player/streamer/transcoder
[sox]          | the swiss army knife of audio manipulation
[oggenc]       | encode audio into the ogg vorbis format
[flac]         | encoding, decoding, testing and analyzing flac streams
[lame]         | create mp3 audio files
[mediainfo]    | display information about audio/video files
[exfalso]      | tag editor for mp3/ogg/flac/musepack/wavpack/mod/xm/it
[id3]          | id3 tag editor
[id3v2]        | add/change/remove/view id3v2 tags, converts/lists id3v1
[id3tool]      | a command line editor for id3 tags
[id3ed]        | edit id3 description tags in mpeg3 files
[mussort]      | sort music files into folders


# Audio Players ###############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[mplayer]      | video/audio player/streamer
[vlc]          | video lan client, a media player/streamer/transcoder
[ocp]          | open cubic music player
[mpc]          | program for controlling music player daemon (mpd)
[ncmpc]        | curses music player daemon (mpd) client
[audtty]       | control audacious from cli with a ncurses interface
[xmms2]        | command-line interface to the xmms2 daemon
[cmus]         | curse music player
[moosic]       | a command-line client for the moosic jukebox system
[play]         | sox invoked as play outputs to the default sound device
[bplay]        | buffered sound playing
[ogg123]       | plays ogg vorbis files
[mpg123]       | play audio mpeg 1.0/2.0/2.5 stream (layers 1, 2 and 3)
[mpg321]       | simple and lightweight command line mp3 player
[splay]        | mpeg-1,2 audio layer 1,2,3 file player
[madplay]      | decode and play mpeg audio stream(s)
[audiopreview] | play audio, video, and internet media streams
[herrie]       | interactive music playlist player
[mp3blaster]   | an interactive text-console based mp3 player
[mocp]         | console audio player
[mpc123]       | your handy musepack audio player
[orpheus]      | text mode menu and window-driven audio player
[pytone]       | music jukebox for your audio files
[yauap]        | audio player based on the gstreamer framework
[mikmod]       | play soundtracker modules on a unix machine
[xmp]          | extended module player
[cdcd]         | command driven cd player
[cplay]        | a front-end for various audio players
[mcdp]         | a small cdplayer for linux
[workbone]     | interactive text-mode program for playing audio cd
[shell-fm]     | console-based player for last.fm radio streams


# Audio Editing ###############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[sox]          | the swiss army knife of audio manipulation
[ecasound]     | sample editor, multitrack recorder, fx-processor, etc
[rec]          | sox invoked as rec set default sound device as input
[brec]         | buffered sound recording
[snd]          | a sound editor
[gramofile]    | sample and process analog recordings
[quelcom]      | command line editing tools for mp3 and wav files
[qmp3check]    | check and clean mp3 streams
[qmp3cut]      | extract, delete parts of a mp3 file
[cutmp3]       | a fast and leightweight mp3 editor
[fadecut]      | rip audiostreams, cut, fade in/out and tag audiofiles
[qmp3info]     | show info from mp3 files
[arename]      | automatically rename audio files by tagging information
[qmp3join]     | join mp3 files
[qmp3report]   | report mp3 files and directories
[qwavinfo]     | show info from wav files
[qwavjoin]     | join wav files
[qwavcut]      | extract, delete parts of a wav file
[qwavsilence]  | detect and shrink silence sequences in wav files
[qwavfade]     | fade in/out wav files
[qwavheaderdump]  | dump and fix wav headers
[normalize-audio] | adjusts volume levels of audio files


# Midi ########################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[timidity]     | midi-to-wave converter and player
[pmidi]        | midi file player for alsa
[playmidi]     | full-featured midi player using the voxware driver
[arecordmidi]  | record standard midi files
[abc2midi]     | converts abc file to midi
[midi2abc]     | program to convert midi format files to abc notation
[abcm2ps]      | translate abc music notation to postscript or svg


# Text to Speech ##############################################################

Command        | Description
--------------- | -----------------------------------------------------------
[espeak]       | a multi-lingual software speech synthesizer
[festival]     | a text-to-speech system
[saydate]      | audio date/uptime check
[saytime]      | audio time check


# Games #######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[adventure]    | an exploration game
[nethack]      | exploring the mazes of menace
[slashem]      | exploring the mazes of menace
[rogue]        | exploring the dungeons of doom
[crawl]        | the roguelike game of crawl
[battlestar]   | a tropical adventure game
[phantasia]    | an interterminal fantasy game
[wump]         | hunt the wumpus in an underground cave
[bastet]       | tetris(r) clone with "bastard" block-choosing ai
[pytris]       | two players console tetris game
[tetris-bsd]   | the game of tetris
[greed]        | eat a game field until you run out of moves
[moon-buggy]   | drive some car across the moon
[ninvaders]    | ncurses version of space invaders
[overkill]     | bloody 2d action deathmatch-like game in ascii-art
[worm]         | play the growing worm game
[snake]        | display chase game
[atc]          | air traffic controller game
[robots]       | fight off villainous robots
[hunt]         | a multi-player multi-terminal game
[wargames]     | shall we play a game?
[canfield]     | the solitaire card game canfield
[cribbage]     | the card game cribbage
[mille]        | play mille bornes
[monop]        | monopoly game
[backgammon]   | the game of backgammon
[sail]         | multi-user wooden ships and iron men
[trek]         | trekkie game
[boggle]       | word search game
[hangman]      | computer version of the game hangman
[gtypist]      | typing tutor for different keyboards and languages
[arithmetic]   | quiz on simple arithmetic
[quiz]         | random knowledge tests
[fortune]      | print a random, hopefully interesting, adage
[display-dhammapada] | display a verse from the dhammapada


# Screensavers ################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[cmatrix]      | simulates the display from the matrix movie
[rain]         | animated raindrops display
[tty-clock]    | a terminal digital clock
[binclock]     | prints time in binary format


# Other #######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[echo]         | display a line of text
[printf]       | format and print data
[getopt]       | parse command options
[expect]       | automate applications accessed over a terminal
[expr]         | evaluate expressions
[yes]          | output a string repeatedly until killed
[true]         | do nothing, successfully
[false]        | do nothing, unsuccessfully
[ifetch]       | image collection tool for ip cameras of ifetch-tools
[rig]          | random identity generator
[pwgen]        | generate pronounceable passwords
[makepasswd]   | generate and/or encrypt passwords
[pwsafe]       | password database utility
[gringotts]    | secure password and data storage manager
[clamscan]     | scan files and directories for viruses
[llines]       | lifelines genealogy program, gedcom format


# X Windows ###################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[xinput]       | utility to configure and test x input devices
[xvidtune]     | adjust x server origin and size
[xcalib]       | tiny monitor calibration loader for x
[xev]          | x event viewer
[setxkbmap]    | set the keyboard using the x keyboard extension
[xmodmap]      | set/modify keymaps and pointer button mappings in x
[xhost]        | server access control program for x
[xsetroot]     | root window parameter setting utility for x
[import]       | window/screenshot
[xset]         | user preference utility for x
[xrdb]         | x server resource database utility
[appres]       | list x application resource database
[listres]      | list resources in widgets
[editres]      | a dynamic resource editor for x toolkit applications
[xlsfonts]     | server font list displayer for x
[xfontsel]     | point and click selection of x11 font names
[xfd]          | display all the characters in an x font
[fc-scan]      | scan font files or directories
[fc-cache]     | build font information cache files
[fc-cat]       | read font information cache files
[fc-list]      | list available fonts
[fc-query]     | query font files
[fc-match]     | match available fonts
[fc-pattern]   | parse and show pattern
[mimeopen]     | open files by mimetype
[xdg-open]     | opens a file or url in the user preferred application
[exo-open]     | open urls and launch preferred applications (xfce)
[gnome-open]   | open files and urls using the gnome file handlers
[dmenu]        | dynamic menu, manages huge numbers defined menu items
[notify-send]  | a program to send desktop notifications
[xmessage]     | display a message/query in a window (x-based /bin/echo)
[dialog]       | display curses dialog boxes from shell scripts
[kdialog]      | show kde dialog boxes from shell scripts
[zenity]       | display gtk+ dialogs
[osd_cat]      | x on-screen file displayer
[xclip]        | command line interface to x selections (clipboard)
[xclipboard]   | x clipboard client
[devilspie]    | perform actions on windows as they are created
[xdotool]      | command-line x11 automation tool
[xnee]         | records, replays x11 data on multiple displays
[xbindkeys]    | grab key and mouse events in x and starts shell commands
[xte]          | generates fake input using the xtest extension
[x2x]          | use keyboard and mouse from an x display on antoher x
[wmctrl]       | interact with a ewmh/netwm compatible x window manager
[xtrlock]      | lock X display until password supplied
[dbus-send]    | send a message to a desktop bus
[dbus-monitor] | debug probe to print desktop bus messages
[qdbus]        | a communication-interface for qt-based applications
[xrandr]       | primitive command line interface to randr extension
[xprop]        | property displayer for x
[xdpyinfo]     | display information utility for x
[xwininfo]     | window information utility for x
[xdriinfo]     | query configuration information of dri drivers
[xvinfo]       | print out x-video extension adaptor information
[glxinfo]      | show information about the glx implementation
[Xvfb]         | virtual framebuffer x server without the hardware
[trash]        | trash utility compliant with freedesktop.org
[trash-list]   | list trashed files
[trash-restore]| restore for command line trash utility
[trash-empty]  | empty for command line trash utility
[xmag]         | magnify parts of the screen


# Funny #######################################################################

Command        | Description
--------------- | -----------------------------------------------------------
[axe]          | tools to improve network performance via snip
[baby]         | create new process from two parents
[bosskill]     | send a signal to your boss, or terminate your boss
[c]            | genericised softdrink generator (coffee, coke etc)
[celibacy]     | don't have sex
[chainsaw]     | tools to improve network performance via snip
[chastise]     | library function to punish users
[condom]       | protects against viruses and child processes
[ctluser]      | control lusers
[cutter]       | tools to improve network performance via snip
[egrope]       | massage a file for a while
[fgrope]       | massage a file for a while
[flame]        | reply to usenet news posting automatically
[flog]         | speed up a process
[gong]         | evaluate process performance
[grope]        | massage a file for a while
[guru]         | system administration
[knife]        | tools to improve network performance via snip
[lart]         | luser attitude readjustment tool
[luser]        | process to control the clueless individuals
[normality]    | defines types of normality different users may have
[nuke]         | launch nuclear weapons at mapped usenet sites
[party]        | set os responses mode
[people]       | fetch a list of all ttys behaving like a human
[pmsd]         | periodically manic system daemon
[rescrog]      | change something, make it different
[rtfm]         | a response for easy questions from clueless lusers
[sex]          | have sex
[slave]        | a semi-interactive command for the dirty work
[strfry]       | string operation
[sysadmin]     | responsible  for everything imaginable
[think]        | you dont have to think, computers can think for you
[tm]           | meditate
[uubp]         | unix-to-unix beer protocol
[whack]        | mangle requests to a printer or damage a printer
[xkill]        | kill processes or users, including usenet poster
[xlart]        | interactive x interface to rlart

-------------------------------------------------------------------------------








[Content]: #user-content-content
[Other Documentation]: #user-content-other-documentation
[Getting Help]: #user-content-getting-help
[Interesting Pages]: #user-content-interesting-pages
[Shells]: #user-content-shells
[Terminal Tools]: #user-content-terminal-tools
[Setup]: #user-content-setup
[System]: #user-content-system
[Kernel]: #user-content-kernel
[Init and Runlevels]: #user-content-init-and-runlevels
[Hardware]: #user-content-hardware
[Filesystem Tools]: #user-content-filesystem-tools
[Quotas]: #user-content-quotas
[Processes]: #user-content-processes
[Performances]: #user-content-performances
[User Management]: #user-content-user-management
[User Information]: #user-content-user-information
[Environment]: #user-content-environment
[Security Context]: #user-content-security-context
[Development]: #user-content-development
[Debugging]: #user-content-debugging
[Revision Control]: #user-content-revision-control
[Database]: #user-content-database
[Network]: #user-content-network
[Wireless]: #user-content-wireless
[Network Monitor]: #user-content-network-monitor
[Network Tunnels]: #user-content-network-tunnels
[Network Scan]: #user-content-network-scan
[Network Capture]: #user-content-network-capture
[Network Filesystems]: #user-content-network-filesystems
[Network Apps]: #user-content-network-apps
[Modem/Fax/GSM]: #user-content-modemfaxgsm
[Network File Transfer]: #user-content-network-file-transfer
[Browser]: #user-content-browser
[RSS Reader]: #user-content-rss-reader
[Podcast]: #user-content-podcast
[Chat]: #user-content-chat
[EMail]: #user-content-email
[Newsgroups]: #user-content-newsgroups
[Websites]: #user-content-websites
[Directories]: #user-content-directories
[Files]: #user-content-files
[Pipes]: #user-content-pipes
[File Attributes]: #user-content-file-attributes
[File Find]: #user-content-file-find
[File Compare]: #user-content-file-compare
[Binary Information]: #user-content-binary-information
[File Managers]: #user-content-file-managers
[Viewers]: #user-content-viewers
[Editors]: #user-content-editors
[Text Utilities]: #user-content-text-utilities
[Print]: #user-content-print
[Compression]: #user-content-compression
[Encryption]: #user-content-encryption
[Backup]: #user-content-backup
[CD/DVD/BluRay]: #user-content-cddvdbluray
[Numbers and Math]: #user-content-numbers-and-math
[Date and Time]: #user-content-date-and-time
[Schedule]: #user-content-schedule
[Office]: #user-content-office
[Spelling]: #user-content-spelling
[Publishing]: #user-content-publishing
[Task Managers]: #user-content-task-managers
[Conversion]: #user-content-conversion
[ASCII Art]: #user-content-ascii-art
[Images]: #user-content-images
[Vector Graphics]: #user-content-vector-graphics
[3D]: #user-content-3d
[Videos]: #user-content-videos
[Audio and Music]: #user-content-audio-and-music
[Audio Players]: #user-content-audio-players
[Audio Editing]: #user-content-audio-editing
[Midi]: #user-content-midi
[Text to Speech]: #user-content-text-to-speech
[Games]: #user-content-games
[Screensavers]: #user-content-screensavers
[Other]: #user-content-other
[X Windows]: #user-content-x-windows
[Funny]: #user-content-funny

[/lib/ld-linux.so.2]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ld.so.8.html
[/lib64/ld-linux-x86-64.so.2]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ld.so.8.html
[7z]: http://manpages.ubuntu.com/manpages/xenial/en/man1/7z.1.html
[a2p]: http://manpages.ubuntu.com/manpages/wily/en/man1/a2p.1.html
[abc2midi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/abc2midi.1.html
[abcde]: http://manpages.ubuntu.com/manpages/xenial/en/man1/abcde.1.html
[abcm2ps]: http://manpages.ubuntu.com/manpages/xenial/en/man1/abcm2ps.1.html
[abiword]: http://manpages.ubuntu.com/manpages/xenial/en/man1/abiword.1.html
[abook]: http://manpages.ubuntu.com/manpages/xenial/en/man1/abook.1.html
[ac]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ac.1.html
[ack]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ack-grep.1p.html
[acl]: http://manpages.ubuntu.com/manpages/xenial/en/man5/acl.5.html
[acpitool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/acpitool.1.html
[adduser]: http://manpages.ubuntu.com/manpages/xenial/en/man8/adduser.8.html
[adventure]: http://manpages.ubuntu.com/manpages/xenial/en/man6/adventure.6.html
[aee]: http://man.cx/aee
[aespipe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/aespipe.1.html
[ag]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ag.1.html
[agedu]: http://manpages.ubuntu.com/manpages/xenial/en/man1/agedu.1.html
[agrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/agrep.1.html
[aiksaurus]: http://manpages.ubuntu.com/manpages/xenial/en/man1/aiksaurus.1.html
[album]: http://manpages.ubuntu.com/manpages/xenial/en/man1/album.1.html
[alien]: http://manpages.ubuntu.com/manpages/xenial/en/man1/alien.1p.html
[alpine]: http://manpages.ubuntu.com/manpages/xenial/en/man1/alpine.1.html
[alsactl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/alsactl.1.html
[alsamixer]: http://manpages.ubuntu.com/manpages/xenial/en/man1/alsamixer.1.html
[amulecmd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/amulecmd.1.html
[an]: http://manpages.ubuntu.com/manpages/xenial/en/man6/an.6.html
[antiword]: http://manpages.ubuntu.com/manpages/xenial/en/man1/antiword.1.html
[apm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/apm.1.html
[appres]: http://manpages.ubuntu.com/manpages/xenial/en/man1/appres.1.html
[apropos]: http://manpages.ubuntu.com/manpages/xenial/en/man1/apropos.1.html
[apt-cache]: http://manpages.ubuntu.com/manpages/xenial/en/man8/apt-cache.8.html
[apt-config]: http://manpages.ubuntu.com/manpages/xenial/en/man8/apt-config.8.html
[apt-file]: http://manpages.ubuntu.com/manpages/xenial/en/man1/apt-file.1.html
[apt-get]: http://manpages.ubuntu.com/manpages/xenial/en/man8/apt-get.8.html
[apt-mark]: http://manpages.ubuntu.com/manpages/xenial/en/man8/apt-mark.8.html
[aptitude]: http://manpages.ubuntu.com/manpages/xenial/en/man8/aptitude-curses.8.html
[aqsis]: http://manpages.ubuntu.com/manpages/xenial/en/man1/aqsis.1.html
[ar]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ar.1.html
[arch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/arch.1.html
[arecordmidi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/arecordmidi.1.html
[arename]: http://manpages.ubuntu.com/manpages/xenial/en/man1/arename.1.html
[aria]: http://man.cx/aria
[aria2c]: http://manpages.ubuntu.com/manpages/xenial/en/man1/aria2c.1.html
[arithmetic]: http://manpages.ubuntu.com/manpages/xenial/en/man6/arithmetic.6.html
[arp]: http://manpages.ubuntu.com/manpages/xenial/en/man8/arp.8.html
[arp-scan]: http://manpages.ubuntu.com/manpages/xenial/en/man1/arp-scan.1.html
[arping]: http://manpages.ubuntu.com/manpages/xenial/en/man8/arping.8.html
[arpspoof]: http://manpages.ubuntu.com/manpages/xenial/en/man8/arpspoof.8.html
[arpwatch]: http://manpages.ubuntu.com/manpages/xenial/en/man8/arpwatch.8.html
[as]: http://manpages.ubuntu.com/manpages/xenial/en/man1/as.1.html
[ascii]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ascii.1.html
[ascii.7]: http://manpages.ubuntu.com/manpages/xenial/en/man7/ascii.7.html
[asciidoc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/asciidoc.1.html
[asciiview]: http://manpages.ubuntu.com/manpages/xenial/en/man1/asciiview.1.html
[ash]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ash.1.html
[aspell]: http://manpages.ubuntu.com/manpages/xenial/en/man1/aspell.1.html
[astyle]: http://manpages.ubuntu.com/manpages/xenial/en/man1/astyle.1.html
[asy]: http://manpages.ubuntu.com/manpages/xenial/en/man1/asy.1.html
[at]: http://manpages.ubuntu.com/manpages/xenial/en/man1/at.1.html
[atc]: http://manpages.ubuntu.com/manpages/xenial/en/man6/atc.6.html
[atool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/atool.1.html
[atop]: http://manpages.ubuntu.com/manpages/xenial/en/man1/atop.1.html
[atq]: http://manpages.ubuntu.com/manpages/xenial/en/man1/atq.1.html
[atrm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/atrm.1.html
[audiopreview]: http://manpages.ubuntu.com/manpages/wily/en/man1/audiopreview.1.html
[audtty]: http://manpages.ubuntu.com/manpages/xenial/en/man1/audtty.1.html
[aumix]: http://manpages.ubuntu.com/manpages/xenial/en/man1/aumix.1.html
[avconv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/avconv.1.html
[avidemux]: http://manpages.ubuntu.com/manpages/wily/en/man1/avidemux.1.html
[avplay]: http://manpages.ubuntu.com/manpages/xenial/en/man1/avplay.1.html
[avprobe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/avprobe.1.html
[awk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/awk.1posix.html
[axe]: http://manpages.ubuntu.com/manpages/xenial/en/man8/axe.8fun.html
[axel]: http://manpages.ubuntu.com/manpages/xenial/en/man1/axel.1.html
[babeltrace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/babeltrace.1.html
[baby]: http://manpages.ubuntu.com/manpages/xenial/en/man1/baby.1fun.html
[backgammon]: http://manpages.ubuntu.com/manpages/xenial/en/man6/backgammon.6.html
[backup-manager]: http://manpages.ubuntu.com/manpages/xenial/en/man8/backup-manager.8.html
[badblocks]: http://manpages.ubuntu.com/manpages/xenial/en/man8/badblocks.8.html
[base64]: http://manpages.ubuntu.com/manpages/xenial/en/man1/base64.1.html
[basename]: http://manpages.ubuntu.com/manpages/xenial/en/man1/basename.1.html
[bash]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bash.1.html
[bashburn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bashburn.1.html
[bastet]: http://manpages.ubuntu.com/manpages/xenial/en/man6/bastet.6.html
[batch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/batch.1.html
[battlestar]: http://manpages.ubuntu.com/manpages/xenial/en/man6/battlestar.6.html
[bbackupctl]: http://manpages.ubuntu.com/manpages/xenial/en/man8/bbackupctl.8.html
[bbe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bbe.1.html
[bc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bc.1.html
[bchunk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bchunk.1.html
[bcpp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bcpp.1.html
[bcrypt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bcrypt.1.html
[bg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bg.1posix.html
[binclock]: http://manpages.ubuntu.com/manpages/xenial/en/man1/binclock.1.html
[binstats]: http://manpages.ubuntu.com/manpages/xenial/en/man1/binstats.1.html
[binwalk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/binwalk.1.html
[BitchX]: http://man.cx/bitchx
[bitlbee]: http://manpages.ubuntu.com/manpages/xenial/en/man8/bitlbee.8.html
[bittorrent-downloader]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bittorrent-downloader.bittornado.1.html
[blktrace]: http://manpages.ubuntu.com/manpages/xenial/en/man8/blktrace.8.html
[blockdev]: http://manpages.ubuntu.com/manpages/xenial/en/man8/blockdev.8.html
[bmon]: http://manpages.ubuntu.com/manpages/xenial/en/man8/bmon.8.html
[boggle]: http://manpages.ubuntu.com/manpages/xenial/en/man6/boggle.6.html
[bosskill]: http://manpages.ubuntu.com/manpages/xenial/en/man8/bosskill.8fun.html
[bplay]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bplay.1.html
[brec]: http://manpages.ubuntu.com/manpages/xenial/en/man1/brec.1.html
[bsdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bsdiff.1.html
[bspatch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bspatch.1.html
[btdownloadcurses]: http://manpages.ubuntu.com/manpages/xenial/en/man1/btdownloadcurses.bittornado.1.html
[bti]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bti.1.html
[bunzip2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bunzip2.1.html
[burn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/burn.1.html
[bwn-ng]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bwm-ng.1.html
[byobu]: http://manpages.ubuntu.com/manpages/xenial/en/man1/byobu.1.html
[bzcat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bzcat.1.html
[bzcmp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bzcmp.1.html
[bzdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bzdiff.1.html
[bzexe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bzexe.1.html
[bzgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bzgrep.1.html
[bzip2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bzip2.1.html
[bzless]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bzless.1.html
[bzmore]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bzmore.1.html
[bzr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bzr.1.html
[c]: http://manpages.ubuntu.com/manpages/xenial/en/man1/c.1fun.html
[c99]: http://manpages.ubuntu.com/manpages/xenial/en/man1/c99.1posix.html
[cabextract]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cabextract.1.html
[cacaview]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cacaview.1.html
[cadubi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cadubi.1.html
[cal]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cal.1.html
[calc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/calc.1.html
[calcurse]: http://manpages.ubuntu.com/manpages/xenial/en/man1/calcurse.1.html
[cancel]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cancel.1.html
[canfield]: http://manpages.ubuntu.com/manpages/xenial/en/man6/canfield.6.html
[canto]: http://manpages.ubuntu.com/manpages/trusty/en/man1/canto.1.html
[capabilities]: http://manpages.ubuntu.com/manpages/xenial/en/man7/capabilities.7.html
[captoinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/captoinfo.1.html
[cat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cat.1.html
[catdoc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/catdoc.1.html
[catdvi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/catdvi.1.html
[cbm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cbm.1.html
[cclive]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cclive.1.html
[ccon]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ccon.1p.html
[ccrypt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ccrypt.1.html
[ccze]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ccze.1.html
[cd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cd.1posix.html
[cdadd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdadd.1.html
[cdcd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdcd.1.html
[cdclose]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdclose.1.html
[cdctrl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdctrl.1.html
[cdda2mp3]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdrkit.cdda2ogg.1.html
[cdda2ogg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdrkit.cdda2ogg.1.html
[cdeject]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdeject.1.html
[cdinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdinfo.1.html
[cdir]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdir.1.html
[cdown]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdown.1.html
[cdparanoia]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdparanoia.1.html
[cdpause]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdpause.1.html
[cdplay]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdplay.1.html
[cdrdao]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdrdao.1.html
[cdrecord]: http://man.cx/cdrecord
[cdshuffle]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdshuffle.1.html
[cdstop]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdstop.1.html
[cdvolume]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdvolume.1.html
[cdw]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cdw.1.html
[celibacy]: http://manpages.ubuntu.com/manpages/xenial/en/man1/celibacy.1fun.html
[centerim]: http://manpages.ubuntu.com/manpages/trusty/en/man1/centerim.1.html
[cfdisk]: http://manpages.ubuntu.com/manpages/xenial/en/man8/cfdisk.8.html
[cflow]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cflow.1.html
[chage]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chage.1.html
[chainsaw]: http://manpages.ubuntu.com/manpages/xenial/en/man8/chainsaw.8fun.html
[chastise]: http://manpages.ubuntu.com/manpages/xenial/en/man3/chastise.3fun.html
[chattr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chattr.1.html
[chcon]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chcon.1.html
[checkrestart]: http://manpages.ubuntu.com/manpages/xenial/en/man1/checkrestart.1.html
[chfn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chfn.1.html
[chgrp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chgrp.1.html
[chkconfig]: http://manpages.ubuntu.com/manpages/precise/en/man8/chkconfig.8.html
[chm2pdf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chm2pdf.1.html
[chmod]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chmod.1.html
[chown]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chown.1.html
[chronic]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chronic.1.html
[chroot]: http://manpages.ubuntu.com/manpages/xenial/en/man8/chroot.8.html
[chsh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chsh.1.html
[chvt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/chvt.1.html
[ci]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ci.1.html
[circo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/circo.1.html
[cjpeg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cjpeg.1.html
[cksum]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cksum.1.html
[clamscan]: http://manpages.ubuntu.com/manpages/xenial/en/man1/clamscan.1.html
[cleanlinks]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cleanlinks.1.html
[clear]: http://manpages.ubuntu.com/manpages/xenial/en/man1/clear.1.html
[clex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/clex.1.html
[clisp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/clisp.1.html
[cloc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cloc.1.html
[cmake]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cmake.1.html
[cmatrix]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cmatrix.1.html
[cmp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cmp.1.html
[cmus]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cmus.1.html
[co]: http://manpages.ubuntu.com/manpages/xenial/en/man1/co.1.html
[col]: http://manpages.ubuntu.com/manpages/xenial/en/man1/col.1.html
[collectl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/collectl.1.html
[colrm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/colrm.1.html
[column]: http://manpages.ubuntu.com/manpages/xenial/en/man1/column.1.html
[combine]: http://manpages.ubuntu.com/manpages/xenial/en/man1/combine.1.html
[comm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/comm.1.html
[compress]: http://manpages.ubuntu.com/manpages/xenial/en/man1/compress.1.html
[condom]: http://manpages.ubuntu.com/manpages/xenial/en/man1/condom.1fun.html
[cone]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cone.1.html
[convert]: http://manpages.ubuntu.com/manpages/xenial/en/man1/convert.1.html
[convertquota]: http://manpages.ubuntu.com/manpages/xenial/en/man8/convertquota.8.html
[convmv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/convmv.1.html
[cowsay]: http://manpages.ubuntu.com/manpages/xenial/en/man6/cowsay.6.html
[cp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cp.1.html
[cpan]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cpan.1.html
[cpio]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cpio.1.html
[cplay]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cplay.1.html
[cpp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cpp.1.html
[cpulimit]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cpulimit.1.html
[crash]: http://manpages.ubuntu.com/manpages/xenial/en/man8/crash.8.html
[crawl]: http://manpages.ubuntu.com/manpages/xenial/en/man6/crawl.6.html
[cream]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cream.1.html
[cribbage]: http://manpages.ubuntu.com/manpages/xenial/en/man6/cribbage.6.html
[crip]: http://manpages.ubuntu.com/manpages/xenial/en/man1/crip.1.html
[crontab]: http://manpages.ubuntu.com/manpages/xenial/en/man1/crontab.1.html
[crsh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/crsh.1p.html
[crypt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/crypt.1.html
[cryptcat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cryptcat.1.html
[cscope]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cscope.1.html
[csh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bsd-csh.1.html
[csplit]: http://manpages.ubuntu.com/manpages/xenial/en/man1/csplit.1.html
[cssh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cssh.1p.html
[csstidy]: http://manpages.ubuntu.com/manpages/xenial/en/man1/csstidy.1.html
[csv2latex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/csv2latex.1.html
[csvtool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/csvtool.1.html
[ctags]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ctags.1posix.html
[ctel]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ctel.1p.html
[ctluser]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ctluser.8fun.html
[ctorrent]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ctorrent.1.html
[cupsaccept]: http://manpages.ubuntu.com/manpages/xenial/en/man8/cupsaccept.8.html
[cupsdisable]: http://manpages.ubuntu.com/manpages/xenial/en/man8/cupsdisable.8.html
[cupsenable]: http://manpages.ubuntu.com/manpages/xenial/en/man8/cupsenable.8.html
[cupsreject]: http://manpages.ubuntu.com/manpages/xenial/en/man8/cupsreject.8.html
[curl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/curl.1.html
[curlftpfs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/curlftpfs.1.html
[cut]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cut.1.html
[cutmp3]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cutmp3.1.html
[cutter]: http://manpages.ubuntu.com/manpages/xenial/en/man8/cutter.8fun.html
[cvs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cvs.1.html
[cxref]: http://manpages.ubuntu.com/manpages/xenial/en/man1/cxref.1.html
[darcs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/darcs.1.html
[darkstat]: http://manpages.ubuntu.com/manpages/xenial/en/man8/darkstat.8.html
[dash]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dash.1.html
[date]: http://manpages.ubuntu.com/manpages/xenial/en/man1/date.1.html
[dblatex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dblatex.1.html
[dbus-monitor]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dbus-monitor.1.html
[dbus-send]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dbus-send.1.html
[dbview]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dbview.1.html
[dc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dc.1.html
[dcfldd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dcfldd.1.html
[dd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dd.1.html
[ddate]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ddate.1.html
[ddrescue]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ddrescue.1.html
[deallocvt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/deallocvt.1.html
[debconf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/debconf.1.html
[debconf-get-selections]: http://manpages.ubuntu.com/manpages/xenial/en/man1/debconf-get-selections.1.html
[debconf-set-selections]: http://manpages.ubuntu.com/manpages/xenial/en/man1/debconf-set-selections.1.html
[debfoster]: http://manpages.ubuntu.com/manpages/xenial/en/man8/debfoster.8.html
[debian-reference]: http://manpages.ubuntu.com/manpages/xenial/en/man1/debian-reference.1.html
[debmany]: http://manpages.ubuntu.com/manpages/xenial/en/man1/debmany.1.html
[deborphan]: http://manpages.ubuntu.com/manpages/xenial/en/man1/deborphan.1.html
[debugfs]: http://manpages.ubuntu.com/manpages/xenial/en/man8/debugfs.8.html
[depmod]: http://manpages.ubuntu.com/manpages/xenial/en/man8/depmod.8.html
[deroff]: http://man.cx/deroff
[detox]: http://manpages.ubuntu.com/manpages/xenial/en/man1/detox.1.html
[devilspie]: http://manpages.ubuntu.com/manpages/xenial/en/man1/devilspie.1.html
[devtodo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/devtodo.1.html
[df]: http://manpages.ubuntu.com/manpages/xenial/en/man1/df.1.html
[dfc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dfc.1.html
[dglob]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dglob.1.html
[dgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dgrep.1.html
[dhex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dhex.1.html
[diakonos]: http://manpages.ubuntu.com/manpages/trusty/en/man1/diakonos.1.html
[dialog]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dialog.1.html
[dict]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dict.1.html
[diff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/diff.1.html
[diff3]: http://manpages.ubuntu.com/manpages/xenial/en/man1/diff3.1.html
[diffpdf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/diffpdf.1.html
[diffstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/diffstat.1.html
[dig]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dig.1.html
[dir]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dir.1.html
[dircolors]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dircolors.1.html
[dirdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dirdiff.1.html
[dirname]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dirname.1.html
[dirs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bash.1.html
[discus]: http://manpages.ubuntu.com/manpages/xenial/en/man1/discus.1.html
[disown]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bash.1.html
[display-dhammapada]: http://manpages.ubuntu.com/manpages/xenial/en/man1/display-dhammapada.1.html
[djpeg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/djpeg.1.html
[dlocate]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dlocate.1.html
[dmake]: http://manpages.ubuntu.com/manpages/precise/en/man1/dmake.1.html
[dmenu]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dmenu.1.html
[dmesg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dmesg.1.html
[dmidecode]: http://manpages.ubuntu.com/manpages/xenial/en/man8/dmidecode.8.html
[dnsdomainname]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dnsdomainname.1.html
[dnstracer]: http://manpages.ubuntu.com/manpages/xenial/en/man8/dnstracer.8.html
[docx2txt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/docx2txt.1.html
[domainname]: http://manpages.ubuntu.com/manpages/xenial/en/man1/domainname.1.html
[doodle]: http://manpages.ubuntu.com/manpages/xenial/en/man1/doodle.1.html
[dos2unix]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dos2unix.1.html
[dot]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dot.1.html
[dpigs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dpigs.1.html
[dpkg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dpkg.1.html
[dpkg-reconfigure]: http://manpages.ubuntu.com/manpages/xenial/en/man8/dpkg-reconfigure.8.html
[dselect]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dselect.1.html
[dsniff]: http://manpages.ubuntu.com/manpages/xenial/en/man8/dsniff.8.html
[dstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dstat.1.html
[dtach]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dtach.1.html
[dtrace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dtrace.1.html
[dtrx]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dtrx.1.html
[du]: http://manpages.ubuntu.com/manpages/xenial/en/man1/du.1.html
[dump]: http://manpages.ubuntu.com/manpages/xenial/en/man8/dump.8.html
[dumpcap]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dumpcap.1.html
[dumpkeys]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dumpkeys.1.html
[duplicity]: http://manpages.ubuntu.com/manpages/xenial/en/man1/duplicity.1.html
[dvdauthor]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dvdauthor.1.html
[dvtm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/dvtm.1.html
[e2dbg]: http://man.cx/eresi
[ecasound]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ecasound.1.html
[echo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/echo.1.html
[ed]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ed.1.html
[edbrowse]: http://manpages.ubuntu.com/manpages/xenial/en/man1/edbrowse.1.html
[editres]: http://manpages.ubuntu.com/manpages/xenial/en/man1/editres.1.html
[edquota]: http://manpages.ubuntu.com/manpages/xenial/en/man8/edquota.8.html
[efax]: http://manpages.ubuntu.com/manpages/xenial/en/man1/efax.1.html
[egrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/egrep.1.html
[egrope]: http://manpages.ubuntu.com/manpages/xenial/en/man1/egrope.1fun.html
[ekg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ekg.1.html
[elfsh]: http://man.cx/eresi
[elinks]: http://manpages.ubuntu.com/manpages/xenial/en/man1/elinks.1.html
[elmo]: http://man.cx/elmo
[emacs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/emacs24.1.html
[enc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/enc.1ssl.html
[encfs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/encfs.1.html
[encfsctl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/encfsctl.1.html
[ent]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ent.1.html
[entr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/entr.1.html
[env]: http://manpages.ubuntu.com/manpages/xenial/en/man1/env.1.html
[environ]: http://manpages.ubuntu.com/manpages/xenial/en/man7/environ.7.html
[epic5]: http://manpages.ubuntu.com/manpages/xenial/en/man1/epic5.1.html
[episoder]: http://manpages.ubuntu.com/manpages/xenial/en/man1/episoder.1.html
[eqn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/eqn.1.html
[eresi]: http://man.cx/eresi
[errno]: http://manpages.ubuntu.com/manpages/xenial/en/man1/errno.1.html
[errno.3]: http://manpages.ubuntu.com/manpages/xenial/en/man3/errno.3.html
[espeak]: http://manpages.ubuntu.com/manpages/xenial/en/man1/espeak.1.html
[etex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/etex.1.html
[ethtool]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ethtool.8.html
[etrace]: http://man.cx/eresi
[ettercap]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ettercap.8.html
[ex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ex.1posix.html
[exfalso]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exfalso.1.html
[exif]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exif.1.html
[exifcom]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exifcom.1.html
[exifgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exifgrep.1.html
[exifprobe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exifprobe.1.html
[exiftags]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exiftags.1.html
[exiftime]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exiftime.1.html
[exiftool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exiftool.1p.html
[exiftran]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exiftran.1.html
[exo-open]: http://manpages.ubuntu.com/manpages/xenial/en/man1/exo-open.1.html
[expand]: http://manpages.ubuntu.com/manpages/xenial/en/man1/expand.1.html
[expect]: http://manpages.ubuntu.com/manpages/xenial/en/man1/expect.1.html
[explain]: http://manpages.ubuntu.com/manpages/xenial/en/man1/explain.1.html
[exportfs]: http://manpages.ubuntu.com/manpages/xenial/en/man8/exportfs.8.html
[expr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/expr.1.html
[extract]: http://manpages.ubuntu.com/manpages/xenial/en/man1/extract.1.html
[f2c]: http://manpages.ubuntu.com/manpages/xenial/en/man1/f2c.1.html
[factor]: http://manpages.ubuntu.com/manpages/xenial/en/man1/factor.1.html
[fadecut]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fadecut.1.html
[fallocate]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fallocate.1.html
[false]: http://manpages.ubuntu.com/manpages/xenial/en/man1/false.1.html
[faucet]: http://manpages.ubuntu.com/manpages/xenial/en/man1/faucet.1.html
[fax]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fax.1.html
[fax2ps]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fax2ps.1.html
[faxalter]: http://manpages.ubuntu.com/manpages/xenial/en/man1/faxalter.1.html
[faxcover]: http://manpages.ubuntu.com/manpages/xenial/en/man1/faxcover.1.html
[faxmail]: http://manpages.ubuntu.com/manpages/xenial/en/man1/faxmail.1.html
[faxq]: http://manpages.ubuntu.com/manpages/xenial/en/man1/faxq.1.html
[faxrm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/faxrm.1.html
[faxrunq]: http://manpages.ubuntu.com/manpages/xenial/en/man1/faxrunq.1.html
[faxspool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/faxspool.1.html
[faxstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/faxstat.1.html
[fbgrab]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fbgrab.1.html
[fbgs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fbgs.1.html
[fbi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fbi.1.html
[fc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fc.1.html
[fc-cache]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fc-cache.1.html
[fc-cat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fc-cat.1.html
[fc-list]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fc-list.1.html
[fc-match]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fc-match.1.html
[fc-pattern]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fc-pattern.1.html
[fc-query]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fc-query.1.html
[fc-scan]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fc-scan.1.html
[fdformat]: http://manpages.ubuntu.com/manpages/xenial/en/man8/fdformat.8.html
[fdisk]: http://manpages.ubuntu.com/manpages/xenial/en/man8/fdisk.8.html
[fdp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fdp.1.html
[fdupes]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fdupes.1.html
[festival]: http://manpages.ubuntu.com/manpages/xenial/en/man1/festival.1.html
[fetchyahoo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fetchyahoo.1.html
[ffmpeg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ffmpeg.1.html
[fg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fg.1posix.html
[fgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fgrep.1.html
[fgrope]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fgrope.1fun.html
[figlet]: http://manpages.ubuntu.com/manpages/precise/en/man6/figlet.6.html
[file]: http://manpages.ubuntu.com/manpages/xenial/en/man1/file.1.html
[file-hierarchy]: http://manpages.ubuntu.com/manpages/xenial/en/man7/file-hierarchy.7.html
[fim]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fim.1.html
[finch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/finch.1.html
[find]: http://manpages.ubuntu.com/manpages/xenial/en/man1/find.1.html
[findimagedupes]: http://manpages.ubuntu.com/manpages/xenial/en/man1/findimagedupes.1p.html
[findmnt]: http://manpages.ubuntu.com/manpages/xenial/en/man8/findmnt.8.html
[finger]: http://manpages.ubuntu.com/manpages/xenial/en/man1/finger.1.html
[fio]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fio.1.html
[fish]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fish.1.html
[fizsh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fizsh.1.html
[flac]: http://manpages.ubuntu.com/manpages/xenial/en/man1/flac.1.html
[flame]: http://manpages.ubuntu.com/manpages/xenial/en/man1/flame.1fun.html
[flex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/flex.1.html
[flickrfs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/flickrfs.1.html
[flock]: http://manpages.ubuntu.com/manpages/xenial/en/man1/flock.1.html
[flog]: http://manpages.ubuntu.com/manpages/xenial/en/man1/flog.1fun.html
[fmt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fmt.1.html
[fold]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fold.1.html
[foremost]: http://manpages.ubuntu.com/manpages/xenial/en/man8/foremost.8.html
[fort77]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fort77.1.html
[fortune]: http://manpages.ubuntu.com/manpages/xenial/en/man6/fortune.6.html
[free]: http://manpages.ubuntu.com/manpages/xenial/en/man1/free.1.html
[freetalk]: http://manpages.ubuntu.com/manpages/trusty/en/man1/freetalk.1.html
[fsck]: http://manpages.ubuntu.com/manpages/xenial/en/man8/fsck.8.html
[fsniper]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fsniper.1.html
[ftff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ftff.1.html
[ftp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ftp-ssl.1.html
[fuser]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fuser.1.html
[fusermount]: http://manpages.ubuntu.com/manpages/xenial/en/man1/fusermount.1.html
[gammu]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gammu.1.html
[gawk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gawk.1.html
[gcal]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gcal.1.html
[gcalcli]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gcalcli.1.html
[gcc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gcc.1.html
[gdb]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gdb.1.html
[gem]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gem.1.html
[gencat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gencat.1.html
[genisoimage]: http://manpages.ubuntu.com/manpages/xenial/en/man1/genisoimage.1.html
[get_flash_videos]: http://manpages.ubuntu.com/manpages/xenial/en/man1/get_flash_videos.1p.html
[getconf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/getconf.1.html
[getfacl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/getfacl.1.html
[getfattr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/getfattr.1.html
[getopt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/getopt.1.html
[ghc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ghc.1.html
[ghci]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ghci.1.html
[gifsicle]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gifsicle.1.html
[git]: http://manpages.ubuntu.com/manpages/xenial/en/man1/git.1.html
[git-sh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/git-sh.1.html
[gitfm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gitfm.1.html
[gitps]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gitps.1.html
[gittutorial]: http://manpages.ubuntu.com/manpages/xenial/en/man7/gittutorial.7.html
[gitunpack]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gitunpack.1.html
[gitview]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gitview.1.html
[gitwipe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gitwipe.1.html
[glances]: http://manpages.ubuntu.com/manpages/xenial/en/man1/glances.1.html
[gle]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gle.1.html
[glob]: http://manpages.ubuntu.com/manpages/xenial/en/man7/glob.7.html
[glxinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/glxinfo.1.html
[gm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gm.1.html
[gnome-open]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gnome-open.1.html
[gnuhtml2latex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gnuhtml2latex.1.html
[gnuplot]: http://manpages.ubuntu.com/manpages/trusty/en/man1/gnuplot.1.html
[gocr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gocr.1.html
[goldendict]: http://manpages.ubuntu.com/manpages/xenial/en/man1/goldendict.1.html
[gong]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gong.1fun.html
[google]: http://manpages.ubuntu.com/manpages/wily/en/man1/google.1.html
[gopher]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gopher.1.html
[gpg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gpg.1.html
[gpgv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gpgv.1.html
[gphotofs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gphotofs.1.html
[gprof]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gprof.1.html
[gramofile]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gramofile.1.html
[greed]: http://manpages.ubuntu.com/manpages/xenial/en/man6/greed.6.html
[grep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/grep.1.html
[gringotts]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gringotts.1.html
[groff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/groff.1.html
[grope]: http://manpages.ubuntu.com/manpages/xenial/en/man1/grope.1fun.html
[groupadd]: http://manpages.ubuntu.com/manpages/xenial/en/man8/groupadd.8.html
[groupdel]: http://manpages.ubuntu.com/manpages/xenial/en/man8/groupdel.8.html
[groupmod]: http://manpages.ubuntu.com/manpages/xenial/en/man8/groupmod.8.html
[groups]: http://manpages.ubuntu.com/manpages/xenial/en/man1/groups.1.html
[growisofs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/growisofs.1.html
[grub]: http://manpages.ubuntu.com/manpages/xenial/en/man8/grub.8.html
[gs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gs.1.html
[gtypist]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gtypist.1.html
[gunzip]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gunzip.1.html
[guru]: http://manpages.ubuntu.com/manpages/xenial/en/man8/guru.8fun.html
[gv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gv.1.html
[gzexe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gzexe.1.html
[gzip]: http://manpages.ubuntu.com/manpages/xenial/en/man1/gzip.1.html
[halt]: http://manpages.ubuntu.com/manpages/trusty/en/man8/halt.8.html
[hangman]: http://manpages.ubuntu.com/manpages/xenial/en/man6/hangman.6.html
[hardlink]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hardlink.1.html
[hdparm]: http://manpages.ubuntu.com/manpages/xenial/en/man8/hdparm.8.html
[head]: http://manpages.ubuntu.com/manpages/xenial/en/man1/head.1.html
[help]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bash.1.html
[herrie]: http://man.cx/herrie
[hexdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hexdiff.1.html
[hexdump]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hexdump.1.html
[hexedit]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hexedit.1.html
[hg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hg.1.html
[hier]: http://manpages.ubuntu.com/manpages/xenial/en/man7/hier.7.html
[highlight]: http://manpages.ubuntu.com/manpages/xenial/en/man1/highlight.1.html
[hnb]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hnb.1.html
[hose]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hose.1.html
[host]: http://manpages.ubuntu.com/manpages/xenial/en/man1/host.1.html
[hostid]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hostid.1.html
[hostname]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hostname.1.html
[hping3]: http://manpages.ubuntu.com/manpages/xenial/en/man8/hping3.8.html
[hpodder]: http://manpages.ubuntu.com/manpages/precise/en/man1/hpodder.1.html
[hte]: http://manpages.ubuntu.com/manpages/xenial/en/man1/hte.1.html
[html2markdown]: http://manpages.ubuntu.com/manpages/xenial/en/man1/html2markdown.py2.1.html
[html2text]: http://manpages.ubuntu.com/manpages/xenial/en/man1/html2text.1.html
[htop]: http://manpages.ubuntu.com/manpages/xenial/en/man1/htop.1.html
[httpry]: http://manpages.ubuntu.com/manpages/xenial/en/man1/httpry.1.html
[httrack]: http://manpages.ubuntu.com/manpages/xenial/en/man1/httrack.1.html
[hunt]: http://manpages.ubuntu.com/manpages/xenial/en/man6/hunt.6.html
[hwinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man8/hwinfo.8.html
[iconv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/iconv.1.html
[icotool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/icotool.1.html
[id]: http://manpages.ubuntu.com/manpages/xenial/en/man1/id.1.html
[id3]: http://manpages.ubuntu.com/manpages/xenial/en/man1/id3.1.html
[id3ed]: http://man.cx/id3ed
[id3tool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/id3tool.1.html
[id3v2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/id3v2.1.html
[ident]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ident.1.html
[identify]: http://manpages.ubuntu.com/manpages/xenial/en/man1/identify.1.html
[ifconfig]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ifconfig.8.html
[ifdata]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ifdata.1.html
[ifdown]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ifdown.8.html
[ifetch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ifetch.1.html
[ifne]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ifne.1.html
[ifstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ifstat.1.html
[iftop]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iftop.8.html
[ifup]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ifup.8.html
[ii]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ii.1.html
[imdb]: http://manpages.ubuntu.com/manpages/trusty/en/man1/imdb.1.html
[imdb-fxd]: http://manpages.ubuntu.com/manpages/trusty/en/man1/imdb-fxd.1.html
[imdb-get]: http://manpages.ubuntu.com/manpages/trusty/en/man1/imdb-get.1.html
[imdb-link]: http://manpages.ubuntu.com/manpages/trusty/en/man1/imdb-link.1.html
[imdb-rename]: http://manpages.ubuntu.com/manpages/trusty/en/man1/imdb-rename.1.html
[imdb-update-cache]: http://manpages.ubuntu.com/manpages/trusty/en/man1/imdb-update-cache.1.html
[img2txt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/img2txt.1.html
[import]: http://manpages.ubuntu.com/manpages/xenial/en/man1/import.1.html
[imvirt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/imvirt.1.html
[indent]: http://manpages.ubuntu.com/manpages/xenial/en/man1/indent.1.html
[info]: http://manpages.ubuntu.com/manpages/xenial/en/man1/info.1.html
[infocmp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/infocmp.1.html
[infotocap]: http://manpages.ubuntu.com/manpages/xenial/en/man1/infotocap.1.html
[initctl]: http://manpages.ubuntu.com/manpages/xenial/en/man8/initctl.8.html
[ink]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ink.1.html
[inkscape]: http://manpages.ubuntu.com/manpages/xenial/en/man1/inkscape.1.html
[inotifywait]: http://manpages.ubuntu.com/manpages/xenial/en/man1/inotifywait.1.html
[inotifywatch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/inotifywatch.1.html
[insmod]: http://manpages.ubuntu.com/manpages/xenial/en/man8/insmod.8.html
[install]: http://manpages.ubuntu.com/manpages/xenial/en/man1/install.1.html
[intro.1]: http://manpages.ubuntu.com/manpages/xenial/en/man1/intro.1.html
[intro.2]: http://manpages.ubuntu.com/manpages/xenial/en/man2/intro.2.html
[intro.3]: http://manpages.ubuntu.com/manpages/xenial/en/man3/intro.3.html
[intro.4]: http://manpages.ubuntu.com/manpages/xenial/en/man4/intro.4.html
[intro.5]: http://manpages.ubuntu.com/manpages/xenial/en/man5/intro.5.html
[intro.6]: http://manpages.ubuntu.com/manpages/xenial/en/man6/intro.6.html
[intro.7]: http://manpages.ubuntu.com/manpages/xenial/en/man7/intro.7.html
[intro.8]: http://manpages.ubuntu.com/manpages/xenial/en/man8/intro.8.html
[inxi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/inxi.1.html
[ionice]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ionice.1.html
[iostat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/iostat.1.html
[iotop]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iotop.8.html
[ip]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ip.8.html
[ip-tunnel]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ip-tunnel.8.html
[ip6tables]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ip6tables.8.html
[ip6tables-restore]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ip6tables-restore.8.html
[ip6tables-save]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ip6tables-save.8.html
[ipcalc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ipcalc.1.html
[ipchains]: http://man.cx/ipchains
[ipcrm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ipcrm.1.html
[ipcs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ipcs.1.html
[iperf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/iperf.1.html
[iptables]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iptables.8.html
[iptables-restore]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iptables-restore.8.html
[iptables-save]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iptables-save.8.html
[iptraf]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iptraf.8.html
[iptstate]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iptables.8.html
[ipv6calc]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ipv6calc.8.html
[irb]: http://manpages.ubuntu.com/manpages/xenial/en/man1/irb.1.html
[irssi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/irssi.1.html
[isadump]: http://manpages.ubuntu.com/manpages/xenial/en/man8/isadump.8.html
[ispell]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ispell.1.html
[isutf8]: http://manpages.ubuntu.com/manpages/xenial/en/man1/isutf8.1.html
[iw]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iw.8.html
[iwconfig]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iwconfig.8.html
[iwevent]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iwevent.8.html
[iwgetid]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iwgetid.8.html
[iwlist]: http://manpages.ubuntu.com/manpages/xenial/en/man8/iwlist.8.html
[jack]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jack.1.html
[jardiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jardiff.1.html
[java]: http://man.cx/java
[javac]: http://man.cx/javac
[javadoc]: http://man.cx/javadoc
[jed]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jed.1.html
[jhead]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jhead.1.html
[jnettop]: http://manpages.ubuntu.com/manpages/xenial/en/man8/jnettop.8.html
[jobs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jobs.1posix.html
[jodconverter]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jodconverter.1.html
[join]: http://manpages.ubuntu.com/manpages/xenial/en/man1/join.1.html
[jot]: http://manpages.ubuntu.com/manpages/xenial/en/man1/athena-jot.1.html
[journalctl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/journalctl.1.html
[jp2a]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jp2a.1.html
[jpegtran]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jpegtran.1.html
[jq]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jq.1.html
[js_beautify]: http://manpages.ubuntu.com/manpages/xenial/en/man1/js_beautify.1p.html
[jsoncat]: http://manpages.ubuntu.com/manpages/trusty/en/man1/jsoncat.1.html
[jsonlint]: http://manpages.ubuntu.com/manpages/xenial/en/man1/jsonlint.1.html
[justniffer]: http://justniffer.sourceforge.net/#!/man_page
[kdialog]: http://man.cx/kdialog
[kibitz]: http://manpages.ubuntu.com/manpages/xenial/en/man1/kibitz.1.html
[kill]: http://manpages.ubuntu.com/manpages/xenial/en/man1/kill.1.html
[killall]: http://manpages.ubuntu.com/manpages/xenial/en/man1/killall.1.html
[kismet]: http://manpages.ubuntu.com/manpages/xenial/en/man1/kismet.1.html
[knife]: http://manpages.ubuntu.com/manpages/xenial/en/man8/knife.8fun.html
[konqueror]: http://manpages.ubuntu.com/manpages/xenial/en/man1/konqueror.1.html
[ksh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ksh93.1.html
[ktap]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ktap.1.html
[lame]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lame.1.html
[lart]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lart.1fun.html
[last]: http://manpages.ubuntu.com/manpages/xenial/en/man1/last.1.html
[lastb]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lastb.1.html
[lastcomm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lastcomm.1.html
[lastlog]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lastlog.8.html
[latex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/latex.1.html
[latexdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/latexdiff.1.html
[latexmk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/latexmk.1L.html
[lckdo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lckdo.1.html
[ld]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ld.1.html
[ld.so]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ld.so.8.html
[ldconfig]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ldconfig.8.html
[ldd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ldd.1.html
[LDP]: http://manpages.ubuntu.com/manpages/wily/en/man7/LDP.7.html
[ledger]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ledger.1.html
[less]: http://manpages.ubuntu.com/manpages/xenial/en/man1/less.1.html
[lex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lex.1.html
[lftp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lftp.1.html
[libc]: http://manpages.ubuntu.com/manpages/xenial/en/man7/libc.7.html
[lilo]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lilo.8.html
[link]: http://manpages.ubuntu.com/manpages/xenial/en/man1/link.1.html
[linkchecker]: http://manpages.ubuntu.com/manpages/xenial/en/man1/linkchecker.1.html
[links]: http://manpages.ubuntu.com/manpages/xenial/en/man1/links.1.html
[links2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/links2.1.html
[linux_logo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/linux_logo.1.html
[listres]: http://manpages.ubuntu.com/manpages/xenial/en/man1/listres.1.html
[lldpad]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lldpad.8.html
[lldptool]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lldptool.8.html
[llines]: http://manpages.ubuntu.com/manpages/xenial/en/man1/llines.1.html
[llttng]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lttng.1.html
[lmbench]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lmbench.8.html
[ln]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ln.1.html
[lnav]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lnav.1.html
[loadkeys]: http://manpages.ubuntu.com/manpages/xenial/en/man1/loadkeys.1.html
[locale]: http://manpages.ubuntu.com/manpages/xenial/en/man1/locale.1.html
[locale.7]: http://manpages.ubuntu.com/manpages/xenial/en/man7/locale.7.html
[localedef]: http://manpages.ubuntu.com/manpages/xenial/en/man1/localedef.1.html
[locate]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mlocate.1.html
[logger]: http://manpages.ubuntu.com/manpages/xenial/en/man1/logger.1.html
[loginctl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/loginctl.1.html
[logname]: http://manpages.ubuntu.com/manpages/xenial/en/man1/logname.1.html
[logwatch]: http://manpages.ubuntu.com/manpages/xenial/en/man8/logwatch.8.html
[lolcat]: http://manpages.ubuntu.com/manpages/xenial/en/man6/lolcat.6.html
[look]: http://manpages.ubuntu.com/manpages/xenial/en/man1/look.1.html
[lp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lp.1.html
[lpadmin]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lpadmin.8.html
[lpc]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lpc.8.html
[lpmove]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lpmove.8.html
[lpoptions]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lpoptions.1.html
[lpq]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lpq.1.html
[lpr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lpr.1.html
[lprm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lprm.1.html
[lpstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lpstat.1.html
[ls]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ls.1.html
[lsattr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lsattr.1.html
[lsb_release]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lsb_release.1.html
[lsblk]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lsblk.8.html
[lsdev]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lsdev.8.html
[lshal]: http://manpages.ubuntu.com/manpages/precise/en/man1/lshal.1.html
[lshw]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lshw.1.html
[lslk]: http://man.cx/lslk
[lsmod]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lsmod.8.html
[lsof]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lsof.8.html
[lspci]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lspci.8.html
[lsusb]: http://manpages.ubuntu.com/manpages/xenial/en/man8/lsusb.8.html
[ltrace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ltrace.1.html
[lua]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lua5.1.1.html
[luac]: http://manpages.ubuntu.com/manpages/xenial/en/man1/luac5.1.1.html
[luadoc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/luadoc.1.html
[luarocks]: http://manpages.ubuntu.com/manpages/xenial/en/man1/luarocks.1.html
[luser]: http://manpages.ubuntu.com/manpages/xenial/en/man8/luser.8fun.html
[lxsplit]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lxsplit.1.html
[lynx]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lynx.1.html
[lz]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lz.1.html
[lzip]: http://manpages.ubuntu.com/manpages/trusty/en/man1/lzip.1.html
[lzma]: http://manpages.ubuntu.com/manpages/xenial/en/man1/lzmp.1.html
[lzma2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xz.1.html
[m4]: http://manpages.ubuntu.com/manpages/xenial/en/man1/m4.1.html
[mad]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mad.1.html
[madplay]: http://manpages.ubuntu.com/manpages/xenial/en/man1/madplay.1.html
[mail]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mailx.1posix.html
[mailx]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mailx.1posix.html
[make]: http://manpages.ubuntu.com/manpages/xenial/en/man1/make.1.html
[makepasswd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/makepasswd.1.html
[man]: http://manpages.ubuntu.com/manpages/xenial/en/man1/man.1.html
[man-pages]: http://manpages.ubuntu.com/manpages/xenial/en/man7/man-pages.7.html
[markdown]: http://manpages.ubuntu.com/manpages/xenial/en/man1/markdown.1.html
[mathomatic]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mathomatic.1.html
[mawk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mawk.1.html
[maxima]: http://manpages.ubuntu.com/manpages/xenial/en/man1/maxima.1.html
[mc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mc.1.html
[mcabber]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mcabber.1.html
[mcdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mcdiff.1.html
[mcdp]: http://manpages.ubuntu.com/manpages/precise/en/man1/mcdp.1.html
[mcedit]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mcedit.1.html
[mcp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mcp.1.html
[mcrypt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mcrypt.1.html
[mcview]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mcview.1.html
[md5pass]: http://manpages.ubuntu.com/manpages/xenial/en/man1/md5pass.1.html
[md5sum]: http://manpages.ubuntu.com/manpages/xenial/en/man1/md5sum.1.html
[mediainfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mediainfo.1.html
[memdump]: http://manpages.ubuntu.com/manpages/xenial/en/man1/memdump.1.html
[mencoder]: http://manpages.ubuntu.com/manpages/trusty/en/man1/mencoder.1.html
[merge]: http://manpages.ubuntu.com/manpages/xenial/en/man1/merge.1.html
[mesg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mesg.1.html
[mf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mf.1.html
[mgetty]: http://manpages.ubuntu.com/manpages/xenial/en/man8/mgetty.8.html
[mhddfs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mhddfs.1.html
[midi2abc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/midi2abc.1.html
[mii-tool]: http://manpages.ubuntu.com/manpages/xenial/en/man8/mii-tool.8.html
[mikmod]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mikmod.1.html
[mille]: http://manpages.ubuntu.com/manpages/xenial/en/man6/mille.6.html
[mimeopen]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mimeopen.1p.html
[mimetype]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mimetype.1p.html
[minicom]: http://manpages.ubuntu.com/manpages/xenial/en/man1/minicom.1.html
[mispipe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mispipe.1.html
[missing]: http://manpages.ubuntu.com/manpages/wily/en/man7/missing.7.html
[mkdir]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mkdir.1.html
[mkfifo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mkfifo.1.html
[mkfs]: http://manpages.ubuntu.com/manpages/xenial/en/man8/mkfs.8.html
[mkisofs]: http://man.cx/mkisofs
[mknod]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mknod.1.html
[mksh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mksh.1.html
[mktemp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mktemp.1.html
[mktorrent]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mktorrent.1.html
[mln]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mln.1.html
[mmv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mmv.1.html
[mocp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mocp.1.html
[modconf]: http://man.cx/modconf
[modinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man8/modinfo.8.html
[modprobe]: http://manpages.ubuntu.com/manpages/xenial/en/man8/modprobe.8.html
[mogrify]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mogrify.1.html
[monop]: http://manpages.ubuntu.com/manpages/xenial/en/man6/monop.6.html
[moon-buggy]: http://manpages.ubuntu.com/manpages/xenial/en/man6/moon-buggy.6.html
[moosic]: http://manpages.ubuntu.com/manpages/xenial/en/man1/moosic.1.html
[more]: http://manpages.ubuntu.com/manpages/xenial/en/man1/more.1.html
[most]: http://manpages.ubuntu.com/manpages/xenial/en/man1/most.1.html
[mount]: http://manpages.ubuntu.com/manpages/xenial/en/man8/mount.8.html
[mountpoint]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mountpoint.1.html
[mp3blaster]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mp3blaster.1.html
[mp3burn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mp3burn.1.html
[mpc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mpc.1.html
[mpc123]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mpc123.1.html
[mpg123]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mpg123.bin.1.html
[mpg321]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mpg321.1.html
[mpgtx]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mpgtx.1.html
[mplayer]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mplayer.1.html
[mplex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mplex.1.html
[mpstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mpstat.1.html
[msmtp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/msmtp.1.html
[msort]: http://manpages.ubuntu.com/manpages/xenial/en/man1/msort.1.html
[mt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mt.1.html
[mtools]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mtools.1.html
[mtr]: http://manpages.ubuntu.com/manpages/xenial/en/man8/mtr.8.html
[mtrace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mtrace.1.html
[mulk]: http://mulk.sourceforge.net/
[multitail]: http://manpages.ubuntu.com/manpages/xenial/en/man1/multitail.1.html
[multitee]: http://manpages.ubuntu.com/manpages/xenial/en/man1/multitee.1.html
[mussort]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mussort.1.html
[mutool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mutool.1.html
[mutt]: http://manpages.ubuntu.com/manpages/trusty/en/man1/mutt.1.html
[mv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mv.1.html
[mybashburn]: http://man.cx/mybashburn
[mysql]: http://manpages.ubuntu.com/manpages/xenial/en/man1/mysql.1.html
[nano]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nano.1.html
[nasm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nasm.1.html
[nc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nc.traditional.1.html
[ncal]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ncal.1.html
[ncat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ncat.1.html
[ncdu]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ncdu.1.html
[ncftp]: http://man.cx/ncftp
[ncftpget]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ncftpget.1.html
[ncftpput]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ncftpput.1.html
[ncmpc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ncmpc.1.html
[ndiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ndiff.1.html
[neato]: http://manpages.ubuntu.com/manpages/xenial/en/man1/neato.1.html
[neqn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/neqn.1.html
[nethack]: http://manpages.ubuntu.com/manpages/xenial/en/man6/nethack.6.html
[nethogs]: http://manpages.ubuntu.com/manpages/xenial/en/man8/nethogs.8.html
[netload]: http://manpages.ubuntu.com/manpages/xenial/en/man1/netload.1.html
[netrik]: http://manpages.ubuntu.com/manpages/xenial/en/man1/netrik.1.html
[netstat]: http://manpages.ubuntu.com/manpages/xenial/en/man8/netstat.8.html
[netwatch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/netwatch.1.html
[newgrp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/newgrp.1.html
[newsbeuter]: http://manpages.ubuntu.com/manpages/xenial/en/man1/newsbeuter.1.html
[newusers]: http://manpages.ubuntu.com/manpages/xenial/en/man8/newusers.8.html
[nfsiostat]: http://manpages.ubuntu.com/manpages/trusty/en/man1/nfsiostat.1.html
[nfsstat]: http://manpages.ubuntu.com/manpages/xenial/en/man8/nfsstat.8.html
[ngrep]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ngrep.8.html
[nice]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nice.1.html
[nicstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nicstat.1.html
[ninvaders]: http://manpages.ubuntu.com/manpages/xenial/en/man6/ninvaders.6.html
[nisdomainname]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nisdomainname.1.html
[nl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nl.1.html
[nload]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nload.1.html
[nm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nm.1.html
[nm-tool]: http://manpages.ubuntu.com/manpages/trusty/en/man1/nm-tool.1.html
[nmap]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nmap.1.html
[nmcli]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nmcli.1.html
[nmon]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nmon.1.html
[nmtui]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nmtui.1.html
[nn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nn.1.html
[node]: http://manpages.ubuntu.com/manpages/xenial/en/man1/node.1.html
[nohup]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nohup.1.html
[normality]: http://manpages.ubuntu.com/manpages/xenial/en/man5/normality.5fun.html
[normalize-audio]: http://manpages.ubuntu.com/manpages/xenial/en/man1/normalize-audio.1.html
[notify-send]: http://manpages.ubuntu.com/manpages/xenial/en/man1/notify-send.1.html
[notmuch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/notmuch.1.html
[nping]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nping.1.html
[nproc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nproc.1.html
[nroff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nroff.1.html
[nrss]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nrss.1.html
[nslookup]: http://manpages.ubuntu.com/manpages/xenial/en/man1/nslookup.1.html
[ntop]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ntop.8.html
[ntopng]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ntopng.8.html
[ntptrace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ntptrace.1.html
[nuke]: http://manpages.ubuntu.com/manpages/xenial/en/man8/nuke.8fun.html
[numaverage]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numaverage.1.html
[numbound]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numbound.1.html
[numfmt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numfmt.1.html
[numgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numgrep.1.html
[numinterval]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numinterval.1.html
[numnormalize]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numnormalize.1.html
[numprocess]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numprocess.1.html
[numrandom]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numrandom.1.html
[numrange]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numrange.1.html
[numround]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numround.1.html
[numsum]: http://manpages.ubuntu.com/manpages/xenial/en/man1/numsum.1.html
[nuttcp]: http://manpages.ubuntu.com/manpages/xenial/en/man8/nuttcp.8.html
[o3read]: http://man.cx/o3read
[o3tohtml]: http://man.cx/o3tohtml
[o3totxt]: http://man.cx/o3totxt
[objcopy]: http://manpages.ubuntu.com/manpages/xenial/en/man1/objcopy.1.html
[objdump]: http://manpages.ubuntu.com/manpages/xenial/en/man1/objdump.1.html
[ocp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ocp.1.html
[octave]: http://manpages.ubuntu.com/manpages/xenial/en/man1/octave.1.html
[od]: http://manpages.ubuntu.com/manpages/xenial/en/man1/od.1.html
[odt2txt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/odt2txt.odt2txt.1.html
[ogg123]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ogg123.1.html
[oggenc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/oggenc.1.html
[oleo]: http://man.cx/oleo
[olive]: http://manpages.ubuntu.com/manpages/xenial/en/man1/olive.1.html
[op]: http://man.cx/op
[openssl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/openssl.1ssl.html
[openvt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/open.1.html
[optipng]: http://manpages.ubuntu.com/manpages/xenial/en/man1/optipng.1.html
[orpheus]: http://man.cx/orpheus
[osd_cat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/osd_cat.1.html
[overkill]: http://man.cx/overkill
[p0f]: http://manpages.ubuntu.com/manpages/xenial/en/man1/p0f.1.html
[pacman]: https://www.archlinux.org/pacman/pacman.8.html
[pactl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pactl.1.html
[pal]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pal.1.html
[pandoc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pandoc.1.html
[paperconfig]: http://manpages.ubuntu.com/manpages/xenial/en/man8/paperconfig.8.html
[par]: http://manpages.ubuntu.com/manpages/xenial/en/man1/par.1.html
[par2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/par2.1.html
[parallel]: http://manpages.ubuntu.com/manpages/xenial/en/man1/parallel.1.html
[parted]: http://manpages.ubuntu.com/manpages/xenial/en/man8/parted.8.html
[party]: http://manpages.ubuntu.com/manpages/xenial/en/man1/party.1fun.html
[passwd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/passwd.1.html
[paste]: http://manpages.ubuntu.com/manpages/xenial/en/man1/paste.1.html
[patch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/patch.1.html
[patchwork]: http://manpages.ubuntu.com/manpages/xenial/en/man1/patchwork.1.html
[pathchk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pathchk.1.html
[patool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/patool.1.html
[pax]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pax.1.html
[pbzip2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pbzip2.1.html
[pcal]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pcal.1.html
[pcapdump]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pcapdump.1.html
[pcapip]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pcapip.1.html
[pcappick]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pcappick.1.html
[pcapuc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pcapuc.1.html
[pchar]: http://manpages.ubuntu.com/manpages/xenial/en/man8/pchar.8.html
[pcrepattern]: http://manpages.ubuntu.com/manpages/xenial/en/man3/pcrepattern.3.html
[pcresyntax]: http://manpages.ubuntu.com/manpages/xenial/en/man3/pcresyntax.3.html
[pdffonts]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdffonts.1.html
[pdfimages]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdfimages.1.html
[pdfinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdfinfo.1.html
[pdfjam]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdfjam.1.html
[pdfseparate]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdfseparate.1.html
[pdftex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdftex.1.html
[pdftk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdftk.1.html
[pdftocairo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdftocairo.1.html
[pdftohtml]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdftohtml.1.html
[pdftoppm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdftoppm.1.html
[pdftops]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdftops.1.html
[pdftotext]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdftotext.1.html
[pdfunite]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pdfunite.1.html
[pdksh]: http://manpages.ubuntu.com/manpages/wily/en/man1/pdksh.1.html
[pee]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pee.1.html
[people]: http://manpages.ubuntu.com/manpages/xenial/en/man2/people.2fun.html
[pepper]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pepper.1.html
[perf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perf.1.html
[perf-list]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perf-list.1.html
[perf-stat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perf-stat.1.html
[perf-top]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perf-top.1.html
[perl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perl.1.html
[perlbug]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perlbug.1.html
[perlcheat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perlcheat.1.html
[perlcritic]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perlcritic.1p.html
[perldoc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perldoc.1.html
[perlintro]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perlintro.1.html
[perltidy]: http://manpages.ubuntu.com/manpages/xenial/en/man1/perltidy.1p.html
[pg]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pg.1.html
[pgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pgrep.1.html
[phantasia]: http://manpages.ubuntu.com/manpages/xenial/en/man6/phantasia.6.html
[photorec]: http://manpages.ubuntu.com/manpages/xenial/en/man8/photorec.8.html
[php]: http://manpages.ubuntu.com/manpages/wily/en/man1/php5.1.html
[pico]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pico.alpine.1.html
[pidof]: http://manpages.ubuntu.com/manpages/xenial/en/man8/pidof.8.html
[pidstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pidstat.1.html
[pigz]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pigz.1.html
[pilot]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pilot.1.html
[ping]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ping.8.html
[pkill]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pkill.1.html
[pktstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pktstat.1.html
[play]: http://manpages.ubuntu.com/manpages/xenial/en/man1/play.1.html
[playmidi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/playmidi.1.html
[pmap]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pmap.1.html
[pmidi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pmidi.1.html
[pmsd]: http://manpages.ubuntu.com/manpages/xenial/en/man8/pmsd.8fun.html
[pngcrush]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pngcrush.1.html
[pnpdump]: http://man.cx/pnpdump
[podget]: http://manpages.ubuntu.com/manpages/xenial/en/man7/podget.7.html
[podracer]: http://manpages.ubuntu.com/manpages/xenial/en/man1/podracer.1.html
[popbugs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/popbugs.1.html
[popcon-largest-unused]: http://manpages.ubuntu.com/manpages/xenial/en/man8/popcon-largest-unused.8.html
[popd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bash.1.html
[popularity-contest]: http://manpages.ubuntu.com/manpages/xenial/en/man8/popularity-contest.8.html
[pork]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pork.1.html
[posixoptions]: http://manpages.ubuntu.com/manpages/xenial/en/man7/posixoptions.7.html
[potrace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/potrace.1.html
[povray]: http://manpages.ubuntu.com/manpages/xenial/en/man1/povray.1.html
[poweroff]: http://manpages.ubuntu.com/manpages/trusty/en/man8/poweroff.8.html
[powertop]: http://manpages.ubuntu.com/manpages/xenial/en/man8/powertop.8.html
[ppthtml]: http://manpages.ubuntu.com/manpages/trusty/en/man1/ppthtml.1.html
[pr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pr.1.html
[prename]: http://manpages.ubuntu.com/manpages/xenial/en/man1/prename.1.html
[primes]: http://manpages.ubuntu.com/manpages/xenial/en/man1/primes.1.html
[primes.6]: http://manpages.ubuntu.com/manpages/xenial/en/man6/primes.6.html
[printenv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/printenv.1.html
[printf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/printf.1.html
[printf]: http://manpages.ubuntu.com/manpages/xenial/en/man3/printf.3.html
[procinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man8/procinfo.8.html
[prtstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/prtstat.1.html
[ps]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ps.1.html
[ps2ascii]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ps2ascii.1.html
[ps2pdf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ps2pdf.1.html
[psed]: http://manpages.ubuntu.com/manpages/wily/en/man1/psed.1.html
[psql]: http://manpages.ubuntu.com/manpages/xenial/en/man1/psql.1.html
[psselect]: http://manpages.ubuntu.com/manpages/xenial/en/man1/psselect.1.html
[pstack]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pstack.1.html
[pstree]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pstree.1.html
[ptunnel]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ptunnel.8.html
[pushd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/bash.1.html
[pv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pv.1.html
[pwd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pwd.1.html
[pwgen]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pwgen.1.html
[pwsafe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pwsafe.1.html
[pxz]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pxz.1.html
[pychecker]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pychecker.1.html
[pycompile]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pycompile.1.html
[pydf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pydf.1.html
[pydoc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pydoc.1.html
[python]: http://manpages.ubuntu.com/manpages/xenial/en/man1/python.1.html
[pytone]: http://manpages.ubuntu.com/manpages/xenial/en/man1/pytone.1.html
[pytris]: http://man.cx/pytris
[qalc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qalc.1.html
[qcp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qcp.1.html
[qdbus]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qdbus.1.html
[qmp3check]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qmp3check.1.html
[qmp3cut]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qmp3cut.1.html
[qmp3info]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qmp3info.1.html
[qmp3join]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qmp3join.1.html
[qmp3report]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qmp3report.1.html
[qmv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qmv.1.html
[qrencode]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qrencode.1.html
[quelcom]: http://manpages.ubuntu.com/manpages/xenial/en/man1/quelcom.1.html
[quilt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/quilt.1.html
[quiz]: http://manpages.ubuntu.com/manpages/xenial/en/man6/quiz.6.html
[quota]: http://manpages.ubuntu.com/manpages/precise/en/man8/quota.8.html
[quotacheck]: http://manpages.ubuntu.com/manpages/xenial/en/man8/quotacheck.8.html
[quotaoff]: http://manpages.ubuntu.com/manpages/xenial/en/man8/quotaoff.8.html
[quotaon]: http://manpages.ubuntu.com/manpages/xenial/en/man8/quotaon.8.html
[quvi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/quvi.1.html
[qwavcut]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qwavcut.1.html
[qwavfade]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qwavfade.1.html
[qwavheaderdump]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qwavheaderdump.1.html
[qwavinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qwavinfo.1.html
[qwavjoin]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qwavjoin.1.html
[qwavsilence]: http://manpages.ubuntu.com/manpages/xenial/en/man1/qwavsilence.1.html
[R]: http://manpages.ubuntu.com/manpages/xenial/en/man1/R.1.html
[r2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/r2.1.html
[rabin2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rabin2.1.html
[radiff2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/radiff2.1.html
[rafind2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rafind2.1.html
[raggle]: http://man.cx/raggle
[rahash2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rahash2.1.html
[rain]: http://manpages.ubuntu.com/manpages/xenial/en/man6/rain.6.html
[random]: http://manpages.ubuntu.com/manpages/xenial/en/man4/random.4.html
[ranger]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ranger.1.html
[rar]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rar.1.html
[rarp]: http://manpages.ubuntu.com/manpages/xenial/en/man8/rarp.8.html
[rarun2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rarun2.1.html
[rasm2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rasm2.1.html
[rasterizer]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rasterizer.1.html
[rawdog]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rawdog.1.html
[rax2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rax2.1.html
[rc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rc.1.html
[rcp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/netkit-rcp.1.html
[rcs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rcs.1.html
[rdfind]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rdfind.1.html
[rdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rdiff.1.html
[rdist]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rdist.1.html
[rdjpgcom]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rdjpgcom.1.html
[rdup]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rdup.1.html
[readelf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/readelf.1.html
[readline]: http://manpages.ubuntu.com/manpages/xenial/en/man3/readline.3readline.html
[readlink]: http://manpages.ubuntu.com/manpages/xenial/en/man1/readlink.1.html
[realpath]: http://manpages.ubuntu.com/manpages/xenial/en/man1/realpath.1.html
[reboot]: http://manpages.ubuntu.com/manpages/precise/en/man8/reboot.8.html
[rec]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rec.1.html
[recode]: http://manpages.ubuntu.com/manpages/xenial/en/man1/recode.1.html
[red]: http://manpages.ubuntu.com/manpages/xenial/en/man1/red.1.html
[regex]: http://manpages.ubuntu.com/manpages/xenial/en/man7/regex.7.html
[remind]: http://manpages.ubuntu.com/manpages/xenial/en/man1/remind.1.html
[rename]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rename.ul.1.html
[renice]: http://manpages.ubuntu.com/manpages/xenial/en/man1/renice.1.html
[repquota]: http://manpages.ubuntu.com/manpages/xenial/en/man8/repquota.8.html
[reptyr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/reptyr.1.html
[rescrog]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rescrog.1fun.html
[reset]: http://manpages.ubuntu.com/manpages/xenial/en/man1/reset.1.html
[restore]: http://manpages.ubuntu.com/manpages/xenial/en/man8/restore.8.html
[rev]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rev.1.html
[rexima]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rexima.1.html
[rfcdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rfcdiff.1.html
[rgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rgrep.1.html
[rhash]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rhash.1.html
[rifle]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rifle.1.html
[rig]: http://manpages.ubuntu.com/manpages/xenial/en/man6/rig.6.html
[ripit]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ripit.1.html
[rlogin]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rsh-redone-rlogin.1.html
[rm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rm.1.html
[rmdir]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rmdir.1.html
[rmmod]: http://manpages.ubuntu.com/manpages/xenial/en/man8/rmmod.8.html
[rmtpdump]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rtmpdump.1.html
[robots]: http://manpages.ubuntu.com/manpages/xenial/en/man6/robots.6.html
[rogue]: http://manpages.ubuntu.com/manpages/xenial/en/man6/rogue.6.html
[route]: http://manpages.ubuntu.com/manpages/xenial/en/man8/route.8.html
[rpm]: http://manpages.ubuntu.com/manpages/xenial/en/man8/rpm.8.html
[rrdtool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rrdtool.1.html
[rs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rs.1.html
[rsh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/netkit-rsh.1.html
[rsstail]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rsstail.1.html
[rst2pdf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rst2pdf.1.html
[rsync]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rsync.1.html
[rsyncrypto]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rsyncrypto.1.html
[rtfm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rtfm.1fun.html
[rtorrent]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rtorrent.1.html
[ruby]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ruby.1.html
[runcon]: http://manpages.ubuntu.com/manpages/xenial/en/man1/runcon.1.html
[runlevel]: http://manpages.ubuntu.com/manpages/xenial/en/man8/runlevel.8.html
[rwho]: http://manpages.ubuntu.com/manpages/xenial/en/man1/rwho.1.html
[s2p]: http://manpages.ubuntu.com/manpages/wily/en/man1/s2p.1.html
[sa]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sa.8.html
[safecopy]: http://manpages.ubuntu.com/manpages/xenial/en/man1/safecopy.1.html
[saidar]: http://manpages.ubuntu.com/manpages/xenial/en/man1/saidar.1.html
[sail]: http://manpages.ubuntu.com/manpages/xenial/en/man6/sail.6.html
[sar]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sar.sysstat.1.html
[saydate]: http://man.cx/saydate
[saytime]: http://manpages.ubuntu.com/manpages/xenial/en/man1/saytime.1.html
[sc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sc.1.html
[scanimage]: http://manpages.ubuntu.com/manpages/xenial/en/man1/scanimage.1.html
[scanmem]: http://manpages.ubuntu.com/manpages/xenial/en/man1/scanmem.1.html
[scapy]: http://manpages.ubuntu.com/manpages/xenial/en/man1/scapy.1.html
[schroot]: http://manpages.ubuntu.com/manpages/xenial/en/man1/schroot.1.html
[scp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/scp.1.html
[screen]: http://manpages.ubuntu.com/manpages/xenial/en/man1/screen.1.html
[screenfetch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/screenfetch.1.html
[script]: http://manpages.ubuntu.com/manpages/xenial/en/man1/script.1.html
[scriptreplay]: http://manpages.ubuntu.com/manpages/xenial/en/man1/scriptreplay.1.html
[scrypt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/scrypt.1.html
[scsiinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man8/scsiinfo.8.html
[sdcv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sdcv.1.html
[sdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sdiff.1.html
[sed]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sed.1.html
[sendfax]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sendfax.1.html
[sendpage]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sendpage.1.html
[seq]: http://manpages.ubuntu.com/manpages/xenial/en/man1/seq.1.html
[service]: http://manpages.ubuntu.com/manpages/xenial/en/man8/service.8.html
[setfacl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/setfacl.1.html
[setfattr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/setfattr.1.html
[setleds]: http://manpages.ubuntu.com/manpages/xenial/en/man1/setleds.1.html
[setpci]: http://manpages.ubuntu.com/manpages/xenial/en/man8/setpci.8.html
[setquota]: http://manpages.ubuntu.com/manpages/xenial/en/man8/setquota.8.html
[setserial]: http://manpages.ubuntu.com/manpages/xenial/en/man8/setserial.8.html
[setsid]: http://manpages.ubuntu.com/manpages/xenial/en/man1/setsid.1.html
[setterm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/setterm.1.html
[setuid]: http://manpages.ubuntu.com/manpages/xenial/en/man1/setuid.1.html
[setxkbmap]: http://manpages.ubuntu.com/manpages/xenial/en/man1/setxkbmap.1.html
[sex]: http://manpages.ubuntu.com/manpages/xenial/en/man6/sex.6fun.html
[sfdp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sfdp.1.html
[sftp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sftp.1.html
[sg_map]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sg_map.8.html
[sginfo]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sginfo.8.html
[sgml2latex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sgml2latex.1.html
[sgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sgrep.1.html
[sh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sh.1.html
[shar]: http://manpages.ubuntu.com/manpages/xenial/en/man1/shar.1.html
[shasum]: http://manpages.ubuntu.com/manpages/xenial/en/man1/shasum.1.html
[shell-fm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/shell-fm.1.html
[shellcheck]: http://manpages.ubuntu.com/manpages/xenial/en/man1/shellcheck.1.html
[showkey]: http://manpages.ubuntu.com/manpages/xenial/en/man1/showkey.1.html
[showmount]: http://manpages.ubuntu.com/manpages/xenial/en/man8/showmount.8.html
[shred]: http://manpages.ubuntu.com/manpages/xenial/en/man1/shred.1.html
[shuf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/shuf.1.html
[shush]: http://manpages.ubuntu.com/manpages/xenial/en/man1/shush.1.html
[shutdown]: http://manpages.ubuntu.com/manpages/xenial/en/man8/shutdown.8.html
[sic]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sic.1.html
[siege]: http://manpages.ubuntu.com/manpages/xenial/en/man1/siege.1.html
[signal]: http://manpages.ubuntu.com/manpages/xenial/en/man7/signal.7.html
[simple-scan]: http://manpages.ubuntu.com/manpages/xenial/en/man1/simple-scan.1.html
[since]: http://manpages.ubuntu.com/manpages/xenial/en/man1/since.1.html
[sipcalc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sipcalc.1.html
[skill]: http://manpages.ubuntu.com/manpages/xenial/en/man1/skill.1.html
[slabtop]: http://manpages.ubuntu.com/manpages/xenial/en/man1/slabtop.1.html
[slashem]: http://manpages.ubuntu.com/manpages/xenial/en/man6/slashem.6.html
[slave]: http://manpages.ubuntu.com/manpages/xenial/en/man1/slave.1fun.html
[sleep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sleep.1.html
[sln]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sln.8.html
[sloccount]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sloccount.1.html
[slrn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/slrn.1.html
[slsc]: http://manpages.ubuntu.com/manpages/xenial/it/man1/slsc.1.html
[slurm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/slurm.1.html
[smart]: http://manpages.ubuntu.com/manpages/xenial/en/man8/smart.8.html
[smartctl]: http://manpages.ubuntu.com/manpages/xenial/en/man8/smartctl.8.html
[smbclient]: http://manpages.ubuntu.com/manpages/xenial/en/man1/smbclient.1.html
[snake]: http://manpages.ubuntu.com/manpages/xenial/en/man6/snake.6.html
[snd]: http://manpages.ubuntu.com/manpages/wily/en/man1/snd.1.html
[snice]: http://manpages.ubuntu.com/manpages/xenial/en/man1/snice.1.html
[sniffit]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sniffit.8.html
[snmpcmd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/snmpcmd.1.html
[snmpget]: http://manpages.ubuntu.com/manpages/xenial/en/man1/snmpget.1.html
[snmpwalk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/snmpwalk.1.html
[snort]: http://manpages.ubuntu.com/manpages/xenial/en/man8/snort.8.html
[snownews]: http://man.cx/snownews
[sntop]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sntop.1.html
[socat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/socat.1.html
[socklist]: http://manpages.ubuntu.com/manpages/xenial/en/man8/socklist.8.html
[sockstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sockstat.1.html
[sort]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sort.1.html
[sox]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sox.1.html
[spc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/spc.1.html
[speedometer]: http://manpages.ubuntu.com/manpages/xenial/en/man1/speedometer.1.html
[spell]: http://manpages.ubuntu.com/manpages/xenial/en/man1/spell.1.html
[splay]: http://manpages.ubuntu.com/manpages/xenial/en/man1/splay.1.html
[split]: http://manpages.ubuntu.com/manpages/xenial/en/man1/split.1.html
[sponge]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sponge.1.html
[sq]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sq.1.html
[sql]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sql.1.html
[sqlite]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sqlite.1.html
[sqlite3]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sqlite3.1.html
[ss]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ss.8.html
[ssconvert]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ssconvert.1.html
[ssdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ssdiff.1.html
[ssgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ssgrep.1.html
[ssh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ssh.1.html
[ssh-copy-id]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ssh-copy-id.1.html
[ssh-keygen]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ssh-keygen.1.html
[sshfs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sshfs.1.html
[sshmitm]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sshmitm.8.html
[sshow]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sshow.8.html
[ssindex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ssindex.1.html
[sslscan]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sslscan.1.html
[standards]: http://manpages.ubuntu.com/manpages/xenial/en/man7/standards.7.html
[stap]: http://manpages.ubuntu.com/manpages/xenial/en/man1/stap.1.html
[start]: http://manpages.ubuntu.com/manpages/xenial/en/man8/start.8.html
[stat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/stat.1.html
[status]: http://manpages.ubuntu.com/manpages/xenial/en/man8/status.8.html
[stdbuf]: http://manpages.ubuntu.com/manpages/xenial/en/man1/stdbuf.1.html
[stegbreak]: http://man.cx/stegbreak
[stegdetect]: http://man.cx/stegdetect
[steghide]: http://manpages.ubuntu.com/manpages/xenial/en/man1/steghide.1.html
[stop]: http://manpages.ubuntu.com/manpages/xenial/en/man8/stop.8.html
[stow]: http://manpages.ubuntu.com/manpages/xenial/en/man8/stow.8.html
[strace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/strace.1.html
[strfry]: http://manpages.ubuntu.com/manpages/xenial/en/man3/strfry.3fun.html
[strftime]: http://manpages.ubuntu.com/manpages/xenial/en/man3/strftime.3.html
[strings]: http://manpages.ubuntu.com/manpages/xenial/en/man1/strings.1.html
[strip]: http://manpages.ubuntu.com/manpages/xenial/en/man1/strip.1.html
[stty]: http://manpages.ubuntu.com/manpages/xenial/en/man1/stty.1.html
[stunnel]: http://manpages.ubuntu.com/manpages/xenial/en/man8/stunnel.8.html
[stx2any]: http://manpages.ubuntu.com/manpages/xenial/en/man1/stx2any.1.html
[su]: http://manpages.ubuntu.com/manpages/xenial/en/man1/su.1.html
[subnetcalc]: http://manpages.ubuntu.com/manpages/xenial/en/man8/subnetcalc.8.html
[sudo]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sudo.8.html
[sudoedit]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sudoedit.8.html
[sum]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sum.1.html
[surfraw]: http://manpages.ubuntu.com/manpages/xenial/en/man1/surfraw.1.html
[suricata]: http://manpages.ubuntu.com/manpages/xenial/en/man8/suricata.8.html
[svn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/svn.1.html
[swapoff]: http://manpages.ubuntu.com/manpages/xenial/en/man8/swapoff.8.html
[swapon]: http://manpages.ubuntu.com/manpages/xenial/en/man8/swapon.8.html
[swatch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/swatch.1p.html
[synaptic]: http://manpages.ubuntu.com/manpages/xenial/en/man8/synaptic.8.html
[sync]: http://manpages.ubuntu.com/manpages/trusty/en/man8/sync.8.html
[sysadmin]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sysadmin.1fun.html
[sysbench]: http://manpages.ubuntu.com/manpages/xenial/en/man1/sysbench.1.html
[sysctl]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sysctl.8.html
[sysdig]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sysdig.8.html
[systemctl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/systemctl.1.html
[sysv-rc-conf]: http://manpages.ubuntu.com/manpages/xenial/en/man8/sysv-rc-conf.8.html
[tabs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tabs.1.html
[tac]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tac.1.html
[tail]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tail.1.html
[talk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/talk.1posix.html
[tar]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tar.1.html
[tarsnap]: https://manned.org/tarsnap.1
[task]: http://manpages.ubuntu.com/manpages/xenial/en/man1/task.1.html
[taskset]: http://manpages.ubuntu.com/manpages/xenial/en/man1/taskset.1.html
[tbl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tbl.1.html
[tc]: http://manpages.ubuntu.com/manpages/xenial/en/man8/tc.8.html
[tcpdump]: http://manpages.ubuntu.com/manpages/xenial/en/man8/tcpdump.8.html
[tcpflow]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tcpflow.1.html
[tcpick]: http://manpages.ubuntu.com/manpages/xenial/en/man8/tcpick.8.html
[tcpkill]: http://manpages.ubuntu.com/manpages/xenial/en/man8/tcpkill.8.html
[tcpnice]: http://manpages.ubuntu.com/manpages/xenial/en/man8/tcpnice.8.html
[tcpreen]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tcpreen.1.html
[tcpspy]: http://manpages.ubuntu.com/manpages/xenial/en/man8/tcpspy.8.html
[tcptrace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tcptrace.1.html
[tcptrack]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tcptrack.1.html
[tcsh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tcsh.1.html
[tdl]: http://manpages.ubuntu.com/manpages/precise/en/man1/tdl.1.html
[teapot]: https://www.syntax-k.de/projekte/teapot/
[tee]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tee.1.html
[telinit]: http://manpages.ubuntu.com/manpages/xenial/en/man8/telinit.8.html
[telnet]: http://manpages.ubuntu.com/manpages/xenial/en/man1/inetutils-telnet.1.html
[terminfo]: http://manpages.ubuntu.com/manpages/xenial/en/man5/terminfo.5.html
[tesseract]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tesseract.1.html
[test]: http://manpages.ubuntu.com/manpages/xenial/en/man1/test.1.html
[tetheral]: http://man.cx/tethereal
[tetris-bsd]: http://manpages.ubuntu.com/manpages/xenial/en/man6/tetris-bsd.6.html
[tex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tex.1.html
[textfmt]: http://manpages.ubuntu.com/manpages/xenial/en/man1/textfmt.1.html
[think]: http://manpages.ubuntu.com/manpages/xenial/en/man1/think.1fun.html
[tic]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tic.1.html
[tidy]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tidy.1.html
[tig]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tig.1.html
[time]: http://manpages.ubuntu.com/manpages/xenial/en/man1/time.1.html
[timeout]: http://manpages.ubuntu.com/manpages/xenial/en/man1/timeout.1.html
[times]: http://manpages.ubuntu.com/manpages/xenial/en/man1/times.1posix.html
[timidity]: http://manpages.ubuntu.com/manpages/xenial/en/man1/timidity.1.html
[tin]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tin.1.html
[tinyirc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tinyirc.1.html
[tiptop]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tiptop.1.html
[tircd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tircd.1.html
[tload]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tload.1.html
[tm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tm.1fun.html
[tmux]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tmux.1.html
[todo.sh]: http://todotxt.com/
[toe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/toe.1.html
[toilet]: http://manpages.ubuntu.com/manpages/xenial/en/man1/toilet.1.html
[top]: http://manpages.ubuntu.com/manpages/xenial/en/man1/top.1.html
[touch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/touch.1.html
[tpp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tpp.1.html
[tput]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tput.1.html
[tr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tr.1.html
[trace-cmd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/trace-cmd.1.html
[trace-cmd-list]: http://manpages.ubuntu.com/manpages/xenial/en/man1/trace-cmd-list.1.html
[tracepath]: http://manpages.ubuntu.com/manpages/xenial/en/man8/tracepath.8.html
[traceroute]: http://manpages.ubuntu.com/manpages/precise/en/man1/tcptraceroute.mt.1.html
[trafshow]: http://manpages.ubuntu.com/manpages/xenial/en/man1/trafshow.1.html
[trash]: http://manpages.ubuntu.com/manpages/xenial/en/man1/trash.1.html
[trash-empty]: http://manpages.ubuntu.com/manpages/xenial/en/man1/trash-empty.1.html
[trash-list]: http://manpages.ubuntu.com/manpages/xenial/en/man1/trash-list.1.html
[trash-restore]: http://manpages.ubuntu.com/manpages/precise/en/man1/trash-restore.1.html
[tree]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tree.1.html
[trek]: http://manpages.ubuntu.com/manpages/xenial/en/man6/trek.6.html
[trickle]: http://manpages.ubuntu.com/manpages/xenial/en/man1/trickle.1.html
[trn]: http://manpages.ubuntu.com/manpages/xenial/en/man1/trn3.1.html
[troff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/troff.1.html
[true]: http://manpages.ubuntu.com/manpages/xenial/en/man1/true.1.html
[truncate]: http://manpages.ubuntu.com/manpages/xenial/en/man1/truncate.1.html
[ts]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ts.1.html
[tshark]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tshark.1.html
[tsort]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tsort.1.html
[tsung]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tsung.1.html
[ttm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ttm.1.html
[tty]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tty.1.html
[tty-clock]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tty-clock.1.html
[ttyplay]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ttyplay.1.html
[ttyrec]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ttyrec.1.html
[tudu]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tudu.1.html
[tune2fs]: http://manpages.ubuntu.com/manpages/xenial/en/man8/tune2fs.8.html
[tweak]: http://manpages.ubuntu.com/manpages/xenial/en/man1/tweak.1.html
[twidge]: http://manpages.ubuntu.com/manpages/xenial/en/man1/twidge.1.html
[twin]: http://man.cx/twin
[twopi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/twopi.1.html
[twyt]: http://man.cx/twyt
[txt2html]: http://manpages.ubuntu.com/manpages/xenial/en/man1/txt2html.1p.html
[txt2man]: http://manpages.ubuntu.com/manpages/xenial/en/man1/txt2man.1.html
[txt2pdbdoc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/txt2pdbdoc.1.html
[txt2regex]: http://manpages.ubuntu.com/manpages/xenial/en/man1/txt2regex.1.html
[txt2tags]: http://manpages.ubuntu.com/manpages/xenial/en/man1/txt2tags.1.html
[type]: http://manpages.ubuntu.com/manpages/xenial/en/man1/type.1posix.html
[uchardet]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uchardet.1.html
[udevadm]: http://manpages.ubuntu.com/manpages/xenial/en/man8/udevadm.8.html
[udptunnel]: http://manpages.ubuntu.com/manpages/xenial/en/man1/udptunnel.1.html
[ufw]: http://manpages.ubuntu.com/manpages/xenial/en/man8/ufw.8.html
[umask]: http://manpages.ubuntu.com/manpages/xenial/en/man1/umask.1posix.html
[umount]: http://manpages.ubuntu.com/manpages/xenial/en/man8/umount.8.html
[unaccent]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unaccent.1.html
[unace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unace.1.html
[uname]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uname.1.html
[uncompress]: http://manpages.ubuntu.com/manpages/trusty/en/man1/uncompress.1.html
[uncrustify]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uncrustify.1.html
[undocumented.3]: http://manpages.ubuntu.com/manpages/xenial/en/man3/undocumented.3.html
[undocumented.7]: http://manpages.ubuntu.com/manpages/wily/en/man7/undocumented.7.html
[unexpand]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unexpand.1.html
[unhtml]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unhtml.1.html
[unicode]: http://manpages.ubuntu.com/manpages/xenial/en/man7/unicode.7.html
[unify]: http://manpages.ubuntu.com/manpages/precise/en/man1/unify.1.html
[uniq]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uniq.1.html
[unison]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unison-latest-stable.1.html
[units]: http://manpages.ubuntu.com/manpages/xenial/en/man1/units.1.html
[units.7]: http://manpages.ubuntu.com/manpages/xenial/en/man7/units.7.html
[unlink]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unlink.1.html
[unoconv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unoconv.1.html
[unpigz]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unpigz.1.html
[unrar]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unrar-free.1.html
[unshar]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unshar.1.html
[unsort]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unsort.1.html
[unsq]: http://manpages.ubuntu.com/manpages/xenial/en/man1/unsq.1.html
[update-alternatives]: http://manpages.ubuntu.com/manpages/trusty/en/man8/update-alternatives.8.html
[update-manager]: http://manpages.ubuntu.com/manpages/xenial/en/man8/update-manager.8.html
[updatedb]: http://manpages.ubuntu.com/manpages/xenial/en/man8/updatedb.8.html
[uptime]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uptime.1.html
[urlscan]: http://manpages.ubuntu.com/manpages/xenial/en/man1/urlscan.1.html
[urlview]: http://manpages.ubuntu.com/manpages/xenial/en/man1/urlview.1.html
[urpmi]: http://download.tuxfamily.org/magnum/doc/man/urpmi.html
[useradd]: http://manpages.ubuntu.com/manpages/xenial/en/man8/useradd.8.html
[userdel]: http://manpages.ubuntu.com/manpages/xenial/en/man8/userdel.8.html
[usermod]: http://manpages.ubuntu.com/manpages/xenial/en/man8/usermod.8.html
[users]: http://manpages.ubuntu.com/manpages/xenial/en/man1/users.1.html
[utf8tolatin1]: http://man.cx/utf8tolatin1
[uubp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uubp.1fun.html
[uucp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uucp.1.html
[uudecode]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uudecode.1.html
[uuencode]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uuencode.1.html
[uustat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uustat.1.html
[uux]: http://manpages.ubuntu.com/manpages/xenial/en/man1/uux.1.html
[vbackup]: http://manpages.ubuntu.com/manpages/xenial/en/man8/vbackup.8.html
[vdir]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vdir.1.html
[venti]: https://manned.org/venti.1
[vfu]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vfu.1.html
[vi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vi.1posix.html
[vidir]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vidir.1.html
[vifm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vifm.1.html
[vilistextum]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vilistextum.1.html
[vim]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vim.1.html
[vipe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vipe.1.html
[vlc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vlc.1.html
[vmstat]: http://manpages.ubuntu.com/manpages/xenial/en/man8/vmstat.8.html
[vnstat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/vnstat.1.html
[w]: http://manpages.ubuntu.com/manpages/xenial/en/man1/w.procps.1.html
[w2do]: http://manpages.ubuntu.com/manpages/xenial/en/man1/w2do.1.html
[w3m]: http://manpages.ubuntu.com/manpages/xenial/en/man1/w3m.1.html
[wait]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wait.1posix.html
[wall]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wall.1.html
[wargames]: http://manpages.ubuntu.com/manpages/xenial/en/man6/wargames.6.html
[watch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/watch.1.html
[wavemon]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wavemon.1.html
[wc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wc.1.html
[wcalc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wcalc.1.html
[wdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wdiff.1.html
[weather]: http://manpages.ubuntu.com/manpages/xenial/en/man1/weather.1.html
[weechat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/weechat.1.html
[wget]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wget.1.html
[whack]: http://manpages.ubuntu.com/manpages/xenial/en/man1/whack.1fun.html
[whatis]: http://manpages.ubuntu.com/manpages/xenial/en/man1/whatis.1.html
[when]: http://manpages.ubuntu.com/manpages/xenial/en/man1/when.1.html
[whereis]: http://manpages.ubuntu.com/manpages/xenial/en/man1/whereis.1.html
[which]: http://manpages.ubuntu.com/manpages/xenial/en/man1/which.1.html
[which-pkg-broke]: http://manpages.ubuntu.com/manpages/xenial/en/man1/which-pkg-broke.1.html
[whichman]: http://manpages.ubuntu.com/manpages/xenial/en/man1/whichman.1.html
[who]: http://manpages.ubuntu.com/manpages/xenial/en/man1/who.1.html
[whoami]: http://manpages.ubuntu.com/manpages/xenial/en/man1/whoami.1.html
[whohas]: http://manpages.ubuntu.com/manpages/xenial/en/man1/whohas.1.html
[whois]: http://manpages.ubuntu.com/manpages/xenial/en/man1/whois.1.html
[whowatch]: http://manpages.ubuntu.com/manpages/xenial/en/man1/whowatch.1.html
[wipe]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wipe.1.html
[wireshark]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wireshark.1.html
[wmctrl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wmctrl.1.html
[woof]: http://manpages.ubuntu.com/manpages/xenial/en/man1/woof.1.html
[wordgrinder]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wordgrinder.1.html
[wordplay]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wordplay.1.html
[workbone]: http://man.cx/workbone
[worklog]: http://manpages.ubuntu.com/manpages/xenial/en/man1/worklog.1.html
[worm]: http://manpages.ubuntu.com/manpages/xenial/en/man6/worm.6.html
[wput]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wput.1.html
[write]: http://manpages.ubuntu.com/manpages/xenial/en/man1/write.1posix.html
[wrjpgcom]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wrjpgcom.1.html
[wtf]: http://manpages.ubuntu.com/manpages/xenial/en/man6/wtf.6.html
[wump]: http://manpages.ubuntu.com/manpages/xenial/en/man6/wump.6.html
[wvdial]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wvdial.1.html
[wvWare]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wvWare.1.html
[wyrd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/wyrd.1.html
[x2x]: http://manpages.ubuntu.com/manpages/xenial/en/man1/x2x.1.html
[x86info]: http://manpages.ubuntu.com/manpages/xenial/en/man1/x86info.1.html
[xalan]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xalan.1.html
[xargs]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xargs.1.html
[xbindkeys]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xbindkeys.1.html
[xcalib]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xcalib.1.html
[xclip]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xclip.1.html
[xclipboard]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xclipboard.1.html
[xdg-open]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xdg-open.1.html
[xdotool]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xdotool.1.html
[xdpyinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xdpyinfo.1.html
[xdriinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xdriinfo.1.html
[xdvi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xdvi.1.html
[xev]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xev.1.html
[xfd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xfd.1.html
[xfontsel]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xfontsel.1.html
[xgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xgrep.1.html
[xhost]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xhost.1.html
[xine]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xine.1.html
[xine-remote]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xine-remote.1.html
[xinput]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xinput.1.html
[xkill]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xkill.1fun.html
[xlart]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xlart.1fun.html
[xlhtml]: http://manpages.ubuntu.com/manpages/trusty/en/man1/xlhtml.1.html
[xls2csv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xls2csv.1.html
[xlsfonts]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xlsfonts.1.html
[xlsx2csv]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xlsx2csv.1.html
[xmag]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xmag.1.html
[xmessage]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xmessage.1.html
[xmlcatalog]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xmlcatalog.1.html
[xmlindent]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xmlindent.1.html
[xmllint]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xmllint.1.html
[xmlstarlet]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xmlstarlet.1.html
[xmms2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xmms2.1.html
[xmodmap]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xmodmap.1.html
[xmp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xmp.1.html
[xnee]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xnee.1.html
[xorriso]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xorriso.1.html
[xprobe2]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xprobe2.1.html
[xprop]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xprop.1.html
[xrandr]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xrandr.1.html
[xrdb]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xrdb.1.html
[xset]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xset.1.html
[xsetroot]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xsetroot.1.html
[xsw]: https://code.google.com/p/xsw/wiki/Reference
[xte]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xte.1.html
[xtrace]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xtrace.1.html
[xtrlock]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xtrlock.1x.html
[Xvfb]: http://manpages.ubuntu.com/manpages/xenial/en/man1/Xvfb.1.html
[xvidtune]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xvidtune.1.html
[xvinfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xvinfo.1.html
[xwininfo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xwininfo.1.html
[xxd]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xxd.1.html
[xz]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xz.1.html
[xzcat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/xzcat.1.html
[yacc]: http://manpages.ubuntu.com/manpages/xenial/en/man1/yacc.1posix.html
[yaourt]: https://archlinux.fr/man/yaourt.8.html
[yasm]: http://manpages.ubuntu.com/manpages/xenial/en/man1/yasm.1.html
[yauap]: http://manpages.ubuntu.com/manpages/wily/en/man1/yauap.1.html
[yes]: http://manpages.ubuntu.com/manpages/xenial/en/man1/yes.1.html
[yokadi]: http://manpages.ubuntu.com/manpages/xenial/en/man1/yokadi.1.html
[youtube-dl]: http://manpages.ubuntu.com/manpages/xenial/en/man1/youtube-dl.1.html
[ypdomainname]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ypdomainname.1.html
[ytalk]: http://manpages.ubuntu.com/manpages/xenial/en/man1/ytalk.1.html
[yum]: http://manpages.ubuntu.com/manpages/xenial/en/man8/yum.8.html
[zcat]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zcat.1.html
[zcmp]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zcmp.1.html
[zdiff]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zdiff.1.html
[zenity]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zenity.1.html
[zgrep]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zgrep.1.html
[zile]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zile.1.html
[zip]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zip.1.html
[zless]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zless.1.html
[zmore]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zmore.1.html
[zonecheck]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zonecheck.1.html
[zoo]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zoo.1.html
[zrun]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zrun.1.html
[zsh]: http://manpages.ubuntu.com/manpages/xenial/en/man1/zsh.1.html
[zypper]: http://manpages.ubuntu.com/manpages/xenial/en/man8/zypper.8.html
