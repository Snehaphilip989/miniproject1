# List Of GIT Basic Commands

## Repository 

Git repository is just a folder or a file location where you have all the project files stored.To store information in a git, it stores in the data structure which is called a repository. It is a .git/ folder inside a project . It tracks all the changes made to the file in a project. 

Git repository is a general term used and you usually work with 2 repositories: Local and Remote repository.

**Local Repository:** This is where you store your files and codes in a folder(s) on your local machine. When you commit any file or code, a new version of that file gets created inside the folder in your local system.

**Remote Repository:** A remote repository is present in a remote location and not on your local computer. An example of remote repository is GitHub where you can store all your files and codes directly on the GitHub server.

The files present in the remote repository can be imported on to your local system and the files on your local git repository can be pushed on to remote git repository.


## Clone 

git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository. git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location. The original repository can be located on the local file system or on remote machine accessible supported protocols. The git clone command copies an existing Git repository.

To create a working copy of the local repository, we use git clone. We use git clone command to clone a repository and bring all the files to the local machine. We can make changes in the cloned repository locally and the changed one can be pushed to the upstream directly. 

## Fork  

Fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project. Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea. 

To create a copy of the repository, we use fork. Unlike clone, fork doesnt allow us to work with repository on the local machine, rather it remains in the github itself. It allows to freely experiment with changes without affecting the original project. We use fork to either propose changes to someone else' project or to use someone else' project as a starting point. 

## Branch 

The "branch" command helps you create, delete, and list branches. 
It's the go-to command when it comes to managing any aspect of your branches - no matter if in your local repository or on your remotes.

A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master. As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically.

## Commit 

The git commit command is used to capture a snapshot of the project's currently staged changes. 
Committed snapshots are safe versions of a project and git will never change them unless you explicitly ask it to. 

The git commit command records a bunch of file changes in the local repository and calculates a hash that can serve as a tag for this bunch of file changes. These commits can later be pushed to a remote repository, merged from a remote repository, or cherrypicked to another branch.

![Image of Commit](https://github.com/Snehaphilip989/miniproject1/blob/master/Image/Commit.PNG)

## Merge 

Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.

Git merge will combine multiple sequences of commits into one unified history. Merge commits are unique against other commits in the fact that they have two parent commits. When creating a merge commit Git will attempt to auto magically merge the separate histories for you. If Git encounters a piece of data that is changed in both histories it will be unable to automatically combine them. This scenario is a version control conflict and Git will need user intervention to continue. 

## Checkout 

The git checkout command lets you navigate between the branches created by git branch.The git checkout command operates upon three distinct entities: files, commits, and branches. 

Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.

## Push  

The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repository. Remote branches are configured using the git remote command. Pushing has the potential to overwrite changes; caution should be taken when pushing.

Push the specified branch to <remote>,along with all of the necessary commits and internal objects. This creates a local branch in the destination repository. To prevent you from overwriting commits, Git won’t let you push when it results in a non-fast-forward merge in the destination repository.


## Pull 

The git pull command is used to fetch and merge remote changes. git pull is a Git command used to update the local version of a repository from a remote. It is one of the four commands that prompt network interaction by Git. By default, git pull does two things.

-  Updates the current local working branch (currently checked out branch)

-  Updates the remote tracking branches for all other branches.


![Image of Pull](https://github.com/Snehaphilip989/miniproject1/blob/master/Image/pull.PNG)

## Remote Add / Remove / Show

The "remote" command helps you to manage connections to remote repositories.
It allows you to show which remotes are currently connected, but also to add new connections or remove existing ones.

**-v**

Shows URLs of remote repositories when listing your current remote connections. By default, listing remote repositories only shows you their shortnames (e.g. "origin"). Using the "-v" option, you will also see the remote's URLs in listings.

**add ```<shortname> <url>```**
  
Creates a new connection to a remote repository. The "shortname" you provide can later be used instead of the URL when referencing the remote. A typical default shortname is "origin": this is used for the remote which your local repository was cloned from.

**remove ```<name>```**
  
Disconnects the remote from the local repository. This will have no effect on the actual remote repository (i.e. the repository itself is not removed / deleted / etc.).


## Status

The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. Status output does not show you any information regarding the committed project history.

## Master Branch

A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master . As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically.

## Sources 

1.  [Basic Commands for Git](https://www.hostinger.com/tutorials/basic-git-commands)
