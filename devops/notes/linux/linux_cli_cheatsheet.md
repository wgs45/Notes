# ✨ DevOps Linux Command Cheatsheet 🌟

Welcome, dear learner, to this charming and beautifully crafted guide to mastering Linux commands for DevOps! 💻💖 Grab your favorite tea, sit back, and enjoy the journey of exploration and discovery! ✨

---

## 🔹 Basic Linux Commands 🛠️

These are the foundational tools that every DevOps wizard must master. Think of them as your trusty spells—use them wisely! 🌟

- **`cd`**: ✨ Change directory
- **`ls`**: 🔍 List files in a directory
- **`pwd`**: 📜 Print working directory
- **`cp`**: ✂️ Copy files or directories
- **`mv`**: 🏃 Move or rename files
- **`rm`**: 🗑️ Remove files or directories
- **`touch`**: 📝 Create a new file
- **`mkdir`**: 🌱 Create a new directory
- **`rmdir`**: ❌ Remove an empty directory
- **`find`**: 🔎 Search for files in a directory hierarchy
- **`cat`**: 📖 Concatenate and display file contents
- **`echo`**: 💬 Print text or variables to the terminal

---

## 🔸 File and Directory Management 📁

Managing files is like nurturing your files and directories to grow into powerful assets. 🌱✨ Here’s how you can organize your treasures:

- **`cp file1 file2`**: ✨ Copy file1 to file2
- **`mv oldname newname`**: 💫 Rename a file
- **`rm -rf dir`**: 🚨 Remove a directory and all its contents (use with care!)
- **`tar -czvf archive.tar.gz folder/`**: 📦 Create a tarball archive
- **`tar -xzvf archive.tar.gz`**: 📬 Extract a tarball archive
- **`chmod 755 file`**: 🔒 Change file permissions
- **`chown user:group file`**: 🔑 Change file owner and group
- **`ln -s /path/to/file link_name`**: 🌐 Create a symbolic link
- **`du -sh`**: 📊 Display disk usage for the current directory
- **`df -h`**: 💾 Show disk space usage

---

## 🔹 User and Group Management 🧑‍💻👥

In the world of DevOps, managing users and groups is vital for maintaining order and security. 🌸

- **`useradd username`**: 🌱 Add a new user
- **`usermod -aG group username`**: 👥 Add a user to a group
- **`passwd username`**: 🔐 Change a user’s password
- **`groupadd groupname`**: 🌈 Add a new group
- **`groups username`**: 🧑‍🤝‍🧑 Show the groups a user belongs to
- **`id username`**: 🆔 Show user and group ID information

---

## 🔸 Process Management ⚙️

Managing processes is like commanding the flow of magic within your system. 🌙 Let’s keep things smooth and organized!

- **`ps`**: 🧑‍💻 List current processes
- **`top`**: ⏰ Show real-time system resource usage
- **`htop`**: 🖥️ Interactive process viewer (if installed)
- **`kill PID`**: 💥 Kill a process by its process ID
- **`killall process_name`**: ⚡ Kill all processes with the specified name
- **`nice`**: 🌟 Set process priority
- **`nohup command &`**: 🌙 Run command in the background

---

## 🔹 Networking 🌐

Ah, networking—the art of communication between systems! 🕸️✨ Here are some must-know commands for DevOps networking:

- **`ifconfig`**: 🌍 Show network interfaces
- **`ip addr`**: 📡 Show network interfaces (alternative to ifconfig)
- **`ping`**: 🧩 Send ICMP packets to test network connectivity
- **`curl http://example.com`**: 🌐 Fetch a web page or test API endpoints
- **`netstat`**: 🔌 Show network connections
- **`ss`**: 🖧 Show socket statistics (alternative to netstat)
- **`ssh user@hostname`**: 🔑 Connect to a remote machine using SSH
- **`scp file user@hostname:/path/to/destination`**: 📤 Securely copy files between systems
- **`wget http://example.com`**: 🌍 Download a file from a URL

---

## 🔸 System Information 🧠

Knowledge is power! Let’s dig into the magic that powers the system. 🔮✨

- **`uname -a`**: 🧳 Display system information
- **`uptime`**: ⏳ Show system uptime
- **`dmesg`**: 📜 Show kernel and system log messages
- **`free -h`**: 💭 Display memory usage
- **`top`**: 🧠 Display real-time system usage (CPU, memory, etc.)
- **`htop`**: 🖥️ Interactive process viewer (if installed)
- **`lscpu`**: 🧑‍💻 Show detailed CPU architecture information
- **`lsblk`**: 💾 List block devices
- **`lspci`**: 🖧 List PCI devices
- **`lsusb`**: 🔌 List USB devices

