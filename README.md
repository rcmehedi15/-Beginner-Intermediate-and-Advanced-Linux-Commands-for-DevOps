# Linux Commands for DevOps  

This repository provides a curated list of Linux commands essential for DevOps, ranging from basic to advanced. The commands are categorized to help both beginners and experienced professionals.  

## 📂 Table of Contents  
- [Beginner Commands](#beginner-commands)  
- [Intermediate Commands](#intermediate-commands)  
- [Advanced Commands](#advanced-commands)  

---

## Beginner Commands  

### File and Directory Management  
- `ls` - List files and directories.  
- `cd` - Change the current directory.  
- `pwd` - Display the current directory path.  
- `mkdir` - Create a directory.  
- `rm` - Remove files or directories.  
- `cp` - Copy files or directories.  
- `mv` - Move or rename files.  
- `touch` - Create an empty file.  
- `cat` - Concatenate and display file contents.  
- `less` - View file contents one screen at a time.  
- `head` - Display the first lines of a file.  
- `tail` - Display the last lines of a file.  
- `tree` - View directories and subdirectories in a tree format.  

### File Permissions and Ownership  
- `chmod` - Modify file permissions.  
- `chown` - Change ownership of files or directories.  
- `ls -l` - View detailed file permissions.  
- `umask` - Set default file permissions.  

### Process and System Monitoring  
- `ps` - List running processes.  
- `top` or `htop` - Monitor real-time system performance.  
- `kill` - Terminate a process by PID.  
- `uptime` - Show system uptime and load average.  
- `df -h` - Display available disk space.  
- `du -sh` - Show directory size.  
- `free -m` - Display memory usage.  

### Networking  
- `ping` - Check network connectivity.  
- `curl` / `wget` - Download files or test API endpoints.  
- `ifconfig` / `ip a` - Display or configure network interfaces.  
- `netstat -an` - Display active network connections.  
- `scp` - Securely copy files between systems.  
- `ssh` - Connect to a remote server.  

### User Management  
- `whoami` - Display the current user.  
- `id` - Show user and group IDs.  
- `passwd` - Change the user password.  
- `who` / `w` - Show logged-in users.  
- `groups` - Display groups a user belongs to.  

---

## Intermediate Commands  

### Disk and File System Management  
- `lsblk` - Display block devices.  
- `fdisk` - Partition a disk.  
- `mount` / `umount` - Mount or unmount file systems.  
- `mkfs` - Create a new file system.  
- `fsck` - Check and repair file systems.  
- `blkid` - Show information about block devices.  
- `resize2fs` - Resize ext2/ext3/ext4 file systems.  
- `xfs_growfs` - Expand an XFS file system.  
- `lsof` - List open files.  

### Text Processing  
- `grep` - Search text using patterns.  
- `awk` - Process and analyze text data.  
- `sed` - Perform text manipulation.  
- `cut` - Remove sections of lines.  
- `sort` - Sort text data.  
- `uniq` - Remove duplicate lines.  
- `wc` - Count words, lines, and characters.  

### Process and Job Management  
- `bg` / `fg` - Move jobs to the background or foreground.  
- `jobs` - List active jobs.  
- `nohup` - Run a command immune to hangups.  
- `nice` / `renice` - Adjust process priority.  
- `systemctl` - Control system services.  
- `journalctl` - View system logs.  

### Networking  
- `traceroute` - Trace the path of network packets.  
- `tcpdump` - Capture network traffic.  
- `netcat` (nc) - Test and debug network connections.  
- `dig` / `nslookup` - Query DNS information.  
- `rsync` - Synchronize files between systems.  

### Scripting and Automation  
- `cron` / `crontab` - Schedule recurring tasks.  
- `at` - Schedule one-time tasks.  
- `bash` - Automate workflows with shell scripts.  

---

## Advanced Commands  

### System Optimization and Performance Tuning  
- `sysctl` - Modify kernel parameters.  
- `ethtool` - Configure network interfaces.  
- `perf` - Analyze performance bottlenecks.  
- `iostat` - Monitor CPU and disk I/O.  
- `vmstat` - Display system performance metrics.  

### Advanced Networking  
- `ip rule` - Configure advanced routing rules.  
- `iptables` / `nftables` - Configure firewalls.  
- `tc` - Control network bandwidth and latency.  
- `arp` - Manage the ARP cache.  
- `bridge` - Configure Ethernet bridges.  

### Process Debugging and Analysis  
- `gdb` - Debug programs.  
- `strace` - Trace system calls made by a process.  
- `pstack` - Print stack trace of a process.  
- `coredumpctl` - Retrieve core dumps for analysis.  

### Containers and Orchestration  
- `docker` - Manage containerized applications.  
- `docker-compose` - Run multi-container Docker setups.  
- `kubectl` - Manage Kubernetes clusters.  
- `helm` - Kubernetes package manager.  

### Monitoring and Logging  
- `prometheus` - Collect and query metrics.  
- `grafana` - Visualize metrics and logs.  
- `logrotate` - Manage log rotation.  
- `sar` - Collect and report system activity.  

---
Thank you.
