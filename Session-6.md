# Hierarchy of Linux File Management System-
In Linux, files are well managed using file management system. Linux File Management System manage files in hierarchical structure where, “/” (slash) is main directory or root directory (root node in hierarchy). All other directories comes beneath “/” directory. 
## /- 
- root of file system
- Every single file and directory start from the root directory.
- The only root user has the right to write under this directory.
- /root is the root user’s home directory, which is not the same as /
## /root- 
- Home directory of root user. In this directory, root user can store its personal files.
- Every single file and directory start from root dir.
- Only root user has right to write under this directory.
## /home-	
- It stores home directories of Standard/local users.
- Home directories are assigned to each user 	separately and no other user can access home directories of other users (Except root user).
	automatically created as “/home” for each user- login directory
## /etc- 
- It stores all configuration files of system and services, some security related files, config file related to networking. 	
## /var -	
- It stores variable data- files that are expected to change frequently as system runs such as mails, logs, messages, etc. 	e.g.-/var/log
## /bin- 	
- It stores binary executable files contain executable code/data. These binary executable files are nothing but the commands.
- It is a link of /usr/bin directory. (this directory contains commands that 	can be used by local users)
## /sbin -	
- It stores system binary executable files.
- It is same as bin directory except that only super user has to 	execute commands from sbin.
- It is also a link of /usr/sbin directory. (This directory contains 	commands that only root user can use.)
## /boot-	
- It stores boot loader program and all other boot related files.
- It helps to operating system to load 	correctly so its important in computer’s startup process.
## /lib- 	
- Library files information- contains complied code that programs can use to perform various function.
- This directory is actually a soft link of /usr/lib directory. 	
## /usr-
- User related files- is typically used to store user-related program files and data Such as documentary 	files, manual pages, etc.
- This directory also contain lib, bin, and sbin directory whose links are 	available in main directory i.e. in “/” directory. 
## /sys- 	
- System information. 	
## /proc -	
- Processes information. This directory also stores RAM and CPU related information. 
## /dev -	
- /dev directory stores device information and their block files. 	




