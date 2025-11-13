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
 <br>
<img width="703" height="74" alt="1" src="https://github.com/user-attachments/assets/74a3ff90-490c-48ed-9be9-140ad88bff23" />
<br>
### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<br>
<img width="523" height="65" alt="2" src="https://github.com/user-attachments/assets/ab91242d-ed40-4769-9ac4-0306766401ed" />
<br>
 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
<br>
<img width="296" height="47" alt="3" src="https://github.com/user-attachments/assets/f0807f57-dea0-4261-819b-08a6f63e57e8" />
<br>

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
<br>
<img width="558" height="48" alt="4" src="https://github.com/user-attachments/assets/b059285c-b9d6-4bfa-a69a-1c272d98c8c3" />
<br>

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
<br>
<img width="612" height="53" alt="5" src="https://github.com/user-attachments/assets/888ee8f3-f1f0-4a44-9bee-df97a49fdde8" />
<br>

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<br>
 <img width="625" height="59" alt="6" src="https://github.com/user-attachments/assets/4ffbaddb-2518-4ef0-ae65-2b3d200f94bd" /><img width="417" height="56" alt="7" src="https://github.com/user-attachments/assets/fddf51b5-d713-4767-a055-157d2428e8ca" />

<br>
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
<br>
<img width="482" height="43" alt="8" src="https://github.com/user-attachments/assets/3faf8c37-b78d-4c56-ba58-b65f7da7f323" />
<img width="433" height="55" alt="9" src="https://github.com/user-attachments/assets/627bb57d-8009-4f43-8459-8f35095554c5" />
<br>
### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
<br>
<img width="389" height="41" alt="11" src="https://github.com/user-attachments/assets/609f8475-d200-45c5-a6f7-af5f9eb10323" />
<br>

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<br>
<img width="368" height="54" alt="10" src="https://github.com/user-attachments/assets/8004852d-d99d-4152-b9a3-3b1bcbc696ae" />
<br>

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
<br>
<img width="391" height="46" alt="12" src="https://github.com/user-attachments/assets/0321d6e3-1dbd-41bb-a802-3894ec5d208b" />
<br>
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<br>
<img width="401" height="41" alt="13" src="https://github.com/user-attachments/assets/7d00164a-1413-4a09-b797-e37427e1b476" />
<br>

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
<br>
<img width="913" height="139" alt="14" src="https://github.com/user-attachments/assets/d1e2a7de-8899-47e3-b8e4-a021eb532bcd" />
<br>

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
<br>
<img width="465" height="149" alt="15" src="https://github.com/user-attachments/assets/e0e1bc1a-e2d8-4944-8cc3-428f36ff49b2" />
<br>

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<br>
<img width="937" height="97" alt="16" src="https://github.com/user-attachments/assets/a0a2d72e-13d9-4c54-99cd-79de91203bbe" />
<br>
### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
<br>
<img width="536" height="53" alt="17" src="https://github.com/user-attachments/assets/df27af83-9113-41a5-9b2c-b156e5202a70" />
<br>

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<br>
<img width="546" height="55" alt="18" src="https://github.com/user-attachments/assets/6a7e6dbf-4681-40fe-b05a-f8e6291236a4" />
<br>

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<br>
<img width="530" height="48" alt="19" src="https://github.com/user-attachments/assets/c7906c97-01b5-4e56-b7d4-d91996271a22" />
<img width="613" height="65" alt="20" src="https://github.com/user-attachments/assets/2323df1e-ad0e-4449-9cd4-8a2f14cea6ff" />
<br>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
<br>
<img width="536" height="55" alt="21" src="https://github.com/user-attachments/assets/0d635aac-ff46-4c98-9f00-78d326fd2733" />
<img width="937" height="96" alt="22" src="https://github.com/user-attachments/assets/1319c89b-837d-4451-ae2d-b72b82e2474d" />
<br>


### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
<br>
<img width="659" height="68" alt="23" src="https://github.com/user-attachments/assets/a61cd1d5-42aa-477d-bbcb-fae6fff31ce4" />
<br>

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<br>
<img width="372" height="35" alt="25" src="https://github.com/user-attachments/assets/a969eb74-355d-4b70-aa03-6d9ca8184838" />

<br>
### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<br>
<img width="732" height="105" alt="26" src="https://github.com/user-attachments/assets/23986063-5601-46e7-911a-095a2f749e59" />
<br>
### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 <br>
<img width="572" height="50" alt="27" src="https://github.com/user-attachments/assets/8e4cec95-71fb-43f5-9941-2aec8780e22a" />
<img width="647" height="56" alt="28" src="https://github.com/user-attachments/assets/470c57af-0da8-4940-91d3-57efc651c0e7" />

<br>

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
<br>
<img width="692" height="113" alt="29" src="https://github.com/user-attachments/assets/8ab8f73b-737b-412e-b772-a606b3f9b119" />
<br>

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
<br>
<img width="618" height="54" alt="30" src="https://github.com/user-attachments/assets/1aa1d9bb-18ae-484d-b79e-d068452cd3fb" />
<img width="346" height="57" alt="32" src="https://github.com/user-attachments/assets/3ed440f3-9fd4-468b-8eca-8d14c578019f" />
<img width="831" height="76" alt="34" src="https://github.com/user-attachments/assets/cb9541df-b64f-4586-90c5-0c0c10fc716e" />
<br>


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
<br>
<img width="470" height="103" alt="35" src="https://github.com/user-attachments/assets/997cd31e-5175-4cb4-a824-077033247734" />
<img width="413" height="111" alt="36" src="https://github.com/user-attachments/assets/35519531-827d-4560-bdc9-0925be47b3fd" />
<br>
 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<br>
<img width="377" height="190" alt="37" src="https://github.com/user-attachments/assets/6d0f1a08-526c-4526-b48c-96bfab8cb208" />
<br>



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
<br>
<img width="569" height="55" alt="41" src="https://github.com/user-attachments/assets/29b4f795-d5c8-4ddb-bb5e-47f6f5848985" />
<br>

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<br>
<img width="745" height="205" alt="38" src="https://github.com/user-attachments/assets/7a4fcda7-95ee-4ca9-a29e-789fbc040c25" />
<br>

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”
<br>
<img width="432" height="213" alt="39" src="https://github.com/user-attachments/assets/bfa9ce94-33e0-4e4c-bb65-1572fa0fa2ad" />
<br>



## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
