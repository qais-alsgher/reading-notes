# [The Command Line]([https://github.com/qais-alsgher/reading-notes/new/main/401](https://github.com/qais-alsgher/reading-notes/blob/main/401/The%20Command%20Line.md))

### 1.What is it

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on

the keyboard and feedback will be given to you similarly as text.

### 2.How does it work 

The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands

### 3.How do I get to one

- If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will

bring up Spotlight, then start typing Terminal and it will soon show up.

- If on Linux then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and

there may be an option 'Open in terminal'.

- If you are on Windows and intend to remotely log into another machine then you will need an SSH client. A rather good one is [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) (free) .

# Basic Navigation

Many tasks rely on being able to get to, or reference the correct location in the system. As such, this stuff really forms the foundation of being able to work effectively in 

Linux  and usually used this command line to get path. 

- pwd
Print Working Directory - ie. Where are we currently.

- ls
List the contents of a directory.

- cd
Change Directories - ie. move to another directory.

##### And we have two type for path 


1.Relative path
A file or directory location relative to where we currently are in the file system.

2.Absolute path

A file or directory location in relation to the root of the file system.

##### More on Paths

- ~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to 

the directory Documents with the path /home/ryan/Documents or ~/Documents

- . (dot) - This is a reference to your current directory. It could also be written as ./Documents (Normally this extra bit is

not required but in later sections we will see where it comes in handy).

- .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy.

eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.



# More About Files


The first thing should you know Everything is a file under Linux and it is an Extensionless System ,it is case sensitive.


common extensions for files:

- file.exe - an executable file, or program.
- file.txt - a plain text file.
- file.png, file.gif, file.jpg - an image.


# Manual Pages

The manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run 

them and what command line arguments they accept. Some of them are a little hard to get your head around but they are fairly consistent in their

structure so once you get the hang of it it's not too bad.


You invoke the manual pages with the following command:  man <command to look up>

It is possible to do a keyword search on the Manual pages with the following command:  man -k <search term>


# File Manipulation 

| File Manipulation      | files  |directories|
| ----------- | ----------- | ----------- |
|  make      | touch [options] <filename>       | mkdir [options] <Directory> |
| remove |   rm [options] <file>  (and used for non empty Directories)      | rmdir [options] <Directory> |
|copy |   cp [options] <source> <destination> | cp [options] <source> <destination> |
|move |   mv [options] <source> <destination> | mv [options] <source> <destination> |

[Useful reference](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

### For more information ([click here]([https://ryanstutorials.net/linuxtutorial/cheatsheet.php](https://github.com/qais-alsgher/reading-notes/blob/main/README.md)))



