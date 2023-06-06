# Linux Course

Following are the syllabus to learn Linux:

## Introduction and Lab Setup

- Course Introduction
- Lab Setup

## Operating System Overview

- Operating System(OS) Introduction
- Operating System functions
- Different kind of OS
  - Linux
  - macOS
  - Windows

## Introduction to Linux

- Why Linux and its features?
- Linux Distributions
- Linux Filesystem Hierarchy
- Bash and Sh shells

## Linux Installation and Upgrade

- Different installation methods
  - Using USB Stick
  - Using CD ROM
  - Using Virtual MAchine
  - Installing over the network
- Demo of Linux Installation using VirtualBox
- Upgrading Linux

## Text Editors and Tmux

- Vim Editor
  - Vim introduction
  - Vim basic commands
  - Vim advanced commands
- Tmux
  - Tmux introduction
  - Working with Tmux commands

## Linux Basic Commands

- Linux Files and Directory commands
  - `ls` command
  - `cd` command
  - `pwd` command
  - `mkdir` command
  - File creation `touch` command
  - `rm` command
  - `cp` command
  - Rename/move command
- Content related commands
  - `cat` command
  - `head` command
  - `tail` command
  - `more` command
  - `less` command

## Linux Advanced Commands
  - Hard link and soft link commands: `ln`
  - Compress and archive commands: `tar` and `zip`
  - Compare two files: `diff`
  - Executing file in current shell: `source` command
  - Find file in the system: `find` command
- Working with Environment Variables
  - What is Environment Variable?
  - Different commands to manage environment variables:
    - `printenv` command
    - `set` and `unset` command
    - Working with `$PATH` variables
- Text Manipulation Commands
  - `grep` command
  - `awk` command
  - `sed` command
- Automation using `cron` utility command
- Other useful commands
  - `history` command
  - `which` command
  - `whereis` command
  - `wget` command
  - `curl` command
  - `uname` command
  - `dmesg` command
  - `exit` command

## Understanding Linux System startup

- Understanding Boot Loader
- Understanding 4 stages of Linux Boot Process

## Package Management in Linux

- What is package and package manager?
- High and low-level package tools
- Managing packages in Ubuntu
  - `dpkg` package manager
  - `apt` package manager

## Users and Groups Management

- What is Linux user and group?
- User management
  - Type of users
  - Creating a user
    - User account creation
    - Exploring /etc/passwd file
    - Exploring /etc/shadow file
  - Updating account updation
  - Deleting user account
- Group management
  - Type of Group in Linux
    - Primary Group
    - Secondary Group
  - Creating a group
  - Setting group password
  - Explore /etc/group file
  - Explore /etc/gshadow file
  - Adding user to the group
  - Adding a User to multiple Groups
  - Removing user from the group
  - Removing the group
- Sudo and su command

## File Ownership and Permission

- Introduction of file ownership and permission
- File ownership
  - Using `chown` command
- File permission
  - Three categories of permissions
  - Using `chmod` command

## Linux Filesystem and its types

- What is a Linux filesystem?
- Linux filesystem features
- Why do we need the Linux filesystem?
- Different filesystem types
- Mounting and Unmounting filesystems
- Disk Partitioning and filesystem creation from a loopback device
- Useful filesystem commands

## Linux Processes

- Introduction to Process
  - Listing processes
  - Process State
- Type of Processes
- Creating a process
- Terminating a process
- Process Monitoring
  - `top` and `htop` commands
  - Process priority and Nice value

## Managing Services in Linux

- What is service and service manager?
- Managing services using `systemctl` command
- Creating custom systemd service
- Service logs with `journalctl` command

## Networking Overview and different commands

- Introduction to Linux Networking
- Overview of OSI Model
- Overview of TCP/IP Model
- Important concepts of Networking
  - `hostname`
  - `ip a`
- IP Address
  - Working of IP Address
  - Types of IP Address
    - IPv4 Address
    - IPv6 Address
  - Classification of IP Address
  - Ping command
  - Classful and Classless Addressing
  - Understand the concept of Subnetting
- Important protocols
  - HTTP and HTTPS
  - TCP and UDP
  - FTP
  - SMTP, POP and IMAP
  - DHCP
- Switch and Router
- Computer Network Architecture
- Type of Area Networks: LAN and WAN
- Routing in Linux
  - Introduction to Routing
  - Types of Routing
  - Traceroute Command
  - `ip route` and `route` commands
- Private Network and VPN
- Domain Name System
  - Introduction to DNS
  - `dig` command
  - `nslookup` command
  - Configuring Nameservers using `resolv.conf` file
- SSH Service
- Capturing network traffic through `tcpdump` command

## System Security

- Introduction to System Security
- AppArmor
  - Introduction
  - How AppArmor works?
  - AppArmor and SELinux
- Umask
- Linux Firewall
