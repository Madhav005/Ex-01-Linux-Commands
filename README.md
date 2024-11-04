# Ex-01-Linux-Commands

## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

![image](https://github.com/user-attachments/assets/334df00f-b0bc-46fe-8488-6f77c15843e1)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/user-attachments/assets/e5941d2a-6e50-45bc-9af9-e13cadefe9a2)
 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/user-attachments/assets/991fe207-13a4-4e9a-959d-397300b0a1b0)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/user-attachments/assets/3133ef3b-5caa-4802-adc4-e160db47c5f6)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/user-attachments/assets/7bdd5718-f59e-4be7-b794-589212279ca5)

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/user-attachments/assets/e4ae3098-bd65-4f06-9593-a930238cde30)
 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/user-attachments/assets/4cbd4704-ad1c-4e80-a54e-3feabbac0c0d)

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/user-attachments/assets/e74b51f1-5911-42c5-bd79-8e754c2986a6)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/user-attachments/assets/51b28c98-4c80-42aa-bf4f-3eaecb68016c)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/user-attachments/assets/e00b8aa1-fa0c-484d-92c2-81f184ebd123)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/user-attachments/assets/550bd45b-364f-40b5-a7c7-a33c985b9603)

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/user-attachments/assets/e0d255dd-8a37-4393-be2f-aa8589590f4b)

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/user-attachments/assets/de545191-cc15-465d-8fd9-9808f72b5855)
 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/user-attachments/assets/cc850010-77dd-4898-9865-1a37bc926f03)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/user-attachments/assets/09284012-8356-49fc-8a0c-c08f0fb57536)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/user-attachments/assets/842effe5-f7a2-44cf-a810-8d9164499210)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

![image](https://github.com/user-attachments/assets/63034207-565b-4d65-a661-85c131f12197)
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![image](https://github.com/user-attachments/assets/414a87f5-a198-4d56-974e-5a170e03d858)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/user-attachments/assets/65b438af-b4b9-4b72-9526-50b304a9b507)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/user-attachments/assets/9cc7ea0a-c8a9-4be7-affe-c32e58ba4c0b)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

![image](https://github.com/user-attachments/assets/d55378a4-3860-44f0-83b4-52d44c4729ef)

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/user-attachments/assets/ecd91f64-018b-4c86-a702-cfbd96f6a659)

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/user-attachments/assets/0f0b022d-e12b-4d8c-9544-3f9812c3c294)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/user-attachments/assets/8cbe08d5-32f8-4e51-a954-4df13d5a2592)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/user-attachments/assets/c2edaf81-37bd-4535-b5d5-65a4a87a216c)

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/user-attachments/assets/288782d6-fd97-408c-be6d-714fc9ac5b78)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/user-attachments/assets/6353de44-5346-445a-ae1c-c8fec6a95465)

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/user-attachments/assets/96a05b6d-39ea-4d53-b152-5a6e52c3cd2f)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

![image](https://github.com/user-attachments/assets/e009da89-58ba-438d-a64e-1ec2abadcd4f)

## RESULT:
Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
