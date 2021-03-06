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

**pwd** outputs the current working directory  
**mkdir** creates a new directory in the working directory  
**rm -r** deletes a directory and all of it's child directories  
**touch** sample creates a file in the working directory named sample  
**rm** deletes a file  
**mv** moves or renames a file  
**ls -a** lists all of the contents including hidden files and directories  
**cp** copies files  
**cat** outputs the contents of a file to the terminal  
**sort** orders the input alphabetically  

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

**ls** lists all files and directories in the working directory  
**ls -a** lists all contents, including hidden files and directories  
**ls -l** shows file or directory, size, modified date and time, file or folder name and owner of file and its permission  
**ls -lh** modifies the format of the file size (human readable) of the **ls -l** command  
**ls -lah** includes a hidden files and directories to the **ls -lh** command  
**ls	-t** order files and directories by the time they were last modified  
**ls -Glp** long listing format with no group names and appended “/” indicator to the directories  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

**ls -d** displays only directories  
**ls -R** displays subdirectories as well  
**ls -r** displays files in reverse order  
**ls -t** displays newest file first  
**ls -x** displays files as rows across the screen  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

The **xargs** command line utility for building an execution pipeline from standard input. Using **xargs** allows tools like **echo** and **rm** and **mkdir** to accept standard input as arguments.  

echo 'first second third' | xargs mkdir  

 

