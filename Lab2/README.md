# CPE 322 Lab 2
## Command Line

### Introduction
This lab aims to demonstrate basic usage of a computer through a command line interface. For this lab, I will be operating on an Ubuntu operating system through Windows Subsystem for Linux (WSL).

**Command 1:** `hostname`
This command is used to display the machine's hostname, which is how it identifies itself on a network.
(Lab2_img/hostname.png)

**Command 2:** `env`
This command when run as is displays the current environment. When called with certain flags these environment vairables can be rassigned.
(Lab2_img/env.png)

**Command 3:** `ps`
This command allows you to check actively running processes on your system.
(Lab2_img/ps.png)

**Command 4:** `pwd`
The pwd command outputs the current directory the user is interfacing in. 
(Lab2_img/pwd.png)

**Command 5:** `git clone`
This command copies a repository off of github to your machine. In this example I cloned the repository containing the labs for this class section.
(Lab2_img/git_clone.png)

**Command 6:** `cd <directory>`
The cd command changes what directory you are interfacing with in the command line. In this example I changed the working directory to the newly cloned iot folder.
(Lab2_img/cd.png)

**Command 7: ** `ls`
The ls command lists all files and subdirectories that are located in the current working directory, which in this example is the cloned iot repository.
(Lab2_img/ls.png)

**Command 8:** `cd`
Similar to when using the command previously, this command will change the working directory. However, when called with no subdirectory, it will move to the home directory.
(Lab2_img/cd_home.png)

**Command 9:** `df`
When run, this command displays the current data usage in the machine's file system. 
(Lab2_img/df.png)

**Command 10:** `mkdir <dir>`
This command when called creates a new subdirectory named by whatever you call with the command. In this example it is named "demo". We then move into this directory using the previously shown `cd` command.
(Lab2_img/mkdir.png)

**Command 11:** `nano <file>`
This command uses the built in nano editor to create and open a new file, named by whatever the flag sent with the command is. In this example I called it file and wrote a couple lines in it. I saved the file contents using Ctrl+S, then quit the file using Ctrl+X.
(Lab2_img/nano.png)

**Command 12:** `cat <file>`
Cat, short for concatenate, is an easy way of printing out a file(s) contents. In this case I called it with the newly written "file", where it displays the two lines written in in the console window.
(Lab2_img/cat.png)

**Command 13:** `cp <file> <newfile>`
The cp command copies the contents of file 1, and creates a new file with the given name from the second flag.

**Command 14:** `mv <file> <newfile>`
The mv command moves the file from the original location to the newly specified location. While this can be used to move it between directories, this can also be used to rename the same file. 

**Command 15:** `rm <file>`
The rm command removes the file from the system.
(Lab2_img/file_manip.png)

**Command 16: ** `clear`
The clear command erases command history in the terminal window without affecting any processes or locations.

**Command 17:** `man`
The man command is used to display the manual for common linux commands. In this case I opened the manual for the command "uname", which will be examined next.
(Lab2_img/man_uname.png)

**Command 18:** `uname`
The uname command displays information about the operating system and kernel. We are also calling it with the -a flag, which as learned from the previous command prints all known flags.
(Lab2_img/uname.png)

**Command 19:** `ifconfig`
The ifconfig command is a useful command for dispalying and modifying network information. In this example I did not have access to the tool initially, so I had to download the toolkit through the package manager apt.
(Lab2_img/ifconfig.png)

**Command 20:** `ping`
This command is used to test connectivity between two devices. In this command I call the ping command with the localhost, which verifies the network connectivity with my own machine. 
(Lab2_img/ping.png)

**Command 21:** `netstat`
This command displays various network statistics such as active protocols, addresses, and current connections.
(Lab2_img/netstat.png)


---
> "I pledge my Honor that I have abided by the Stevens Honor System." - George Mularadelis


