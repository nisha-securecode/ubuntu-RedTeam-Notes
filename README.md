# ubuntu-RedTeam-Notes
# 🐧 Ubuntu Linux Commands for Red Team - Nisha's Notes
**B.Tech CS 1st Sem | Target: Penetration Tester | OS: Ubuntu 24.04**

Hi, I'm Nisha 👋 Aspiring Ethical Hacker from jharkhand, India. These are my personal Ubuntu notes for Red Teaming. Learning in public 💜

---

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

#### 5. Search Commands
`find`: Search for files in a directory hierarchy.
`locate`: Quickly search for files by name.
`grep [pattern] [file]`: Search for specific text inside files.

#### 6. User & Permission Management
`chmod [permissions] [file]`: Change file access permissions.
`chown [user] [file]`: Change file owner.
`useradd` / `usermod` / `passwd`: User account management.
`sudo`: Execute commands with root privileges.

#### 7. System & Process Management
`ps` / `top` / `htop`: View running processes.
`kill [PID]`: Terminate a process.
`free`: Check memory usage.
`df` / `du`: Check disk space usage.

