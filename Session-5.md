# Basic Commands in Linux-
## power off OR init 0-
- To power off system 
## logout OR exit OR ctrl + d -
- Logout from currently logged in user.

# Commands To View System Information-                                                                                                                           
## hostnamectl
Show detailed information about system
## uname
- It display Operating System name.
## uname -r
It display kernel release information.
## uname -a
#### It displays:
- Kernel Version: This includes information about the kernel version running on the system.
- Hostname: This displays the name of the system on the network (fully qualifiled).
- Kernel Release: This provides the release number of the kernel.
- Kernel Architecture: This indicates the system's architecture, such as x86_64 for 64-bit systems or i686 for 32-bit systems.
- Operating System: This specifies the name of the operating system.
## ls(List)-
* It is used to list files and directories in a directory. It is used to list files and directories in a directory.
- l: Long format. Displays detailed information about files, including permissions, owner, group, size, and modification time.
- a: All entries. Shows hidden files (those starting with a dot .).
- h: Human-readable. Prints file sizes in a human-readable format (e.g., KB, MB, GB).
- R: Recursive. Lists subdirectories recursively. It is used to display files and directories in reverse order. It reverses the order of the sorting, showing the files or directories in descending order based on their names.
- t: Sort by modification time, newest first.
- S: Sort by file size, largest first.

## mkdir(make directory)- 
- Used to create directories (folders).
- It allows users to create one or more directories with specified names. mkdir is a fundamental utility for managing the directory structure in a Linux file system.
### Creating a Single Directory:
mkdir my_directory
### Creating Multiple Directories:
mkdir dir1 dir2 dir3
## rmdir (Remove Directory)- 
- Command is used to remove empty directories in Linux.
- rmdir directory_name
## mv (Move)-
- Command in Linux is used to move or rename files and directories 
- mv file_name destination/
## cp (Copy)- 
- Command in Linux is used to copy files and directories from one location to another.
- It can be used to duplicate files and create backups.
## touch-
- Used to create empty files and update the access and modification timestamps of existing files.
- touch new_file.txt
- touch file1.txt file2.txt file3.txt
- touch existing_file.txt
- This command updates the access and modification timestamps of the existing file without modifying its content.
## cat- 
- display the content of files and concatenate file.
- displaying the content of files and concatenating files, but you can use it in combination with input redirection to create a file with data
- cat filename.txt- Display content
- cat file1.txt file2.txt- Concatenate
- cat file1.txt > newfile- copy one file into another
## ls(List)-
* It is used to list files and directories in a directory. It is used to list files and directories in a directory.
- l: Long format. Displays detailed information about files, including permissions, owner, group, size, and modification time.
- a: All entries. Shows hidden files (those starting with a dot .).
- h: Human-readable. Prints file sizes in a human-readable format (e.g., KB, MB, GB).
- R: Recursive. Lists subdirectories recursively. It is used to display files and directories in reverse order. It reverses the order of the sorting, showing the files or directories in descending order based on their names.
- t: Sort by modification time, newest first.
- S: Sort by file size, largest first.
## echo- 
- for printing messages or information to the console
## man- 
### Mannual page- 
- It is form of documentation in Unix-like operating systems that provides detailed information about a specific command, utility, or function.
-  These manual pages serve as a reference guide, offering users comprehensive information on how to use a particular command or program.
- Access man page by using man command 
## info- 
same as manual page
  







