# Linux Prompt-
- The Linux command line is a text interface to your computer. Often referred to as the shell, terminal, console, prompt.
- The command prompt is an executable CLI program, cmd.exe
- The default prompt for many Linux distributions is often a string ending with the dollar sign ('$') for regular users and a hash ('#') for the root or superuser.
- The prompt typically includes information about the current user, hostname, and the current working directory.

**[user@hostname current_directory]$**

* user: The current username.
* hostname: The name of the computer or server.
* current_directory: The path to the current working directory.
* $ or #: The prompt character, which is usually a dollar sign ('$') for regular users and a hash ('#') for the root user.

## Example- john@mylinuxmachine:~$
This prompt indicates that the current user is "john," the hostname is "mylinuxmachine," and the current working directory is the user's home directory (~).

# Commands-
- Commands are nothing but executable programs which perform specific task written in it.
- These executable programs can be called using their name as per provided syntax.
- Commands are nothing but executable programs which perform specific task written in it.
- These executable programs can be called using their name as per provided syntax.
  General Syntax:

## [commands] -[options] -[argument] [multiple arguments]
- Commands- To run the command.
- Options - To adjust behavior of the commands.
- Arguments - The behavior, file folder name.
# sudo (Super User DO)- 
- Generally used as a prefix for some commands that only superusers are allowed to run.
- If you prefix any command with “sudo”, it will run that command with elevated privileges or in other words allow a user with proper permissions to execute a command as another user, such as the superuser. -
- This is the equivalent of the “run as administrator” option in Windows. The option of sudo lets us have multiple administrators.
# su (short for substitute or switch user) 
- allows you to run commands with another user’s privileges.
- using su is the simplest way to switch to the administrative account in the current login session. 
# Basic Commands in Linux-
## pwd- Print Working Directory.                                                                                                                                     
- Displays the current working directory, shwoing the full path to your current  location in the file system.
  
## tty-
- This command displays current user terminal number. 	
## who am i- 
- Display current user details.
## whoami-
- It simply prints the username of the currently logged-in user.
## w-
- Display all current user details with their time schedule.
- Provides a summary of information about currently logged-in users, including details like usernames, terminal, remote host (if applicable), login time, idle time, JCPU (total time used by all processes attached to the terminal), PCPU (total time used by the current process), and more.
##  wh tab tab- 
- To see similar commands or autocomplete cmd. using the <tab> key for command autocompletion, is a feature of many Linux shells, such as Bash.
-  When you type a partial command and press the <tab> key twice, the shell attempts to autocomplete or show a list of possible commands or files that match the entered characters.
## Clear or ctrl+l - 
- It clears screen but not background data.
- Remember that using Clear does not erase the command history or any background data; it just provides a visually clean terminal window.
- If you scroll up, you'll still see previous commands and their output.
## cal  -
- It displays current month of calendar. This command is used to display a calendar in the terminal. By default, it shows the calendar for the current month.
## cal year - 
- It displays specified year calendar. 	
## cal month year - 
- It displays specific months calendar in particular year 
## cal -3- 
- It displays previous, current and next month's calendar of current year. 
## date-
- It shows current date and time.
- This output includes the day of the week, the month, the day of the month, the time, and the Coordinated Universal Time (UTC) offset.
- The exact output may vary depending on your system's configuration.
 ## date -s “YYYY/MM/DD HH:MM:SS “-
- It set date and time. The date -s option is used to set the date and time.
## reboot OR init 6 -
To restart the system 	
 

	



 

