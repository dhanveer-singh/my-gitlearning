## What is Git?
- Git is an **open source, distributed version control system** that helps developers collaborate on projects of any scale.
- Git is version-control system for tracking changes in source code during software development.
- Its goal is to increase efficiency, speed and easily manage large projects through version controlling.
- Linus Torvalds, the developer of the Linux kernel, created Git in 2005 to help control the Linux kernel's development.


## What is Git Bash?
- Git Bash is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience.
- Bash is an acronym for Bourne Again Shell.
- A shell is a terminal application used to interface with an operating system through written commands.
- Bash is a popular default shell on Linux and macOS.
- Git Bash is a package that installs Bash, some common bash utilities, and Git on a Windows operating system.

## Git - Environment Setup
- [Download Git from here](https://git-scm.com/)

### Launch Git Bash after installation.

- To open Git bash in working folder simply `right click` inside that folder then select `Git bash here`.
- Check version in Git Bash: `$ git --version`

### Getting Started - First-Time Git Setup
Now that you have Git on your system, you’ll want to do a few things to customize your Git environment. You should have to do these things only once on any given computer.


### Add or delete a record from Git config
The first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating:

Set your user name and email address.

    $ git config --global user.name "Your Name" 
    $ git config --global user.email "your@email.com" 

Remove your user name and email address.
   
    $ git config --global --unset user.name
    $ git config --global --unset user.email

If you want to check your configuration settings, you can use the `git config --list` command to list all the settings Git can find at that point.

## Initialise Git in your project
If you have a project directory that is currently not under version control and you want to start controlling it with Git, you first need to open Git Bash inside your project's directory. And Type below command:

    $ git init
This creates a new sub-directory named .git that contains all of your necessary repository files. At this point, nothing in your project is tracked yet.

## Start tracking your project
If you want to start version-controlling existing files, you should probably begin tracking. You can accomplish that with a few git commands that specify the files you want to track.

### Git add (Tracking Files)
To add a file as it looks new to your next commit (stage) type below command:

    $ git add <file>

To add all files to the repository type below command:

    $ git add --a

At this point you have added single or all files (as per command entered) in staging area. To check
the status of staging area just type: 
    
    $ git status
### Add More Files
In order to begin tracking a new file, you use the command `git add`. Let's say, you have a new README file. 
To begin tracking the README file, you can run this:

    $ git add README
If you run your status command again, you can see that your README file is now tracked and staged to be committed.

### Remove Files
To Remove or untrack added file from staging-area just type below command:

    $ git rm --cached <filename>
To Remove or Delete file from working directory:

    $ git rm <filename>
## Git commit (Committing Your Changes)
    
    $ git commit -m "message"

- The above command will make a commit with the given commit message. 
- The commit command will commit the changes and generate a commit-id.

## Git diff (Compare changes)
    $ git diff
Above command will compare changes between the staging area and the working directory. Also if you want to
compare changes between the staging area and against the previous commit just type bleow command:
    
    $ git diff --staged
    
 ## git push
The git push command is used to upload local repository content to a remote repository.

    $ git branch -M main
    $ git remote add origin git@github.com:[user name]/[repo name].git
    $ git push -u origin main

## git pull
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. 

    $ git clone https://github.com/[user name]/[repo name]

## git clone
git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.

    $ git clone https://github.com/[user name]/[repo name]


## Useful links
- [Git Books](https://git-scm.com/book/en/v2)
- [Tool for Explaining Git Commands](https://explainshell.com/)
