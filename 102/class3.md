# Class 3 Reading Notes

## Git Tutorial

+ Terminal is for Mac.  Command Line is for Windows and Linux.
+ A Version Control System (VCS) is a program that tracks changes or various versions in a project by recording them at different snap shots.
+ A Distributed Version Control System (DVCS) prevents a server from being a single point of failure.  A DVCS uses multiple mirrored repositories, allowing multiple programmers to work in teams on different parts of the project.
+ Git is a DVCS that stores data files in snapshots.  A commit is when you save your work at a certain point.  Git can help you back track through changes when you are troubleshooting to find problem and also helps to prevent any major losses of data.
+ Customization and third party tools are available.

+ Files in Git have three main states: committed, modified and staged.

    >1. Committed - Data is securely stored in a local database
    >2. Modified - File has been changed but not committed to the database
    >3. Staged - Flagged a file’s changed version to be committed in the next snapshot

+ Getting Help - There are three ways to get more information on a particular command, by accessing the manual:

    >1. git help command
    >2. git command --help
    >3. man git-command

+ Cloning – allows you to create a copy of an existing Git repository copying all versions of all files for a project.  It will automatically retrieves for editing the latest version of the project.

+ The local Git repository has three components:

    >1. Working Directory: The actual files reside here.
    >2. Index: The area used for staging
    >3. Head: Points to the most recent commit

+ All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.
+ Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
+ Untracked files were not in the last snapshot and do not currently reside in the staging area.

## Commands for Git

*git status* – shows status of the file, like salt, use it all over

*git add filename* – tracks one file only

*git add* - tracks all files in a repository

*git commit -m “chanded cool thing”*  -- message to commit what you did and why

*git commit -a* commits a snapshot of all modifications to tracked files in the working directory

*git push origin master* – pushes changes from the local “master” branch to the remote repository named “origin”.

*git stash* – temporarily removes changes and hides them, giving you a clean directory

*git stash apply* – retrieves the hidden changes when you are ready to work with them again

*git push* is used to upload local repository content to a remote repository.

*git-sync* is used for syncing a personal fork with the upstream repository the personal fork was created from

**If you see red, you need to A-C-P  add, commit, push.**

**If you have a gituation, review the video for class 3 starting at 1:20:00.**

[Back to home](../README.md)
