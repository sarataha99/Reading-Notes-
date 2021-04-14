
#  what's is GitHub?

* code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere. This tutorial teaches you GitHub essentials like repositories, branches, commits
![image](https://user-images.githubusercontent.com/82365206/114433178-2e743980-9bca-11eb-9013-919bb2d2e908.png)



# Git can be installed in three ways:

1- Install as a package

2- Install via another installer

3- Download and compile the source code.


# Git can be run in different operating system


1- Mac OS x
* Terminal

The simplest method for installing Git on a Mac (for Mavericks 10.9 and above) is running Git from the Terminal. If Git is not installed, you will see a prompt for installation.

Git Website

You can also download Git by visiting this link and following the posted directions:

http://git-scm.com/download/mac

GitHub

A third option is to install Git as part of the GitHub for Mac install. GitHub is repository hosting service, which we will discuss in a future section.

Download GitHub for Mac via the following link:

http://mac.github.com

![image](https://user-images.githubusercontent.com/82365206/114434931-3df48200-9bcc-11eb-9a12-2fe9be7b4db2.png)

2- windows
* Git Website

You can download Git by visiting this link and following the posted directions:

http://git-scm.com/download/win

GitHub

Install Git as part of the GitHub for Windows install.

http://windows.github.com

![image](https://user-images.githubusercontent.com/82365206/114435255-a5123680-9bcc-11eb-8daf-5358c12dcd8d.png)

3- linux
* Package Manager

You can try installing Git via your distribution’s inherent package management tool.

For Fedora:

$ sudo yum install git
For Ubuntu:

$ sudo apt-get install git
Git Website

To download Git for Linux, visit this link and follow the posted directions:

http://git-scm.com/download/linux

![image](https://user-images.githubusercontent.com/82365206/114435576-f9b5b180-9bcc-11eb-99f6-ff035d9de755.png)


# Workflow
* Local Repository Structure
The local Git repository has three components:

1- working Directory: The actual files reside here.

2- Index: The area used for staging

3- Head: Points to the most recent commit

# Saving Changes
* All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

1- Tracked

Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

2- Untracked

Untracked files were not in the last snapshot and do not currently reside in the staging area.

*After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.

