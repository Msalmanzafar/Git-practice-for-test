
# Getting started with git:
#### Installing Git:

+ First one we going to install Git.
+ This link may be hellp us. Visit https://git-scm.com/downloads
+ After installation we are going to follow These commands

#### Running our first Git command:

+ First we are going to create an account, then git know that who operate me.
    ```
    − git config --global user.name "Salman",
    − git config --global user.email “Salman@gmail.com”
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
- echo "you contant" >> file.txt
```
+ Know we are going to *Add* a file who untrack.
```
1. git add file.txt
2. git add -A
3. git add .
4. git --All
```
+ So we are going to make a file to the part of repository.
```
- git commit -m "First commit"
- git commit
```
+ If we write and use this command, it's tell you files are untrack or modified.
```
- git status 
```
