# Getting started with git:
#### Installing Git:

+ First one we going to install Git.
+ This link may be hellp us. Visit https://git-scm.com/downloads
+ After installation we are going to follow These commands

#### Running our first Git command:

+ First we are going to create an account, then git know that who operate me.
```
1. git config --global user.name "Salman"
2. git config --global user.email “Salman@gmail.com”
```
+ Second we create a empty Folder and open it.
+ Then press the right click button and select **Git Bash Here** in your empty folder.
+ You see that one windows file open in pc screen, it's look like a cmmand prompt.
+ So we are ready to use Git(version control system).

+ First we write a command.
```
 - Git init 
```
+ Second we create a file useing git commands 
```
- echo "your contant" >> file.txt
```
+ Know we are going to **Add** a file who untrack.
```
1. git add file.txt
2. git add -A
3. git add .
4. git --All
```
+ So we are going to make a file to the part of repository.
```
1. git commit -m "First commit"
2. git commit
```
#### Viewing the history:
 
+ If we write and use this command, it's tell you files are untrack or   modified.
```
1. git status
2. git log 
```
#### The staging area:

 The staging area or index is a virtual place that collects all the 
 files you want to include in the next commit.

#### Unstaging a file:

+ Be sure to be in a clean state by typing `git status`.
+ Create a new file `touch NewFile.txt`.
+ Using `git status` again, verify that `NewFile.txt` is untracked.
+ Use the `git add NewFile.txt` command and go on.
+ Use the suggested `git reset HEAD <file name>` or `git rm --cached`    command to back the file in the untracked status.








