# 🐧 Linux Mind Map (DevOps Interview & Learning)

```text
                                 🐧 LINUX
                                    │
 ┌──────────────────────────────────┼──────────────────────────────────┐
 │                                  │                                  │
 Basics                         File System                     Users & Permissions
 │                              │                               │
 ├── What is Linux              ├── / (Root)                    ├── useradd
 ├── Kernel                     ├── /home                       ├── passwd
 ├── Shell                      ├── /etc                        ├── groupadd
 ├── Terminal                   ├── /var                        ├── chmod
 ├── Distribution               ├── /opt                        ├── chown
 │                              ├── /tmp                        ├── chgrp
 ├── Ubuntu                     ├── /usr                        ├── sudo
 ├── CentOS                     ├── /bin                        ├── su
 ├── RHEL                       ├── /sbin                       └── umask
 └── Amazon Linux               └── /boot

                                    │
 ┌──────────────────────────────────┼──────────────────────────────────┐
 │                                  │                                  │
 File Commands                 Text Processing                  Package Management
 │                              │                               │
 ├── pwd                        ├── cat                         Ubuntu
 ├── ls                         ├── more                        ├── apt update
 ├── cd                         ├── less                        ├── apt install
 ├── mkdir                      ├── head                        ├── apt remove
 ├── rmdir                      ├── tail                        └── apt upgrade
 ├── touch                      ├── grep
 ├── cp                         ├── awk                         RHEL/CentOS
 ├── mv                         ├── sed                         ├── yum
 ├── rm                         ├── cut                         ├── dnf
 ├── find                       ├── sort                        └── rpm
 ├── locate                     ├── uniq
 └── tree                       └── wc

                                    │
 ┌──────────────────────────────────┼──────────────────────────────────┐
 │                                  │                                  │
 Process Management            Disk Management                  Networking
 │                              │                               │
 ├── ps                         ├── df -h                       ├── ip addr
 ├── top                        ├── du -sh                      ├── ifconfig
 ├── htop                       ├── lsblk                       ├── ping
 ├── kill                       ├── fdisk                       ├── traceroute
 ├── killall                    ├── mkfs                        ├── netstat
 ├── nice                       ├── mount                       ├── ss
 ├── renice                     ├── umount                      ├── curl
 └── jobs                       └── blkid                       ├── wget
                                                                ├── nslookup
                                                                └── dig

                                    │
 ┌──────────────────────────────────┼──────────────────────────────────┐
 │                                  │                                  │
 Services                      Logs                           Scheduling
 │                              │                              │
 ├── systemctl                  ├── journalctl                 ├── crontab -e
 ├── service                    ├── /var/log                   ├── at
 ├── enable                     ├── messages                   ├── systemd timers
 ├── start                      ├── syslog                     └── cron jobs
 ├── stop                       ├── auth.log
 ├── restart                    └── dmesg
 └── status

                                    │
 ┌──────────────────────────────────┼──────────────────────────────────┐
 │                                  │                                  │
 Archive & Compression         SSH & Security                Shell Scripting
 │                              │                              │
 ├── tar                        ├── ssh                        ├── Variables
 ├── gzip                       ├── scp                        ├── Conditions
 ├── gunzip                     ├── sftp                       ├── Loops
 ├── zip                        ├── ssh-keygen                 ├── Functions
 ├── unzip                      ├── authorized_keys            ├── Arguments
 └── xz                         ├── firewall                   └── Exit Codes
                                └── fail2ban

                                    │
 ┌──────────────────────────────────┼──────────────────────────────────┐
 │                                  │                                  │
 Environment Variables         File Permissions               DevOps Linux
 │                              │                              │
 ├── PATH                       ├── rwx                        ├── Git
 ├── export                     ├── 755                        ├── Docker
 ├── env                        ├── 644                        ├── Kubernetes
 ├── printenv                   ├── SUID                       ├── Jenkins
 └── ~/.bashrc                  ├── SGID                       ├── Ansible
                                └── Sticky Bit                 ├── Terraform
                                                              └── AWS CLI

                                    │
                           ⭐ Interview Topics
                                    │
               ├── Linux Boot Process
               ├── Runlevels / Targets
               ├── LVM
               ├── Swap Memory
               ├── Inodes
               ├── Soft Link vs Hard Link
               ├── grep vs awk vs sed
               ├── chmod (755, 644, etc.)
               ├── Top vs htop
               ├── Cron vs Systemd Timer
               ├── TCP vs UDP
               ├── File Descriptors
               ├── Zombie Process
               ├── Daemon Process
               ├── Load Average
               └── High CPU / Memory / Disk Troubleshooting
```

## 📚 Learning Order

1. Linux Basics
2. File System
3. File & Directory Commands
4. Text Processing
5. Users & Permissions
6. Package Management
7. Process Management
8. Disk Management
9. Networking
10. Services (`systemd`)
11. Logs
12. Scheduling (Cron)
13. SSH & Security
14. Shell Scripting
15. Environment Variables
16. DevOps Tools on Linux

---

## 🧠 Memory Trick

Remember this sequence:

**B → F → C → U → P → D → N → S → L → C → SSH → Shell → DevOps**

- **B** = Basics
- **F** = File System
- **C** = Commands
- **U** = Users & Permissions
- **P** = Processes
- **D** = Disk
- **N** = Networking
- **S** = Services
- **L** = Logs
- **C** = Cron
- **SSH** = Remote Access & Security
- **Shell** = Shell Scripting
- **DevOps** = Git, Docker, Kubernetes, Jenkins, Terraform, Ansible, AWS CLI

---

## 🎯 Most Important Interview Topics

- Linux Boot Process
- File System Hierarchy (FHS)
- File Permissions (`chmod`, `chown`, `umask`)
- Soft Link vs Hard Link
- Inodes
- Process Lifecycle
- Zombie vs Orphan Process
- Daemon Process
- grep vs sed vs awk
- `find` vs `locate`
- `cp` vs `mv`
- `top` vs `htop`
- `ps` command
- `kill` vs `kill -9`
- `systemctl`
- `journalctl`
- Cron Jobs
- SSH Key Authentication
- Disk Usage (`df`, `du`, `lsblk`)
- LVM
- Swap Memory
- Networking Commands
- TCP vs UDP
- DNS Troubleshooting
- Bash Scripting Basics
- Linux Troubleshooting Scenarios
