# Basic Shell Commands
The folder contains commands for navigating and for manipulating files.

## Description
This projection serves as an intoduction to shell

A shell is a user interface for access to an operating system's services. Most often the user interacts with the shell using a command-line interface (CLI). The terminal is a program that opens a graphical window and lets you interact with the shell.
### Objectives
At the end of the project I was able to explain the following
* What does RTFM mean?
* What is a Shebang
* What is the Shell
* What is the difference between a terminal and a shell
* What is the shell prompt
* How to use the history (the basics)
* What do the commands or built-ins cd, pwd, ls do
* How to navigate the filesystem
* What are the . and .. directories
* What is the working directory, how to print it and how to change it
* What is the root directory
* What is the home directory, and how to go there
* What is the difference between the root directory and the home directory of the user root
* What are the characteristics of hidden files and how to list them
* What does the command cd - do
* What do the commands ls, less, file do
* How do you use options and arguments with commands
* Understand the ls long format and how to display it
* What does the ln command do
* What do you find in the most common/important directories
* What is a symbolic link
* What is a hard link
* What is the difference between a hard link and a symbolic link
* What do the commands cp, mv, rm, mkdir do
* What are wildcards and how do they work
* How to use wildcards
* What do type, which, help, man commands do
* What are the different kinds of commands
* What is an alias
* When do you use the command help instead of man
* How to read a man page
* What are man page sections
* What are the section numbers for User commands, System calls and Library functions
* Keyboard Shortcuts for Bash
* Common shortcuts for Bash
* LTS

### Files 

- [File 0-current_working_directory](./0-current_working_directory) prints the current working directory.

- [File 1-listit](./1-listit) displays the contents list of the current directory.

- [File 2-bring_me_home](./2-bring_me_home) changes the working directory to the user’s home directory.

- [File 3-listfiles](./3-listfiles) displays current directory contents in a long format.

- [File 4-listmorefiles](./4-listmorefiles) displays current directory contents, including hidden files (starting with .).

- [File 5-listfilesdigitonly](./5-listfilesdigitonly) displays current directory contents in long format, with user and group IDs displayed numerically and hidden files.

- [File 6-firstdirectory](./6-firstdirectory) creates a script that creates a directory named holberton in the /tmp/ directory.

- [File 7-movethatfile](./7-movethatfile) moves the file betty from /tmp/ to /tmp/my_first_directory.

- [File 8-firstdelete](./8-firstdelete) deletes he file betty.

- [File 9-firstdirdeletion](./9-firstdirdeletion) deletes the directory my_first_directory that is in the /tmp directory.

- [File 10-back](./10-back) writes a script that changes the working directory to the previous one.

- [File 11-lists](./11-lists) writes a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

- [File 12-file_type](./12-file_type) writes a script that prints the type of the file named iamafile. 

- [File 13-symbolic_link](./13-symbolic_link) creates a symbolic link to /bin/ls, named __ls__. 

- [File 14-copy_html](./14-copy_html) creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

- [File 15-lets_move](./100-lets_move) creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

- [File 16-clean_emacs](./101-clean_emacs) creates a script that deletes all files in the current working directory that end with the character ~.

- [File 17-tree](./102-tree) creates a script that creates the directories welcome/, welcome/to/ and welcome/to/holberton in the current directory.

- [File 18-commas](./103-commas) writes a command that lists all the files and directories of the current directory, separated by commas (,).
