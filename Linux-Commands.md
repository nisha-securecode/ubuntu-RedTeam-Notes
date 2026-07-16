## 1. 🔄 System Update - Ubuntu Ko Taza Rakho
```bash
sudo apt update          
sudo apt upgrade        
sudo apt install nmap
```

## 2. 🧭 File System Navigation
```bash

pwd                     # Print Working Directory - shows your current location
ls                      # List files and folders in the current directory
ls -la                  # List all files including hidden ones with permissions
cd /var/log             # Change directory to Ubuntu's log folder
cd ~                    # Navigate to the home directory /home/username
cd ..                # Move up one directory level
```

## 3. 📁 File and Directory Operations
```bash

mkdir red-team-lab                   # Create a new directory named 'red-team-lab'
touch scan.txt          # Create a new empty file named 'scan.txt'
cp source.txt dest.txt  # Copy a file. User to copy directories
mv old.txt new.txt      # Move or rename a file or directory
rm file.txt             # Delete a file. This is permanent.
rm -r directory       # Recursively delete a directory and all its contents
```

## 4. 📖 Viewing and Searching File Contents
```bash

cat /etc/passwd             # Display the entire content of a file
head -n 10 file.txt         # Display the first 10 lines of a file
tail -f /var/log/auth.log   # Display the last 10 lines and follow updates live
less /var/log/syslog        # View large files with scrolling. Press 'q' to quit
grep "Failed" auth.log      # Search for the word "Failed" inside auth.log
```

## 5) Permissions & Editing
```bash
- `chmod` # Used to change file permissions: Read, Write, Execute
- `cat` # Used to display the content of a file on the terminal
- `nano / gedit` # Text editors used to edit a file
- `sudo` # Used to run commands with root/admin privileges
```

## 6) Search Commands
```bash
- `find` # Used to search for files in the system
- `locate` # Used to quickly search for files using a database
- `which / whereis` # Used to find the location of a command or file
- `grep` # Used to search for a specific word or text inside a file
- `head -n 10 file.txt` # Display the first 10 lines of a file
- `less /var/log/syslog` # View large files with scrolling. Press 'q' to quit
- `grep "failed" auth.log` # Search for the word "failed" inside auth.log
```

## 7) Permissions and User Management
```bash
- `chmod` # Change permissions of a file or folder
- `chown` # Change the owner of a file
- `umask` # Set default permissions for newly created files
- `useradd / usermod` # Create a new user or modify an existing user
- `passwd` # Set or change user password
- `sudo` # Run commands with admin/root permission
- `su` # Switch to another user
- `id / whoami` # Display current user and user ID
```

## 8) Process and Performance
```bash
- `ps / top / htop` # View running processes
- `kill / pkill` # Terminate a running process
- `free / uptime / vmstat` # Check system performance and memory usage
- `df / du` # Check disk space and usage
```
