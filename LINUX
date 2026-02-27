                           LINUX
                              |
  ----------------------------------------------------------------
  |            |            |            |           |            |
Basics     File System   Users &     Process     Networking    Storage
                        Permissions  Management


1️⃣ Linux Basics

What is Linux?

Kernel vs Shell

Distributions:

Ubuntu

CentOS

Red Hat Enterprise Linux

CLI vs GUI

Important directories: /etc, /var, /home, /bin, /usr

2️⃣ File System & Commands
File Handling

ls, pwd, cd

cp, mv, rm

mkdir, touch

File Viewing

cat

less

head

tail

Search & Filter

find

grep

locate

3️⃣ Users & Permissions
User Management

useradd

passwd

usermod

groupadd

Permissions

r (read)

w (write)

x (execute)

Permission Commands

chmod

chown

chgrp

Concept:

Owner | Group | Others
4️⃣ Process Management

ps

top

htop

kill

kill -9

bg

fg

jobs

Concept:

Foreground

Background

Daemon process

5️⃣ Package Management

Debian based:

apt update

apt install

RHEL based:

yum install

dnf install

6️⃣ Networking

ifconfig

ip a

ping

netstat

ss

curl

wget

Concept:

IP address

Port

DNS

SSH

7️⃣ Disk & Storage

df -h

du -sh

lsblk

mount

umount

Concept:

Partition

File system (ext4, xfs)

Swap memory

8️⃣ Logs & Monitoring

Important Logs:

/var/log/syslog

/var/log/messages

Commands:

journalctl

tail -f

9️⃣ Shell Scripting

Variables

if condition

loops (for, while)

functions

cron jobs

🔟 DevOps-Oriented Linux

SSH configuration

Systemctl (service management)

Log rotation

Firewall (firewalld / iptables)

Environment variables

File permissions for deployment

Disk full troubleshooting

CPU high issue analysis


Interview Quick Visual Summary

Linux
 ├── File System
 ├── Users & Permissions
 ├── Process Mgmt
 ├── Networking
 ├── Storage
 ├── Package Mgmt
 ├── Logs
 └── Shell Scripting




                                                    OR




1️⃣ Linux Basics

What is Linux?

Kernel vs OS

Distributions:

Ubuntu

CentOS

Red Hat Enterprise Linux

2️⃣ File System Structure (Very Important 🔥)

/
├── /bin
├── /etc
├── /home
├── /var
├── /usr
├── /tmp
├── /opt

Important Directories

/etc → configuration files

/var/log → logs (Kubernetes logs troubleshooting ki use)

/home → users

/root → root user

/proc → running process info

3️⃣ File & Directory Commands

| Command  | Use                         |
| -------- | --------------------------- |
| `pwd`    | Current location            |
| `ls -la` | List files with permissions |
| `cd`     | Change directory            |
| `mkdir`  | Create folder               |
| `rm -rf` | Delete forcefully           |
| `cp`     | Copy                        |
| `mv`     | Move/Rename                 |
| `touch`  | Create file                 |
| `cat`    | View file                   |


4️⃣ File Permissions (Interview Favorite 💥)

-rwxr-xr--
r → read (4)

w → write (2)

x → execute (1)

Change permission

chmod 755 file.sh

Change owner
chown user:group file.txt
👉 Kubernetes pods lo volume permission issue vastey idi use avuthundi.
5️⃣ User Management

useradd devuser
passwd devuser
usermod -aG sudo devuser

DevOps lo servers create chesinappudu required.

6️⃣ Process Management (K8s Debugging Ki 🔥)

| Command                  | Use            |
| ------------------------ | -------------- |
| `ps -ef`                 | List processes |
| `top`                    | Live usage     |
| `htop`                   | Advanced top   |
| `kill -9 PID`            | Force stop     |
| `systemctl status nginx` | Service check  |


Pod crash issue troubleshoot ki use.
7️⃣ Disk & Memory
df -h      # disk usage
du -sh *   # folder size
free -m    # memory

👉 Kubernetes node disk full ayite pods run avvu.

