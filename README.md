# Linux-Commands-Mindmap + Modern Alternatives

• Mind-map Preview
https://www.xmind.net/m/taCNUs/#

• Download  it here⬇️

• Available Formats:
.png, pdf, docx, ppt, svg, md

https://github.com/0xTRAW/Linux-Commands-Mindmap/tree/main/Mindmaps/v1

![](prv.png)

## Basic File Operations

### ls

-  List files in a directory. ls does more than that.

### exa

- exa is a modern replacement for ls.

	- https://github.com/ogham/exa

### lsd

- The next gen file listing command. Backwards compatible with ls.

	- https://github.com/Peltoche/lsd

### cp

- Copy a file.

### mv

-  Rename (“move”) a file.

### rm

-  Delete (“remove”) a file.

### rmdir

- utility for deleting empty directories

### ln

- Create links (alternative names) to a file.

### shred

- Completely erase a file when the file is deleted

  The operating system does not completely erase a file when the file is deleted.the file could be recovered by third party forensic tools. But we can use the SHRED command to overwrite a file to make it almost impossible for it to be recovered. The file is overwritten three times, by default,which can be changed by the -n option

### rename

- rename files or multiple fiies

## Directory Operations

### cd

- Change your current directory.

### zoxide

- zoxide is a smarter cd command

	- https://github.com/ajeetdsouza/zoxide

### broot

- A new way to see and navigate directory trees

	- https://github.com/Canop/broot

### tree

- a tiny, cross-platform command-line program used to recursively list or display the content of a directory in a tree-like format

### pwd

- Print the name of your current directory, i.e., “where you are now” in the        filesystem.

### basename

- Print the final part of a file path.

### dirname

- Print a file path without its final part.

### mkdir

-  Create (make) a directory.

### rmdir

-  Delete (remove) an empty directory.

### rm -r

- Delete a nonempty directory and its contents.

## File Viewing

### cat

- print the content of a file onto the standard output stream

### tac

- print the content of a file  in reverse onto the standard output stream

### bat

- A cat clone with syntax highlighting and Git integration.

	- https://github.com/sharkdp/bat

### glow

- Glow is a terminal based markdown reader designed from the ground up to bring out the beauty—and power—of the CLI

	- https://github.com/charmbracelet/glow

### more

- View text files one page at a time.

### less

- View text files one page at a time.

### head

-  View the first lines of a text file.

### tail

-  View the last lines of a text file.

### nl

- View text files with their lines numbered.

### strings

- Display text that’s embedded in a binary file.

### od

- View data in octal (or other formats).

### xxd

- View data in hexadecimal.

### acroread

- View PDF files.

### gv

- View PostScript or PDF files.

### xdvi

-  View TeX DVI files.

## File Creation and Text Editors

### touch

- used to create, change and modify timestamps of a file

### emacs

- Text editor from Free Software Foundation.

### vim

- Text editor, extension of Unix vi.

### nano

- an easy to use command line text editor for Unix and Linux operating systems.

### soffice 

- Office suite for editing Microsoft Word, Excel, and PowerPoint documents.

### abiword

-  Edit Microsoft Word documents.

### gnumeric 

- Edit Excel spreadsheets.

### tee

-  Copy a file and print it on standard output, simultaneously.

## File Properties

### stat

-  Display attributes of files and directories.

  The stat command displays the status of a file.The information is much more when compared to ls -l. It also includes the absolute path,Number of blocks used by the file,access time, time of modification etc.,,
  

### wc 

- Count bytes, words, lines in a file or STDIN.

### file

- Identify (guess) the type of a file.

### touch

-  Change timestamps of files and directories.

### chmod

-  Change protection mode of files and directories.

### chgrp

- Change group ownership of files and directories.

### chown

-  Change owner of files and directories.

### umask

-  Set a default mode for new files and directories.

### chattr

-  Change extended attributes of files and directories.

### lsattr

-  List extended attributes of files and directories.

## Print Text

### echo

-  Print simple text on standard output.

### printf

-  Print formatted text on standard output.

### yes

-  Print repeated text on standard output.

### seq

-  Print a sequence of numbers on standard output.

### clear

-  Clear the screen or window.

## Search File Location

### fd

- A simple, fast and user-friendly alternative to find.

### locate

- searches the file system for files and directories whose name matches a given pattern

### find

-  searches for files and directories in a directory hierarchy based on a user given expression and can perform user-specified action on each matched file

### which

-  Locate executables in your search path (command).

### fzf

- A general purpose command-line fuzzy finder.

	- https://github.com/junegunn/fzf

### whereis

-  Locate executables, documentation, and source files.

### type

