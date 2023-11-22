# RedHat-System-Administration-
## lab1

### 2. What is the difference between cat and more command?
####   Both display rhe content of the file but the difference is that in case of larger files, 'cat' command output will scroll off your screen while 'more' command displays output one screenful at a time (page by page ).
    

### 3. What is the difference between rm and rmdir using man?
#### rm 
##### Remove files or directories




##### SYNOPSIS rm [OPTION]... [FILE]...
#### DESCRIPTION
#####  This manual page documents the GNU version of rm. rm removes each specified file. By default, it does not remove directories.    
#### rmdir
##### Remove empty directories
##### SYNOPSIS rmdir [OPTION]... DIRECTORY...
#### DESCRIPTION    
##### Remove the DIRECTORY(ies), if they are empty.

### 4. Create the following hierarchy under your home directory:
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q4.png)

#### a. Remove dir11 in one-step. What did you notice? And how did you overcome that?
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q4-a.png)

#### b. Then remove dir12 using rmdir –p command. State what happened to the
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q4-b.png)

#### c. The output of the command pwd was /home/user. Write the absolute and relative path for the file mycv
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q4-c.png)

### 5. Copy the /etc/passwd file to your home directory making its name is mypasswd.
### 6. Rename this new file to be oldpasswd.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q5.png)

### 7. You are in /usr/bin, list four ways to go to your home directory
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q7.png)

### 8. List Linux commands in /usr/bin that start with letter w
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q8.png)

### 9. Display the first 4 lines of /etc/passwd
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q9.png)

### 10.Display the last 7 lines of /etc/passwd
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q10.png)

### 11.Display the man pages of passwd the command and the file sequentially in one command.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q11-output.png)

### 12.Display the man page of the passwd file.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q12-output.png)


### 13.Display a list of all the commands that contain the keyword passwd in their man page.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab1/q13.png)



## Lab2
### 1. Create a user account with the following attribute and username: islam and Fullname/comment: Islam Askar and Password: islam
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q1.png)

### 2. Create a user account with the following attribute and Username: baduser and Full name/comment: Bad User and Password: baduser
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q2.png)

### 3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q3.png)

### 4. Create a supplementary group called badgroup
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q4.png)

### 5. Add islam user to the pgroup group as a supplementary group
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q5.png)

### 6. Modify the password of islam's account to password
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q6.png)

### 7. Modify islam's account so the password expires after 30 days
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q7.png)

### 8. Lock bad user account so he can't log in
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q8.png)

### 9. Delete bad user account
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q9.png)

### 10. Delete the supplementary group called badgroup.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q10.png)

### 13.Create a folder called myteam in your home directory and change its permissions to read only for the owner.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q13.png)

### 14.Log out and log in by another user.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q14.png)
### 15.Try to access (by cd command) the folder (myteam)
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q15.png)
### 16. Using the command Line
#### a- Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others(using chmod in 2 different ways)
![FOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q16-a.png)

#### b-Change your default permissions to be as above.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q16-b.png)
#### c-What is the maximum permission a file can have, by default when it is just created? And what is that for directory.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q16-c.png)
#### d-Change your default permissions to be no permission to everyone then create a directory and a file to verify.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q16-d.png)
### 17.What are the minimum permission needed for:
#### Copy a directory (permission for source directory and permissions for target parent directory)
##### source directory : r-x
##### target parent directory: -wx
#### Copy a file (permission for source file and and permission for target parent directory)
##### file: r--
##### source directory : --x
##### target parent directory : -wx
#### Delete a file
##### file: ---
##### source directory: -wx
#### Change to a directory
##### --x
#### List a directory content (ls command)
##### r--
#### View a file content (more/cat command)
##### r--
#### Modify a file content
##### for interactive tool like vi need rw-
##### for non interative tool vi need -w-
### 18.Create a file with permission 444. Try to edit in it and to remove it? Note what happened.
![UNFOUND](https://github.com/yossrmohammed/RedHat-System-Administration-/blob/main/lab2/q18.png)
### 19. What is the difference between the “x” permission for a file and for a directory?
#### file: allow user to run this file.
#### directory: allow user to make cd to it.


