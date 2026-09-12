# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 

ls


**Output:**

<img width="1417" height="202" alt="639459273-f29979a0-e7df-4a7d-ac51-02f2cc8d4fd3" src="https://github.com/user-attachments/assets/58e09049-3b2e-4a54-bc77-dfe19cbcd5d1" />

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**

pwd


**Output:**
<img width="403" height="244" alt="639459502-467e9cd8-516a-413e-82a3-585e0a73f9e1" src="https://github.com/user-attachments/assets/60d9560d-cd89-4331-bfcf-a391a011017a" />


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**

mkdir <directory_name>


**Output:**
<img width="764" height="148" alt="639459956-5c6bc406-e290-469d-9d09-e507ce830c78" src="https://github.com/user-attachments/assets/fb337dd4-5a88-4fec-9d9b-e5248f17d845" />


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**

rmdir <directory_name>


**Output:**
<img width="831" height="224" alt="639460304-29ed8117-39de-48fe-951d-50eef8182ff1" src="https://github.com/user-attachments/assets/9ae9582d-6197-4c17-b2e0-3c4f59cbb273" />

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**

cd <directory_name>


**Output:**
<img width="542" height="184" alt="639460619-2062a1cc-8124-4e5d-a7cb-38ce1d27d83e" src="https://github.com/user-attachments/assets/5593f296-f622-411f-b85a-f6d77d9ed3a7" />


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**

cat [OPTION]... [FILE]...


**Output:**
<img width="344" height="194" alt="639461019-447e6bcc-56b2-4427-afce-7c869d735fa2" src="https://github.com/user-attachments/assets/5a6269b0-63f9-42aa-9a53-78744afe0612" />


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**

cp <source_file> <destination_file>


**Output:**
<img width="299" height="197" alt="639461515-6d0f12d4-9e2f-4864-ae72-661a6a15e1f5" src="https://github.com/user-attachments/assets/73671b99-a9ca-4149-be13-5f183c6a4e37" />


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**

gedit <file_name>


**Output:**
<img width="457" height="70" alt="639462080-4bc983e7-18aa-4d2b-95b9-ac328fcf07a3" src="https://github.com/user-attachments/assets/db6d0d78-e81c-4b06-af63-eba512bc8761" />


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**

su <username>


**Output:**
<img width="469" height="178" alt="639462801-421431ad-a4d6-4035-9340-491aeacc6260" src="https://github.com/user-attachments/assets/76205ef4-b2e7-4d02-a926-547bacf7b67a" />


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**

mv <file_name> <directory_path>


**Output:**
<img width="646" height="568" alt="639463390-1170e4c1-17ed-4b7a-8e0c-68430f7203d0" src="https://github.com/user-attachments/assets/8cc006c4-5c61-48d0-a273-933a4ad4fcd6" />


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**

rename 's/old-name/new-name/' <files>


**Output:**
<img width="555" height="79" alt="639466640-c1b0c5a8-460a-4368-ad7f-086aad9aeeeb" src="https://github.com/user-attachments/assets/fe170b2a-8103-4071-b565-a3a20f9b72b4" />


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**

head <file_name>


**Output:**
<img width="672" height="449" alt="639466982-42c12f7c-232f-4209-89e7-4d8efc82e143" src="https://github.com/user-attachments/assets/245475dc-d646-41ec-8ef2-5f39dcab597a" />


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**

tail <file_name>


**Output:**
<img width="726" height="454" alt="639467224-e322f684-0844-4a7b-8416-bdf9036d41e1" src="https://github.com/user-attachments/assets/00b43742-31be-43c1-b523-ca73def878ce" />


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**

id


**Output:**
<img width="956" height="116" alt="639467427-6caa7713-f7f1-4d63-8f6c-ef89ca01e78c" src="https://github.com/user-attachments/assets/9cbc0a95-5c42-4573-8464-d2435cd6886d" />


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**

command | grep <search_word>


**Output:**
<img width="485" height="116" alt="639467701-39c52784-1d3b-43fd-aa44-7c161f6b6b95" src="https://github.com/user-attachments/assets/c9296b71-0cd2-4c1e-a98c-cce6d33159bb" />


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**