-  Locate executables in your search path (bash built-in).

## Miscellaneous

### help

-  the simplest way to get information regarding a built-in shell command.

### man

- used to display the user manual of any command that we can run on the terminal.

### tldr

- A community effort to simplify man pages with practical examples.

	- https://github.com/tldr-pages/tldr

### cheat

- Create and view interactive cheatsheets on the command-line.

	- https://github.com/cheat/cheat

### r

- used to execute the previous command.

### history

- a very useful command to show you all of the last commands that have been recently used.

### mcfly

- Fly through your shell history. Great Scott!

	- https://github.com/cantino/mcfly

### xargs

- used in a UNIX shell to convert input from standard input into arguments to a command.

## Web Browsing

### firefox

-  Full-featured web browser.

### curl

- cURL, which stands for client URL, is a command line tool that developers use to transfer data to and from a server.

### wget

-  Download web pages and files.

### curlie

- Curlie is a frontend to curl that adds the ease of use of httpie, without compromising on features and performance.

	- https://github.com/rs/curlie

### httpie

- A modern, user-friendly command-line HTTP client for the API era.

	- https://github.com/httpie/httpie

### xh

- A friendly and fast tool for sending HTTP requests. It reimplements as much as possible of HTTPie's excellent design, with a focus on improved performance.

	- https://github.com/ducaale/xh

### lynx

-  Text-only web browser.

## File Text Manipulation

### grep

-  Find lines in a file that match a regular expression.

### ripgrep

- An extremely fast alternative to grep that respects your gitignore

	- https://github.com/BurntSushi/ripgrep

### ack

- ack is a grep-like source code search tool.


### ag

- A code searching tool similar to ack, but faster.

	- https://github.com/ggreer/the_silver_searcher

### sed

- stream editor  used for text substitution , find & replace but it can also perform other text manipulations like insertion, deletion, search etc.

### sd

- An intuitive find & replace CLI (sed alternative).

	- https://github.com/chmln/sd

### jq

- sed for JSON data.

	- https://github.com/stedolan/jq

### awk/gawk

-  AWK command in Unix is used for pattern processing and scanning.

### cut

-  Extract columns from a file.

### choose

- A human-friendly and fast alternative to cut and (sometimes) awk

	- https://github.com/theryangeary/choose

### paste

-  Append columns.

### tr

-  Translate characters into other characters.

### sort

-  Sort lines of text by various criteria.

### uniq

-  Locate identical lines in a file.

## File Compression and Packaging

### tar

-  Package multiple files into a single file.

### gzip

-  Compress files with GNU Zip.

### gunzip

-  Uncompress GNU Zip files.

### bzip2

-  Compress files in BZip format.

### bunzip2

-  Uncompress BZip files.

### bzcat

-  Compress/uncompress BZip files via standard input/output.

### compress

-  Compress files with traditional Unix compression.

### uncompress

-  Uncompress files with traditional Unix compression.

### zcat

-  Compress/uncompress file via standard input/output (gzip or compress).

### zip

-  Compress files in Windows Zip format.

### unzip

-  Uncompress Windows Zip files.

### metamail

-  Extract MIME data to files.

## File Comparison

### diff

-  Line-by-line comparison of two files or directories.

### comm

-  Line-by-line comparison of two sorted files.

### cmp

-  Byte-by-byte comparison of two files.

### md5sum

-  Compute a checksum of the given files (MD5).

## Printing

### lpr

- Print a file.

### lpq

-  View the print queue.

### lprm

-  Remove a print job from the queue.

## Spell Checking

### look

-  Look up the spelling of a word quickly.

### aspell

-  Interactive spelling checker.

### spell

-  Batch spelling checker.

## Disks and Filesystems

### df

-  get a full summary of available and used disk space usage of the file system on the Linux system.

### fdisk

- check the partitions on a disk

### duf

- A better df alternative, used to show disk usage

### du

-  Measure disk usage of files and directories.

### dust

- A more intuitive version of du written in rust.

### mount

-  Make a disk partition accessible.

### umount

-  Unmount a disk partition (make it inaccessible).

### fsck

-  Check a disk partition for errors.

### sync

-  Flush all disk caches to disk.

### sfdisk

- Sfdisk is another utility with a purpose similar to fdisk, but with more features. It can display the size of each partition in MB.

### inxi

- a very useful command line program that can display information about various hardware components present on the system.

### lsblk

- Lists out all the storage blocks, which includes disk partitions and optical drives.

### hwinfo

-  a general purpose hardware information tool and can be used to print out the disk and partition list.

### quota

- Display disk usage and limits

## Backups and Remote Storage

### dump

