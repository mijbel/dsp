# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

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

> > pwd
> > mkdir directory
> > rm -r directory
> > touch filename
> > rm filename
> > mv oldfilename newfilename
> > ls -a
> > mv filename folder
> > nano filename
> > sort filename

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

> > listing
> > listing all files (inc. hidden)
> > listing long form 
> > listing long form with filesize in KB
> > listing all files (inc. hidden) long form with filesize in KB
> > listing files sorted by time modified
> > listing files long form with colorized output and add a / after directories
---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -R to display subdirectories
> > ls -m to display names as a comma-separated list
> > ls -r to display files in reverse order
> > ls -u to display files by access time
> > ls -d displays only directories

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > used to build and execute command lines from standard input. e.g., find /path -type f -print | xargs rm

 