command | tr <old> <new>


**Output:**
<img width="793" height="504" alt="639468443-0e70a886-075d-4728-9566-0438a1cd4051" src="https://github.com/user-attachments/assets/71fba64e-c438-4958-b178-72f19a0196d6" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**

chmod <options> <permissions> <file_name>


**Output:**
<img width="286" height="80" alt="639469014-ea109067-ad34-4a48-a763-cd26ab918add" src="https://github.com/user-attachments/assets/dafda86b-1edc-4b9b-80cb-bacd42e576f9" />


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**

tar [options] [archive-file] [files_to_archive]


**Output:**
<img width="368" height="68" alt="639469882-4654c44d-bdeb-4553-b5b2-954dbd219a75" src="https://github.com/user-attachments/assets/b9e02d19-64c9-4eff-a45f-2343c8173d14" />


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
chown <owner_name> <file_name>


**Output:**
<img width="314" height="91" alt="639471075-52f05da3-779c-4d73-b094-dc5a4e218a7d" src="https://github.com/user-attachments/assets/ed409c99-a842-462a-9bb2-059482f906c1" />


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
make [-f makefile] [options] [targets]


**Output:**
<img width="551" height="203" alt="639472559-0a14d594-8a6d-4b5b-8573-e2f7c5869bd9" src="https://github.com/user-attachments/assets/08b17700-5099-4dfc-8430-f2fcdad75f62" />


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
ifconfig [options] [interface]


**Output:**
<img width="788" height="313" alt="639472805-98ea5fa6-cd70-4bd1-8a84-eb9a539681cd" src="https://github.com/user-attachments/assets/cc9c2e1a-0c03-43a0-9231-50a7322c5561" />


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**

chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder


**Output:**
<img width="302" height="85" alt="639473021-eebf8e3e-6b77-445e-8001-205c9fecd346" src="https://github.com/user-attachments/assets/0cf0712d-4e68-41b5-bfc6-56d90b0251c1" />


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
host <domain_name> or <ip_address>


**Output:**
<img width="921" height="116" alt="639473284-a133cfc0-e6be-40ca-9f06-2f42db16c095" src="https://github.com/user-attachments/assets/d27c5de8-ce4e-4c22-b537-1c5ac75182fe" />


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
gzip <file1> <file2> <file3>...


**Output:**
<img width="569" height="237" alt="639473882-8df4cc12-e7d8-4a53-879e-c11b596a573b" src="https://github.com/user-attachments/assets/28318485-2c8b-4035-bd70-477f6a2aab92" />


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
sort <file_name>


**Output:**
<img width="305" height="185" alt="639474093-ea17c9e4-2932-4151-8363-e89a979a1e33" src="https://github.com/user-attachments/assets/a9fceb25-8bfb-4098-883a-fd33665b219a" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
cal


**Output:**
<img width="325" height="155" alt="639474583-bc7c1f8a-a458-4cdd-b60d-f23b8f57a95c" src="https://github.com/user-attachments/assets/e0a038f9-b135-4e80-9bb2-7987696726a6" />


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
clear


**Output:**
<img width="278" height="38" alt="639474771-626e9252-2a9f-4023-9c06-0a673158d588" src="https://github.com/user-attachments/assets/3d3f0f2e-f2a0-4b57-94ca-d74ea0b7bf3a" />


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
mail

**Output:**
<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/c0e6c12e-229b-408a-8917-96fae9d69b39" />


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
df

**Output:**
<img width="781" height="218" alt="639476795-1caca7a7-5677-41af-8d4c-b5e88ad3a280" src="https://github.com/user-attachments/assets/1a5195c0-d241-4acb-9504-d0d17365ab4c" />


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
find <directory> -name <file_name>


**Output:**
<img width="449" height="216" alt="639477166-3620026f-6ca4-414c-91d7-fdd7e874e406" src="https://github.com/user-attachments/assets/38d45a6f-c92f-4aa6-b8b6-abd404030278" />


## Result
Linux commands are executed in the linux terminal successfully.
