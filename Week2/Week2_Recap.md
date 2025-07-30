# Week 2 Recap – macOS & Linux CLI Fundamentals

## Objective
Gain comfort with terminal navigation, file operations, and process control in macOS and Linux.

## Topics Covered
- Folder structure and file creation
- File permissions and ownership
- Background processes and process management
- Basic networking tools

## Commands Practiced
```bash
# File management
touch test.txt
ls -l
```
# Permissions and ownership
chmod 600 test.txt
chmod a+x script.sh
sudo chown root:staff secure.conf

# Background processing
sleep 100 &
jobs
ps aux | grep sleep
kill [PID]

# Networking
ping 8.8.8.8
traceroute google.com
networkQuality
nslookup apple.com

