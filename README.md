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
