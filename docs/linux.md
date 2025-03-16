# linux

List files and directories
```bash
ls
```

Show detailed list
```bash
ls -l
```

Show hidden files
```bash
ls -a
```

Change directory
```bash
cd <directory_name>
```

Go to home directory
```bash
cd ~
```

Go up one directory
```bash
cd ..
```

Print working directory
```bash
pwd
```

Create a directory
```bash
mkdir <directory_name>
```

Remove a directory
```bash
rmdir <directory_name>
```

Remove directory and its contents
```bash
rm -r <directory_name>
```

Create a file
```bash
touch <file_name>
```

Copy a file or directory
```bash
cp <source> <destination>
```

Copy recursively (for directories)
```bash
cp -r <source> <destination>
```

Move or rename a file or directory
```bash
mv <source> <destination>
```

Remove a file
```bash
rm <file_name>
```

Remove recursively (for directories)
```bash
rm -r <directory_name>
```

View file content
```bash
cat <file_name>
```

View with pagination
```bash
less <file_name>
```

View the first few lines
```bash
head <file_name>
```

View the last few lines
```bash
tail <file_name>
```

Search for text in a file
```bash
grep <search_text> <file_name>
```

Check system information
```bash
uname -a
```

Check disk usage
```bash
df -h
```

Check memory usage
```bash
free -h
```

Check running processes
```bash
top
```

Check CPU information
```bash
lscpu
```

Check network interfaces
```bash
ifconfig
```

Alternatively
```bash
ip a
```

Change file permissions
```bash
chmod <permissions> <file_name>
```

Give execute permission to the owner
```bash
chmod u+x <file_name>
```

Change file ownership
```bash
chown <user><group> <file_name>
```

Change group ownership
```bash
chgrp <group> <file_name>
```

Ping a host
```bash
ping <hostname_or_ip>
```

Check network connectivity
```bash
curl <url>
```

Download a file
```bash
wget <url>
```

Check open ports
```bash
netstat -tuln
```

SSH into a remote server
```bash
ssh <username>@<hostname_or_ip>
```

Copy files over SSH (SCP)
```bash
scp <source> <username>@<hostname_or_ip><destination>
```

Update package list
```bash
sudo apt update
```

Install a package
```bash
sudo apt install <package_name>
```

Remove a package
```bash
sudo apt remove <package_name>
```

Update all installed packages
```bash
sudo apt upgrade
```

List running processes
```bash
ps aux
```

Kill a process by PID
```bash
kill <pid>
```

Kill a process by name
```bash
pkill <process_name>
```

Run a process in the background
```bash
<command> &
```

Bring a background process to the foreground
```bash
fg
```

Compress a file or directory (tar.gz)
```bash
tar -czvf <archive_name.tar.gz> <file_or_directory>
```

Extract a tar.gz archive
```bash
tar -xzvf <archive_name.tar.gz>
```

Compress a file (zip)
```bash
zip <archive_name.zip> <file_or_directory>
```

Extract a zip archive
```bash
unzip <archive_name.zip>
```

Find files by name
```bash
find /path/to/search -name "<file_name>"
```

Search for a command in history
```bash
history | grep <command>
```

Check command history
```bash
history
```

Edit a file with nano
```bash
nano <file_name>
```

Edit a file with vim
```bash
vim <file_name>
```