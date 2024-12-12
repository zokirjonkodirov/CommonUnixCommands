# CommonUnixCommands
A collection of the most commonly used Unix commands with simple, practical examples

## **File and Directory Management**
**`ls`**: List files and directories.
   ```bash
   ls
   ls -la
  ```
**`pwd`**: Print the current working directory.
   ```bash
   pwd
  ```
**`mkdir`**: Create a new directory.
   ```bash
   mkdir new_folder
  ```
**`rm`**: Remove files or directories.
   ```bash
   rm file.txt
   rm -r folder_name
  ```
**`cp`**: Copy files or directories.
   ```bash
   cp source.txt destination.txt
   cp -r folder1 folder2
  ```
**`mv`**: Move or rename files or directories.
   ```bash
   mv old_name.txt new_name.txt
   mv file.txt /destination/path/
  ```
**`touch`**: Create an empty file.
   ```bash
   touch file.txt
  ```
**`open`**: Open files or applications.
   ```bash
   open file.txt
   open -a "Safari"
  ```
**`find`**: Search for files and directories.
   ```bash
   find . -name "*.txt"
  ```
## **File Content Viewing**
**`cat`**: Display the content of a file.
   ```bash
   cat file.txt
  ```
**`less`**: View file content one screen at a time.
   ```bash
   less file.txt
  ```
**`head`**: Show the first 10 lines of a file.
   ```bash
   head file.txt
  ```
**`tail`**: Show the last 10 lines of a file.
   ```bash
   tail file.txt
  ```
**`wc`**: Word, line, character count.
   ```bash
   wc file.txt
   wc -l file.txt
  ```
**`grep`**: Search for patterns in a file.
   ```bash
   grep "pattern" file.txt
  ```
**`diff`**: Compare two files.
   ```bash
   diff file1.txt file2.txt
  ```
## **Disk and System Info**
**`df`**: Disk space usage.
   ```bash
   df -h
  ```
**`du`**: Disk usage of a directory.
   ```bash
   du -sh folder_name
  ```
**`top`**: Display running processes.
   ```bash
   top
  ```
**`ps`**: View running processes.
   ```bash
   ps -aux
  ```
**`kill`**: Terminate a process.
   ```bash
   kill PID
  ```
**`uptime`**: Show system uptime.
   ```bash
   uptime
  ```
**`who`**: Show logged-in users.
   ```bash
   who
  ```
**`date`**: Display current date and time.
   ```bash
   date
  ```
**`cal`**: Show the calendar.
   ```bash
   cal
  ```
**`hostname`**: Display the computer's hostname.
   ```bash
   hostname
  ```
## **Networking**
**`ping`**: Test network connectivity.
   ```bash
   ping google.com
  ```
**`ifconfig`**: View network configuration.
   ```bash
   ifconfig
  ```
**`curl`**: Make HTTP requests.
   ```bash
   curl https://example.com
  ```
**`wget`**: Download files from the web.
   ```bash
   wget https://example.com/file.zip
  ```
**`scp`**: Securely copy files between systems.
   ```bash
   scp file.txt user@host:/path/to/destination
  ```
**`uptime`**: Show system uptime.
   ```bash
   uptime
  ```
**`ssh`**: Connect to a remote system.
   ```bash
   ssh user@hostname
  ```
**`netstat`**: View network statistics.
   ```bash
   netstat -an
  ```
## **Compression and Archiving**
**`zip`**: Compress files into a .zip archive.
   ```bash
   zip archive.zip file1 file2
  ```
**`unzip`**: Extract a .zip archive.
   ```bash
   unzip archive.zip
  ```
**`tar`**: Compress or extract tar archives.
   ```bash
   tar -cvf archive.tar folder_name
   tar -xvf archive.tar
  ```