---

## 🔹 Permissions 🛡️

Security is the key to a well-guarded system. Here are your trusty commands for controlling access! 🔒✨

- **`chmod 755 file`**: 🔒 Change permissions for file (rwx for owner, rx for others)
- **`chmod -R 755 directory/`**: 🔐 Recursively change permissions for a directory
- **`chown user:group file`**: 🗝️ Change owner and group of a file
- **`chgrp group file`**: 💼 Change group ownership of a file
- **`umask`**: 💡 Show the default file permission mask

---

## 🔸 Disk Management 💾

Your system’s hard drive is like a treasure chest—let’s keep it in top shape! ✨

- **`fdisk -l`**: 🔍 List all disks and partitions
- **`mount`**: 🧩 Mount a filesystem
- **`umount /mnt/drive`**: 🚪 Unmount a filesystem
- **`fsck /dev/sda1`**: 🔧 Check and repair filesystem
- **`mkfs.ext4 /dev/sda1`**: 🛠️ Format a partition with ext4 filesystem
- **`resize2fs`**: 🔄 Resize an ext2/ext3/ext4 filesystem

---

## 🔹 Package Management 📦

The art of managing packages is like weaving a spell of functionality into your system. 🌟✨

### 🟢 Debian/Ubuntu (apt)

- **`sudo apt update`**: 🌀 Update package list
- **`sudo apt upgrade`**: 🔄 Upgrade installed packages
- **`sudo apt install package_name`**: 📥 Install a package
- **`sudo apt remove package_name`**: ❌ Remove a package

### 🟢 CentOS/RHEL (yum)

- **`sudo yum update`**: ⚡ Update packages
- **`sudo yum install package_name`**: 📥 Install a package
- **`sudo yum remove package_name`**: ❌ Remove a package

### 🟢 Fedora (dnf)

- **`sudo dnf update`**: 🔄 Update packages
- **`sudo dnf install package_name`**: 📥 Install a package
- **`sudo dnf remove package_name`**: ❌ Remove a package

---

## 🔸 Bash Scripting Basics 📝

Ah, Bash scripting! Your very own magical spellbook! 📜✨ Let’s dive into the basics of this powerful language:

- **`#!/bin/bash`**: 🧑‍💻 Shebang for Bash scripts
- **`echo "Hello, World!"`**: 💬 Print a message to the screen
- **`variable="value"`**: ✨ Declare a variable
- **`if [ $var -eq 10 ]; then echo "Equal"; fi`**: 💭 Simple if statement
- **`for i in {1..5}; do echo $i; done`**: 🔁 For loop example
- **`while [ condition ]; do ... done`**: 🔄 While loop example
- **`read -p "Enter your name: " name`**: 📖 Read user input
- **`echo "Your name is $name"`**: 💬 Print the value of a variable
- **`$(command)`**: 🪄 Command substitution
- **`if [ -f "file.txt" ]; then echo "File exists"; fi`**: ✅ Check if a file exists

---

## 🔹 Advanced Linux Commands 🌌

Time for the magic to get a little more advanced, like a wizard learning new spells! ✨🧙‍♀️

- **`strace command`**: 🕵️‍♀️ Trace system calls for a command
- **`lsof`**: 🗂️ List open files and processes using them
- **`ps aux --sort=-%mem`**: ⚡ Sort processes by memory usage
- **`cron`**: ⏰ Schedule tasks with cron jobs
- **`at`**: 🌙 Run tasks at a specific time
- **`iptables`**: 🔥 Configure the firewall
- **`docker ps`**: 🐳 List running Docker containers
- **`docker exec -it container_name bash`**: 💼 Access a running container
- **`systemctl status service_name`**: ⚙️ Check the status of a service
- **`journalctl -u service_name`**: 📜 View logs for a service
- **`rsync -av source/ destination/`**: 🧳 Synchronize files between systems

---

## 🧠 TL;DR Recap 💫

Mastering Linux commands is like learning a set of powerful spells. With the right tools at your fingertips, you can conquer the DevOps world! 🌟 Remember to use these commands wisely, practice regularly, and never stop exploring. ✨

---

_May your commands be swift and your systems ever reliable, dear learner!_ 🌸💫