8️⃣ Networking Commands (Very Important for K8s)

| Command          | Use          |
| ---------------- | ------------ |
| `ip a`           | Check IP     |
| `ping`           | Connectivity |
| `netstat -tulnp` | Open ports   |
| `ss -tulnp`      | Ports        |
| `curl`           | API test     |
| `wget`           | Download     |

Kubernetes service communication test cheyadaniki.

9️⃣ Package Management

Ubuntu:
apt update
apt install nginx

CentOS:

yum install httpd

🔟 Shell Scripting Basics
#!/bin/bash
echo "Hello DevOps"

Automation ki must.

Kubernetes Ki Linux Connection

| Linux Concept   | Kubernetes Lo Use |
| --------------- | ----------------- |
| Process         | Container         |
| VM              | Node              |
| Service         | Pod               |
| File system     | Volume            |
| Logs (/var/log) | Pod logs          |
| Port            | Service Port      |




                                                     OR





1️⃣ Introduction to Linux

Open-source Operating System

Kernel-based architecture

Multi-user & Multi-tasking

CLI-focused environment

Popular Distributions:

Ubuntu

CentOS

Red Hat Enterprise Linux

Debian

2️⃣ Linux Architecture
Hardware
   ↓
Kernel
   ↓
Shell
   ↓
User Commands
Kernel Responsibilities:

Process management

Memory management

Device drivers

File system handling

3️⃣ File System Structure

Root Directory: /

Important Directories:

/bin → essential binaries

/boot → boot loader files

/etc → configuration files

/home → user directories

/root → root user home

/var → logs & variable data

/usr → user programs

/tmp → temporary files

/proc → process information

4️⃣ File & Directory Management
Basic Commands:

pwd → Print working directory

ls → List files

cd → Change directory

mkdir → Create directory

rmdir → Remove empty directory

rm -rf → Remove forcefully

cp → Copy files

mv → Move/Rename files

touch → Create file

cat, less, more → View files

5️⃣ File Permissions & Ownership

Permission format:

-rwxr-xr--

r = Read (4)

w = Write (2)

x = Execute (1)

Commands:

chmod → Change permission

chown → Change owner

chgrp → Change group

6️⃣ User & Group Management

useradd

passwd

usermod

userdel

groupadd

groups

Concepts:

Root user

Sudo access

/etc/passwd file

/etc/shadow file

7️⃣ Process Management

Commands:

ps -ef

top

htop

kill

kill -9

nice

renice

bg, fg

jobs

Concepts:

PID

Foreground vs Background process

Zombie process

Daemon process

8️⃣ Memory & Disk Management

Commands:

free -m

df -h

du -sh

mount

umount

lsblk

fdisk

Concepts:

Swap memory

Disk partitions

Inodes

9️⃣ Networking in Linux

Commands:

ip a

ifconfig

ping

netstat

ss

curl

wget

scp

ssh

Concepts:

Ports

DNS

Firewall

Routing table

🔟 Package Management

Debian-based:

apt update

apt install

apt remove

RHEL-based:

yum install

dnf install

rpm

1️⃣1️⃣ Shell & Bash Scripting

Variables

Condition statements (if, else)

Loops (for, while)

Functions

Shebang (#!/bin/bash)

Input/Output redirection (>, >>, <)

Pipes (|)

1️⃣2️⃣ System Services

Commands:

systemctl start

systemctl stop

systemctl restart

systemctl status

service

Concepts:

systemd

Daemons

Boot targets

1️⃣3️⃣ Log Management

Important Log Locations:

/var/log/syslog

/var/log/messages

/var/log/auth.log

Commands:

tail -f

journalctl

1️⃣4️⃣ Environment Variables

echo $PATH

export

.bashrc

.profile

1️⃣5️⃣ Security Concepts

SSH key authentication

Firewall (ufw, firewalld)

SELinux

File permissions

Sudoers file

1️⃣6️⃣ Important DevOps Concepts in Linux

Cron jobs (crontab -e)

Log rotation

Process monitoring

Disk cleanup

Service troubleshooting

Port troubleshooting

Server hardening basics








