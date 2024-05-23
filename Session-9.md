# User Management in Linux-
- A user is a person who utilizes a computer or network service.
- Linux is said to be secure because one user cannot access files of other user without its permission.
- Each user is assigned an ID that is unique for each user in the operating system.
## There are three types of user:
### 1. Super user: 
- Super users are those users who has all privileges of Linux system.
- On all Linux systems, by default there is the user root, also known as the super user.
- This account is used for managing Linux. Root, for instance, can create other user accounts on the system.
- For some tasks, root privileges are required. Some examples are installing software, managing users, and creating partitions on disk devices. 
### 2. System user: 
- System accounts are used by the services in Linux system.
- These accounts or users generally created when services are installed in system. 
### 3. Standard user: 
- local user accounts or standard user accounts are for the people who need to work on a system and who need limited access to the resources on that system.
- These user accounts typically have a password that is used for authenticating the user to the system.
# Adding New User-
- Adding new local user means creating user account.                                                                                                       
- User can be added by root user or using root user’s privileges.
- Whenever new user has been added, some files get affected. These files holds user accounts related information.                                                                                                                                                                                   -Also whenever new user is created, by default, its home directory and mail account also has been generated.  -New users are created using some skeleton files located in /etc/skel directory. These files are hidden and copied into home directory of new user.
* useradd [username]- Create user acc
* usermod [username]- modify or changes exiting user acc 
* userdel [username]- delete exiting user acc
# Password Management-
## passwd: 
- Password is the secret phrase that can be used to login to the system.
- ‘passwd’ command will be used to assign or change password of any user by root user.
- whenever, password assigned to the user, it will stored in /etc/shadow file in encrypted format.
- Only root user can change password of any user, but local users can change their own password.
- Password should follow some rules such as:
* Password must be 8 character long
* It should not contain user name
* It cannot accept old password
* Any dictionary name is not allowed
* Password should not be too simplistic 
- passwd - change current user’s password 
- passwd [user_name] - assign or change other user’s password by root user.
# View and change password policy-
- chage – ‘chage’ (change age) command use to view or modify password policy of user.
- chage <option> <parameter> <username> 

### Options:
- -l :- list / view password policy.
- -m :- min. days between password change.
- -M :- maximum days between password change.
- -W :- number of days of warning.
- -I :- number of inactivation days.
- -E :- Expiry date of user account.
- -d :- force to change password!
# Group Management-
- Group is collection of user accounts that share set of permissions.
- Primary Group- Every user acc associated with primary group.
- Specified in /etc/passwd
- Secondary group- any additional group
- Specified in /etc/group
- groupadd – ‘groupadd’ command is use to add secondary or supplementary group in system. Group information are stored in /etc/group file. 
* Syntax- 
- groupadd [groupname]
- groupmod [groupname]
- groupdel [groupname]
# Password Management-
## gpasswd –
- ‘gpasswd’ command is use to give password to group.
- It also can be used to add members and assign admin to the group.
* gpasswd <option> <parameter> <groupname> 
### Options:
- -a :- Add members in group
- -M :- Set list of members in group
- -A :- Assign user as group admin 





