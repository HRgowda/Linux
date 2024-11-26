----------Working with directories:-----------

1. man : Gives detailed information about the command we specify.

2. pwd : Displays the present/current working directory.

3. ls : Lists all the directories of the current path/directory.

4. ls -a : Lists all the directories and files ( hidden and unhidden )

5. ls -lah : Lists all the directories and files in more readable form ( Ex : A file 4009 Feb 2 18:30 .git is displayed as A file 4.0k Feb 18:30 .git )

6. mkdir : Creates a new directory.

7. mkdir -p : Creates a new parent directory with 'n' number of children directories. ( Ex: mkdir -p folder1/folder1.1/folder1.11 )

8. rmdir <directory_name> : Deletes a direcotry.

9. rm -rf <directory_name> : Deletes the non-empty directory.

-----------Working with Files:-----------

1. file : It displays the information of the respective files whether it is a text document or an empty document etc.

2. touch : It is used to create file or files ( Ex: touch file1.txt ).

3. rm : Deletes a file ( Ex: rm file1.txt ).

4. cp : Copies file from one path to other ( Ex: cp ./DirectoryA/file1.txt ./DirectoryB ).

5. cp -r : Copies an entore directory.

6. mv : Moves or renames file ( Ex: mv file1 file2 ).

-----------Working with file contents:----------

1. head <file_name> : Displays the 1st part of a file. Prints the first 10 ten lines of the file.

2. tail <file_name> : Displays the last part of a file. Prints the last 10 ten lines of the file.

3. cat : Concatenates file and prints on the standard output. Prints all the content of a file.
   -> Different ways of using 'cat' command:
	a. We can open and view contents of different files at a time( cat file1 file2 file3 ).
	b. We can create a new file and can write into it inside the terminal itself ( cat > file1.txt ) ctrl + D to save the file.
	c. It can be used to rename a file ( cat file1 > file2 ).

4. more : Used to view the text files in the terminal , displaying one screen at a time in case the file is large.

5. less : It is linux utility that can be used to read the contents of the file on page at a time. It has faster access because if a file is large it doesn't access the complete file, but accesses it page by page.

-----------Linux file structure ( System information commands )----------

1. uptime: Tells how long the system has been running.

2. free : Displays the amount of free and used memory in the system.

3. ps : Reports a snapshot of the current processes.

4. df : Pulls a lot of information about the disk space.

5. df -h : Displays the information of the disk space in human redable form.

6. fdisk : Manipulates disk partition table.

7. lsblk : List all the block devices.

8. top : Displays linux processes.

9. htop : Displays or gives a clear representation of linux processes ( Benificiary during troubleshooting ).

-----------Network commands:-----------

1. ifconfig : Configures a network interface ( oldest version ).

2. ip : Shows/manipulates routing, network devices, interfaces and tunnels.

3. ip -a : Provides a detailed view.

----------Package Managers:----------

1. sudo : Stands for 'Super User Do', it is used to access restricted files and operations ( Executes a command as another user ).

2. apt : Used to install and update packages ( advanced management tool ). TO update any packages 'sudo apt update' or 'sudo apt upgrade'. To install a package 'sudo apt install <package_name>'. TO remove a package 'sudo apt remove <package_name>' .

----------Text Editors:----------

1. nano : One of the commands used to edit a file ( Ex: nano file1.txt ).

2. vim : It is a highly configurable and powerful text editor known for its efficiency in editing code and text through keyboard shortcuts.
	-> i : enter insert mode.
	-> ESC : exit insert mode.
	-> :w : save ( write ) changes.
	-> :q : quit vim .
	-> :wq : save and quit .
	-> :q! : quit without saving changes .
