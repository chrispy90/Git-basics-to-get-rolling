# Time to get rolling with some basics on Git

## Navigating around and working with your system files 

Command | Function
------- | --------
```ls```| Lists everything in the current directory
```cd```| Change directory
```..cd```| Move one directory up
```mkdir```| Makes a new directory
```rmdir```| Deletes a directory
```touch```| Makes a new file
```mv```| Move/ rename a file
```rm```| Deletes a file
```echo Hello World >> "hello.txt"```| Creates a text file and pipes your text into it
*some command* ``` \| clip``` | Copies the output of the preceeding tool to the clipboard


## Basic commands to make things run smoothly  
Set user name

```
git config --global user.name "Your user name"
```

Set line ending
```
git config --global core.autocrlf true
git config --global.core.safecrlf true
```

## Git Commands

Command | Function
------- | --------
```gitk``` | Opens the GUI for Git
```git init``` | Creates a local repository
```git clone```*path to repo* | Makes a copy of a remote repository on your local machine
```git pull``` | Update the local repository (same as running ```git fetch``` & then ```git merge```)
```git add``` *full name of file* | Add a file in the working directory to the index (stage)
```git add *``` | Add all the files in the working directory to the index (stage)
```git commit -m "message"```| Moves the staged files to the head of the local repository
```git push```| Update the remote repo with your local repository
```git status``` | Notifies user if working directory has changes that have not been commited
```git diff``` | Look at the differences between two branchs
```git log``` | Shows you the commit history for the repository

## Online guides explaining Git

* [GitHub Help Docs](https://help.github.com/)
* [Pro Git book](https://git-scm.com/book/en/v2)
* [Simple Git overview](http://rogerdudler.github.io/git-guide/)
* [Git Immersion](http://gitimmersion.com/lab_01.html)

