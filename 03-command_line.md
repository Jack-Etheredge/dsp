# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > * `ls` # shows current working directory path
> > * `mkdir` # creating a directory
> > * `rm` # deleting a directory
> > * `touch <filename>` # creating a file using `touch` command
> > * `rm <filename>` # deleting a file
> > * `mv <old-filename> <new-filename>` # renaming a file
> > * `ls -a` # listing hidden files
> > * `cp <filename> <new-location>` # copying a file from one directory to another
> > * `echo <command or variable name>` # print the output of a command without running it or return the value of a variable 
> > * `$variable <value>` # assign a value to a variable name (in this case '$variable')

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > * `ls` # lists files in current directory  
> > * `ls -a`  # Displays all files (even hidden ones) 
> > * `ls -l`  # Displays the long format listing (details) 
> > * `ls -lh`  # show details and print file sizes in human readable format 
> > * `ls -lah` #  show details of all files (including hidden ones) and print file sizes in human readable format
> > * `ls -t` # sort the list of files by modification time 
> > * `ls -Glp` # Displays the long format listing (details) without group name, Displays directories with /  


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > * `ls -R` # recursively list subdirectories
> > * `ls -d` # Displays only directories.
> > * `ls -u` # Displays files sorted by the file access time.
> > * `ls -g` # Displays the long format listing, but exclude the owner name.
> > * `ls -S` # Sort by file size

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > `xargs` works sort of like pipe (`|`). It can also parallel process jobs. Additionally, it is a way to avoid a "too many arguments" error possible from passing the output of one command into another command. It executes commands once for each input line/argument and defaults to `echo` if no command is specified. I still don't understand `xargs` super well.  
>> find -name "*.txt" | xargs grep "blah" # This will use grep to search the .txt files in the directory for "blah".

 

