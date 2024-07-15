# User Management in Linux-
- A user is a person who utilizes a computer or network service.
- Linux is said to be secure because one user cannot access files of other user without its permission.
- Each user is assigned an ID that is unique for each user in the operating system.
## There are three types of user:
### 1. System user: 
- System accounts are used by the services in Linux system.
- These accounts or users generally created when services are installed in system. 
### 2. Super user: 
- Super users are those users who has all privileges of Linux system.
- On all Linux systems, by default there is the user root, also known as the super user.
- This account is used for managing Linux. Root, for instance, can create other user accounts on the system.
- For some tasks, root privileges are required. Some examples are installing software, managing users, and creating partitions on disk devices. 
### 3. Standard user: 
- local user accounts or standard user accounts are for the people who need to work on a system and who need limited access to the resources on that system.
- These user accounts typically have a password that is used for authenticating the user to the system.
# Adding New User-
- Adding new local user means creating user account.                                                                                                       
- User can be added by root user or using root user’s privileges.
- Whenever new user has been added, some files get affected. These files holds user accounts related information.
- Also whenever new user is created, by default, its home directory has been generated.
  
* useradd [username]- Create user account.

### Files affected by newly added user:
- /etc/passwd: It store user profile related information, 
- /etc/shadow: It stores user password policies
- /etc/group: It store group information.
- /etc/gshadow: Stores group password and member’s list.

# To modify user-
* usermod [username]- modify or changes exiting user acc.
* usermod option parameters username 
#### Options, 
- -u :- user id
- -g :- primary group 
- -c :- Comment 
- -s :- login shell 
- -G :- secondary group 
- -l :- login name 
- -L :- lock user password 
- -U :- unlock user password 

  
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
* chage <option> <parameter> <username>
- Last password change -> the date when the password was changed most recently.
- Password expires -> the date when the password will expire.
- Password inactive -> how many days the account will remain inactive after the password is expired.
- Minimum number of days between password change -> the minimum day break required between two password changes.
- Maximum number of days between password change -> how many days you are left to change your current password.

### Options:
- -l :- list / view password policy.
- -m :- min. days between password change.
- -M :- maximum days between password change.
- -W :- number of days of warning.
- -I :- number of inactivation days.
- -E :- Expiry date of user account.
# Group Management-
- Group is collection of user accounts that share set of permissions.
- Primary Group- Every user acc associated with primary group.
- Specified in /etc/gpasswd
- Secondary group- any additional group
- Specified in /etc/group
### groupadd –
- ‘groupadd’ command is use to add secondary or supplementary group in system. Group information are stored in /etc/group file. 
* Syntax- 
- groupadd [groupname]
### usermod to add user in group-
- usermod option groupname username
### option-
- -G -groupname
- -a - append
### groupmod -
- Modify existing group with customize setting,
* Syntax-
- groupmod option parameter groupname
# Options, 
* -g :- Group id
- sudo groupmod -g new_gid groupname
* -n :- Group Name
- sudo groupmod -n new_groupname old_groupname
 
### groupdel-
- groupdel [groupname]

# Password Management-
## gpasswd –
- ‘gpasswd’ command is use to give password to group.
- It also can be used to add members and assign admin to the group.
- Specified in /etc/gshadow
* gpasswd <option> <parameter> <groupname> 
### Options:
- -a :- Add members in group
#### Syntax-
- gpasswd -a username groupname

- -M :- Set list of members in group
#### Syntax-
- gpasswd -M username1,username2,...,usernameN groupname

- -A :- Assign user as group admin
#### Syntax-
- gpasswd -A username groupname
  
- -d :- To remove user from group
#### Syntax-
- gpasswd -d username groupname







