I've created a Linux Commands Cheat Sheet covering essential commands. 

## Linux Commands Cheat Sheet

# 1. File Management

ls – List files and directories

cd <directory> – Change directory

pwd – Show current directory

mkdir <dir> – Create a new directory

rmdir <dir> – Remove an empty directory

rm -r <dir> – Remove directory with files

cp <source> <destination> – Copy files and directories

mv <source> <destination> – Move or rename files

rm <file> – Delete a file

find <dir> -name <file> – Search for a file in a directory

# 2. File Permissions

ls -l – View file permissions

chmod 755 <file> – Change file permissions

chown user:group <file> – Change file owner

# 3. File Viewing & Editing

cat <file> – View file content

less <file> – View large files page by page

nano <file> – Edit a file in nano editor

vi <file> – Edit a file in vi editor

head -n <num> <file> – View first n lines

tail -n <num> <file> – View last n lines

# 4. User Management

whoami – Show current user

id – Show user ID and group ID

who – Show logged-in users

useradd <username> – Create a new user

passwd <username> – Change user password

su <user> – Switch to another user

sudo <command> – Run command as superuser

# 5. Networking

ping <host> – Test network connection

curl <url> – Fetch content from URL

wget <url> – Download a file from URL

ifconfig – Show network interfaces

netstat -tulnp – Show active ports

ssh user@host – Connect to a remote server via SSH

# 6. Process Management

ps aux – Show running processes

top – Show real-time system usage

htop – Interactive process viewer

kill <PID> – Terminate a process by ID

killall <process> – Terminate all processes by name

jobs – Show background jobs

bg <job> – Resume a background job

fg <job> – Bring job to foreground

# 7. System Monitoring

df -h – Show disk space usage

du -sh <dir> – Show directory size

free -m – Show memory usage

uptime – Show system uptime

history – Show command history

# 8. Package Management

Ubuntu/Debian:

sudo apt update – Update package list

sudo apt upgrade – Upgrade all packages

sudo apt install <package> – Install a package

sudo apt remove <package> – Remove a package

CentOS/RHEL:

sudo yum update – Update package list

sudo yum install <package> – Install a package

sudo yum remove <package> – Remove a package

# 9. Log Management

cat /var/log/syslog – View system logs (Ubuntu)

cat /var/log/messages – View system logs (CentOS)

journalctl -xe – View systemd logs

# 10. Archiving & Compression

tar -cvf archive.tar <files> – Create a tar archive

tar -xvf archive.tar – Extract a tar archive

gzip <file> – Compress a file

gunzip <file.gz> – Decompress a file

zip archive.zip <files> – Create a zip archive

unzip archive.zip – Extract a zip archive

# 11. Disk Management

fdisk -l – Show disk partitions

mount /dev/sdX /mnt – Mount a disk

umount /mnt – Unmount a disk

mkfs.ext4 /dev/sdX – Format a disk

# 12. System Control

shutdown -h now – Shutdown the system

reboot – Restart the system

systemctl status <service> – Check service status

systemctl start <service> – Start a service

systemctl stop <service> – Stop a service

systemctl restart <service> – Restart a service

This cheat sheet covers essential Linux commands. 
