# [GIT INTRO](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
___
*Version Control* is a system where you can revisit multiple versions of a set of files by recording the changes.
* Local Version Control
* Centralized Version Control
* Distributed Version Control

### GIT
*Git* is a DVCS (Distributed Version Control System) that stores data in snapshots.
* Utilizes local operations
* Good at tracking changes and detecting file corruption
* Minimizes the loss of data 
* Files in Git are in 3 main states
1. Committed
2. Modified
3. Staged

### INSTALL (Mac OS x & Windows)
* [GIT](http://git-scm.com/download/mac)
* [GITHUB](http://mac.github.com)
* [Here](https://git-scm.com/downloads/guis) is a list of accessible GUI (Graphical User Interface) clients for Git
* Use Vim, default text order or configure your own. 
* Check Settings // git config --list

### GIT REPOSITORY
1. Switch to target project directory // $ cd test (cd = change directory)
2. Use // $ git init
3. To track the repository files // 
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”

### CLONING
Create copies of existing Git repositories

$ git clone https://github.com/test

If you want to change the name, add your new directory name at the end of the command. 
$ git clone https://github.com/test mydirectory

### LOCAL REPOSITORY STRUCTIRE
1. **Working Directory**: where the files reside
2. **Index**: staging area
3. **Head**: Points to recent commit

[<==Return to Home](README.md)