-  Write a disk partition to a backup medium.

### restore

-  Restore the results of a dump.

### cdrecord

-  Burn a CD, DVD, or Blu-ray disc.

### rsync

-  Mirror a set of files onto another device or host.

### mt

-  Control a tape drive.

## Viewing Processes

### ps

-  List process.

### procs

- A modern replacement for ps written in Rust.

	- https://github.com/dalance/procsic 

### pgrep

- searches for processes currently running on the system, based on a complete or partial process name, or other specified attributes.pic 1

### uptime

-  View the system load.

### w

-  List active processes for all users.

### top

-  Monitor resource-intensive processes interactively.

### htop

-  a cross-platform interactive process viewer

### gtop

- System monitoring dashboard for terminal.

	- https://github.com/aksakalli/gtop

### hyperfine

- A command-line benchmarking tool.

	- https://github.com/sharkdp/hyperfine

### glances

- Glances an Eye on your system. A top/htop alternative for GNU/Linux, BSD, Mac OS and Windows operating systems.

	- https://github.com/nicolargo/glances

### btop

- Resource monitor that shows usage and stats for processor, memory, disks, network and processes.

	- https://github.com/aristocratos/btop

### bottom

- Yet another cross-platform graphical process/system monitor.

	- https://github.com/ClementTsang/bottom

### iotop

- used to display and monitor the disk IO usage details and even gets a table of existing IO utilization by the process.

### powertop

-  used to diagnose issues with power consumption and power management.

### gnome-system-monitor

-  Monitor system load and processes graphically.

### xload

-  Simple, graphical monitor of system load.

### free

-  Display free memory.

### pidof

-  Command, which looks up and prints the PID of a process by its name

### nmon

- displays and records local system information. The command can run either in interactive or recording mode.

## Controlling Processes

### kill

-  Terminate a process (or send it a signal).

### killall

- a utility command used for killing any running process on the system based on a given name.

### nohup

- nohup (No Hang Up) is a command in Linux systems that runs the process even after logging out from the shell/terminal.

### nice

-  Invoke a program at a particular priority.

### renice

-  Change a process’s priority as it runs.

### cpulimit

## Scheduling Jobs

### sleep

-  Wait a set number of seconds, doing nothing.

### watch

-  Run a program at set intervals.

  The watch command can be used to repeat a command at fixed intervals.the default interval is 2 second.the interval can be changed with -n option
  

### at

-  Schedule a job for a single, future time.

### crontab

-  Schedule jobs for many future times.

## Logins, Logouts, and Shutdowns

### shutdown

- Halts or reboots a Linux system

### halt

-  is used to instruct the hardware to stop all the CPU functions. Basically, it reboots or stops the system.

## Users and Their Environment

### logname

-  Print your login name.

### whoami

-  Print your current, effective username.

### id

-  Print the user ID and group membership of a user.

### who

-  List logged-in users, long output.

### users

-  List logged-in users, short output.

### finger

-  Print information about users.

### last

-  Determine when someone last logged in.

### printenv

-  Print your environment.

## User Account Management

### useradd

-  Create an account.

### userdel

-  Delete an account.

### usermod

-  Modify an account.

### passwd

-  Change a password.

### chfn

-  Change a user’s personal information.

### chsh

-  Change a user’s shell.

## Group Management

### groups

-  Print the group membership of a user.

### groupadd

-  Create a group.

### groupdel

-  Delete a group.

### groupmod

-  Modify a group.

## Host Information

### uname

-  Print basic system information.

### hostname

-  Print the system’s hostname.

### dnsdomainname

-  Same as hostname -d.

### domainname

-  Same as hostname -y.

### nisdomainname

-  Same as hostname -y.

### ypdomainname

-  Same as hostname -y.

### ip

-  Set and display network interface information.

### ifconfig

-  Older command to set and display network interface information.

## Host Location

### host

-  Look up hostnames, IP addresses, and DNS info.

### whois

-  Look up the registrants of Internet domains.

### ping

-  Check if a remote host is reachable.

### traceroute

-  View the network path to a remote host.

## Shell Job Control

### jobs

-  List your jobs.

### &

- Run a job in the background.

### ^Z

- Suspend the current (foreground) job.

### suspend

- Suspend a shell.

### fg

- Unsuspend a job: bring it into the foreground.

### bg

- Make a suspended job run in the background.

## Network Connections

uname -a
lspci -nnk | grep -iA2 net
lsusb
lsmod
iwconfig
rfkill list


### ssh

-  Securely log into a remote host, or run commands on it.

### telnet

-  Log into a remote host (insecure!).

### scp

-  Securely copy files to/from a remote host (batch).

### sftp

