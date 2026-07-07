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
               ├── chmod Numeric Values
               ├── Top vs htop
               ├── Cron vs Systemd Timer
               ├── TCP vs UDP
               ├── File Descriptors
               ├── Zombie Process
               ├── Daemon Process
               ├── Load Average
               └── Troubleshooting High CPU/Memory/Disk
