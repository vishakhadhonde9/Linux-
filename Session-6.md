# Hierarchy of Linux File Management System-
In Linux, files are well managed using file management system. Linux File Management System manage files in hierarchical structure where, “/” (slash) is main directory or root directory (root node in hierarchy). All other directories comes beneath “/” directory. 

![image](https://github.com/vishakhadhonde9/Linux-/assets/97825776/682ca238-07e1-4e22-a25f-e88de3410a67)

## /- 
- root of file system
- Every single file and directory start from the root directory.
- The only root user has the right to write under this directory.
  
## /root- 
- Home directory of root user. In this directory, root user can store its personal files.
- Every single file and directory start from root dir.
- Only root user has right to write under this directory.
## /home-	
- It stores home directories of Standard/local users.
- Home directories are assigned to each user separately and no other user can access home directories of other users (Except root user).
- Automatically created as “/home” for each user- login directory
## /etc- 
- It stores all configuration files of system and services, some security related files, config file related to networking. 	
## /var -	
- It stores variable data- files that are expected to change frequently as system runs such as mails, logs, messages, etc. 	e.g.-/var/log
## /bin- 	
- It stores binary executable files contain executable code/data. These binary executable files are nothing but the commands.
- It is a link of /usr/bin directory. (this directory contains commands that can be used by local users)
## /sbin -	
- It stores system binary executable files.
- It is same as bin directory except that only super user has to execute commands from sbin.
- It is also a link of /usr/sbin directory. (This directory contains commands that only root user can use.)
## /boot-	
- It stores boot loader program and all other boot related files.
- It helps to operating system to load 	correctly so its important in computer’s startup process.
## /lib- 	
- Library files information- contains complied code that programs can use to perform various function.
- This directory is actually a soft link of /usr/lib directory.
## /lib64-
- Same as that of lib directory and stores 64 architecture library file information.
## /usr-
- User related files- is typically used to store user-related program files and data Such as documentary files, manual pages, etc.
- This directory also contain lib, bin, and sbin directory.
* ‘/usr/bin’ contains basic user commands
* ‘/usr/sbin’ contains additional commands for the administrator
* ‘/usr/lib’ contains the system libraries
* ‘/usr/share’ contains documentation or common to all libraries, for example ‘/usr/share/man’ contains the text of the manpage
## /sys- 	
- System information.
## /media-
- All removable devices.
## /proc-	
- Processes information. This directory also stores RAM and CPU related information.
## /mnt-
- Standard directory to mount storage device temporary.
- In mnt, temporary files available up to 30 days.
## opt-
-  Use for add-on service.
-  Contains optional software packages
## /run- 
- Contains runtime files and directories that are created and deleted automatically.
- Current Running Devices.
## /dev -	
- /dev directory stores device information and their block files.
- These files represent physical and virtual devices connected to the system and provide an interface for interacting with them. 
## /tmp-
- It stores temporary files. It stores temporary data for 10 days.
## /srv-
- Contains data for services provided by the system.