-  Securely copy files to/from a remote host (interactive).

### ftp

-  Copy files to/from a remote host (interactive, insecure!).

## @xtremepentest

## Linux Listing Commands

uname -a
lspci -nnk | grep -iA2 net
lsusb
lsmod
iwconfig
rfkill list


### lsattr

- List file attributes on a Linux second extended file system

### lsb_release

- prints certain LSB (Linux Standard Base) and Distribution information.

### lsblk

- List block devices

### ls

- 	List information about file(s)

### lsof

- List open files

### lspci

- List all PCI devices


### lsmem

-  shows the memory block size, the device size, and the amount of memory in online and offline state.

## Email

### thunderbird

-  Graphical mail client.

### evolution

-  Graphical mail client.

### mutt

-  Text-based mail client.

### mail

-  Minimal text-based mail client.

### mailq

-  View the outgoing mail queue on your system.

## Usenet News

### slrn

- Usenet newsreader

## Instant Messaging

### gaim

-  Instant messaging and IRC client.

### talk

-  Linux/Unix chat program.

### write

-  Send messages to a terminal.

### mesg

-  Prohibit talk and write.

### tty

-  Print your terminal device name.

## Math and Calculations

### xcalc

-  Display a graphical calculator.

### expr

-  Evaluate simple math on the command line.

### dc

-  Text-based calculator.

### bc

- Arbitrary precision calculator language


## Dates and Times

### xclock

-  Display a graphical clock.

### cal

-  Print a calendar.

### date

-  Print or set the date and time.

### ntpdate

-  Set the system time using a remote timeserver.

## Graphics and Screensavers

### eog

-  Display graphics files.

### geeqie

-  Display graphics files and slideshows.

### ksnapshot

-  Take a screenshot (screen capture).

### gimp

-  Edit graphics files.

### dia

-  Draw structured diagrams.

### gnuplot

-  Create graphs and plots.

### xscreensaver

-  Run a screensaver.

## Audio

### amarok, rhythmbox, xmms

-  Audio file players (MP3, WAV, OGG).

### grip

-  CD player, ripper, and MP3 encoder.

### cdparanoia

-  Rip audio from CDs to WAV files.

### lame

-  Convert from WAV to MP3.

### id3tag

-  Edit ID3 tags.

### audacity

-  Edit audio files.

### k3b

-  CD burner with graphical interface.

## Video

### mplayer

-  Video file playback.

### gxine

-  Simple DVD player.

### kino

-  Video editor.

### HandBrake

-  Video ripper.

## Network

### traceroute

-  View the network path to a remote host.

### ss

- ss (socket statistics) tool is a CLI command used to show network statistics.

### ifconfig

-  Older command to set and display network interface information.

### netstat

- prints network connections, routing tables, interface statistics, masquerade connections, and multicast memberships

### who

-  List logged-in users, long output.

### tcpdump

-  a command-line utility that you can use to capture and inspect network traffic going to and from your system.

### ping

-  Check if a remote host is reachable.

### gping

- Ping, but with a graph.

	- https://github.com/orf/gping

### ifdown

-  disables a network interface, placing it in a state where it cannot transmit or receive data.

### ifup

-  brings the network interface up, allowing it to transmit and receive data.

### ifquery

- displays information about a network interface's configuration.

### nslookup

- Nslookup (stands for “Name Server Lookup”) is a useful command for getting information from the DNS server.

### dig

- allows you to query information about various DNS records, including host addresses, mail exchanges, and name servers.

### dog

- A user-friendly command-line DNS client. dig on steroids

	- https://github.com/ogham/dog

### mtr

- mtr combines the functionality of the traceroute and ping programs in a single network diagnostic tool

  As mtr starts, it investigates the network connection between the host mtr runs on and HOSTNAME. by sending packets with purposely low TTLs. It continues to send packets with low TTL, noting the response time of the intervening routers. This allows mtr to print the response percentage and response times of the internet route to HOSTNAME. A sudden increase in packet loss or response time is often an indication of a bad (or simply overloaded) link. The results are usually reported as round-trip-response times in miliseconds and the percentage of packetloss.
  

## Transfer files between remote and local systems

### scp

- allows you to securely copy files and directories between two locations over SSH.

### rsync

- a fast and versatile command-line utility for synchronizing files and directories between two locations over a remote shell, or from/to a remote Rsync daemon.

### sftp

- a secure file protocol that is used to access, manage, and transfer files over an encrypted SSH transport.

### sshfs

- allows us to mount a remote directory locally

## Modern Alternatives

### This commands might not come pre-installed on your system, so you may need to install them first. You can can find the installation instructions from the link provide

