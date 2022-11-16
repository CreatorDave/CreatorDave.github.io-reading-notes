# Git Intro

### Version Control

Local version control is one database on your hard disk that stores changes to files. Centralized Version Control System is a single server storing all changes and file version, which can be accessed by various clients. Distributed Version Control systems addresses the server going down by having multiple servers.

Git is a DVCS that stores data in a file system that is made up of snapshots. When you commit or save a changed Git creates a snapshot of the file and stores a reference to it.

### History of GIT

Git started out of Linux kernal. Linus Torvalds began creating Git soon after this. Git allows for non-linear development via mutiple branches, supports large projects, has strong mechanisms for preventing corruption, and a simple design.

### Let's Start

Git can be installed in three ways:

1. Install as a package
2. Install via another installer
3. Downlaod and compile the source code.

You can install Git on MacOS, Windows, and Linux

### Git Repository

1. Switch to the project's directory

- cd newdirectory
- git init
- git add
- git commit -m "why you made the change"
- git clone <https://github.com/test>

### Workflow

Local Git repository has three components: 1. Working directory: the files reside here. 2. Index: the area used for staging. 3. Head: Points to the most recent commit.

### Remote Repositories

By running *git remote* you can view the short names of remote handles

### Undoing Actions

- got commit --amend
- git reset HEAD

### Branching

Branching allows multiple users to work simultaneously via multiple branches without affecting the main repository.

### Merging

- git merge

### Rebasing

an alternative to merging is rebasing.

- git checkout test
- git rebase master

### Log

To view committed snapshots use *git log*

### Tagging

- git tag

### Github

Many open source projects are used by GitHub due to the integrated-manager workflow that allows for the largest existing host for Git repositories.

[Back Home](../reading-notes/README.md)
