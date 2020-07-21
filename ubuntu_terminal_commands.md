# Linux Terminal Commands
### What is Operating System?
### What is Linux OS?
Linux is the best-known and most-used open source operating system. As an operating system, Linux is software that sits underneath all of the other software on a computer, receiving requests from those programs and relaying these requests to the computer’s hardware.
### What is Ubuntu OS?
Ubuntu is a Linux distribution based on Debian mostly composed of free and open-source software. Ubuntu is officially released in three editions: Desktop, Server, and Core for Internet of things devices and robots
Here we present the basic but very important Ubuntu commands to give you an in-depth knowledge of how to use your Linux terminal.
### Basic Commands
- ```pwd``` Displays the path of the current directory.
- ```cd``` Stands for change directory and it is used to change the current directory.
- ```cd <DirectoryPath>``` Change the directory to the given path.
- ```cd ..``` Change the directory to up from the current directory.
- ```cd ~``` Change the directory to the home directory.
- ```cd``` Change the directory to the home directory.
- ```clear``` Is to clear the screen of Terminal.
- ```ls```  Displays the list of all directories, folder, and files present in the current directory.
- ```ls -l``` Displays the list of all directories, folder, and files present in the current directory along with other details.
- ```ls -a``` Displays hidden files along with the list of all directories, folder, and files present in the current directory.
- ```ls -la``` 
- ```ls -ltr``` Displays the name of directories, folders, files with their respective owner name, group’s name and rights your user have over these.
- ```whereis <PackageName>``` Is self-explanatory, as it displays the path where the package for specific built-in Linux command locates.
- ```whatis <Package>``` Is self-explanatory, as it displays a brief description of what is the functionality of specific built-in Linux command.
- ```history``` Displays the list of all commands entered since the user started the session.
- ```history -c``` Clear all the previous history 
- ```man <LinuxCommand>``` “man” stands for manual and it is used to display the user manual of any built-in Linux command.
- ```dir``` “dir” stands for directory and it is used to display the list of all directories or folders.

### Commands used for System Information
- ```df``` Shows the amount of disk space used and disk space available on every file system containing each filesystem’s name and its path.
- ```df -h``` Better understandable than ```df```.
- ```free``` Displays the amount of free and used memory in the complete system.
- ```uptime``` Provides information about how long the system has been running in one line.
- ```w``` Displays the detailed information about the users who are logged in the system currently.
- ```passwd``` It is used to change the password of the user.
- ```exit``` Exit from the system and log out from the current user.
- ```shutdown``` Used to shut down the system.

### Commands used for File Handling
 - ```mkdir <NewDirectory>``` allows users to create directories/folders in the system.
 - ```touch <FileName>``` Create new file.
 - ```rm <FileName>``` Used to remove files from the directory.
 - ```rm -rf <FileName>``` Allows users to remove directories/folders or files from the system. "-r" stands for recursive. When you do something recursively, you should know that your computer will execute commands that many times(or if nothing remains to do)
 - ```rmdir <Directory>``` Allows users to remove directories/folders from the system. 
 - ```mv <SourceDirectory/SourceFile> <DestinationDirectory>``` To move files or directories from one path to another path in the system.
 - ```cp <SourceFile> <DestinationDirectory/FileName>``` Copy file to a specific destination folder or to a folder with a filename.
 - ```cp -r <SourceDirectory> <DestinationDirectory>``` Copy a directory to the destination folder.
 - ```cat <FileName>``` Display each line of the file starting from the first row and finishing on its last row.
 - ```cat <FileName1> <FileName2>``` Display each line of the FileName1 and then FileName2 also.
 - ```cat <FileName1> <FileName2> > <OutputFileName>``` User can create a new file (OutputFileName) and append data from both the files (FileName1 and FileName2) into this new file named as utputFileName by using operand “>”.
 - ```cat <FileName1> >> <FileName2>``` Takes the standard output of the command on the left and appends (adds) it to the file on the right.
 - ```head -n <FileName>``` Prints the top N rows of data of the given FileName.
 - ```tail -n <FileName>``` Prints the last N rows of data of the given FileName.
 - ```echo <Expression>``` Used to display any expression that is passed as an argument.
 - ```unique <FileName>``` Print without any exact duplicates.
 - ```grep <Expression> <Directory/FileName>``` Used to search for a text in the specified file/folder.
 - ```zip <FileName.zip> <File1> <File2> <File3>``` Used to compress one or more files and store them in a new file with .zip extension.
 - ```unzip <ZipFile>``` Used to decompress a .zip file and extract all the files within to current directory.
 - ```ps aux | grep <RunningAppName>``` Display the PID (Process ID).
 - ```kill -9 <PID>``` Kill the running program.
 - ```wget <URL>``` Used to download the data.
 - ```ping <Domain/IP>``` Used to test the reachability of a host on an Internet Protocol network. 
 - ```vim <FileName>``` Text Editor
 - ```nano <FileName>``` Text Editor
 - ```alias <shorcutName>=<CurrentCommandName>``` Allows you to create keyboard shortcuts, or aliases, for commonly used commands.
