*git config
Usage: git config (–global) user.name “[username]”  
Usage: git config (–global) user.email “[email address]”  

This command sets the author name and email address respectively to be used with your commits.
NB: -global is optional and without -global, it sets author name and email for specific repository.


*git init

Usage: git init [repository name]
This command is used to start or create a new repository.


*git remote

Usage: git remote add [remote name] [Remote Server Link]  
This command is used to connect your local repository to the remote server.
NB: variable name commonly used as [origin] and remote server link is your [repository url]

Usage: git remote -v
This command list all remote server you are connected to

Usage: git remote remove [remote name]
This command list all remote server you are connected to
NB: remote name can be [upstream]


*git clone

Usage: git clone [url]  
This command is used to download a repository from an existing URL to local directory.
NB: url should look like this <https://github.com/username/repository_name.git>


*git add

Usage: git add [file]  
This command adds a file to the staging area.

Usage: git add *  
This command adds one or more to the staging area.


*git commit

Usage: git commit -m “[ Type in the commit message]”  
This command records or snapshots the file permanently in the version history.

Usage: git commit -a  
This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

Usage: git commit -am  “[ Type in the commit message]”
This command does the same as git commit -a but also enables you to type a descriptive message.


*git rm

Usage: git rm [filename.ext]  
This command deletes the file from your working directory and stages the deletion.


*git push

Usage: git push -u [variable name] main  
This command sends the committed changes from your working directory main branch to your remote repository.
NB: -u set your current branch to default and when next you push a file just use [git push]
variable name commonly used as origin

Usage: git push –all [variable name]  
This command pushes all branches to your remote repository.

Usage: git push [variable name] :[branch name]  
This command deletes a branch on your remote repository.


*git pull

Usage: git pull [Repository Link]  
This command fetches and merges changes on the remote server to your working directory.


*git branch

Usage: git branch  
This command lists all the local branches in the current repository.

Usage: git branch [branch name]  
This command creates a new branch.

Usage: git branch -d [branch name]  
This command deletes the feature branch from command line.

Usage: git push origin --delete [branch name]
This command deletes the feature branch from github directly


*git checkout

Usage: git checkout [branch name]
This command is used to switch from one branch to another.

Usage: git checkout -b [branch name]  
This command creates a new branch and also switches to it.


*git merge

Usage: git merge [branch name]
This command merges the specified branch’s history into the current branch.


*git diff

Usage: git diff  
This command shows the file differences which are not yet staged.

Usage: git diff –staged 
This command shows the differences between the files in the staging area and the latest version present.

Usage: git diff [first branch] [second branch]
This command shows the differences between the two branches mentioned.


*git status

Usage: git status  
This command lists all the files that is yet to be committed.


*git log

Usage: git log  
This command is used to list the version history for the current branch.

Usage: git log –follow [filename]
This command lists version history for a file, including the renaming of files also.


*git show

Usage: git show [commit]
This command shows the metadata and content changes of the specified commit.


*git tag

Usage: git tag [commitID]  
This command is used to give tags to the specified commit.


*git reset

Usage: git reset [filename]
This command unstages the file, but it preserves the file contents.

Usage: git reset [commitID]
This command undo all the commits after the specified commit and preserves the changes locally.

Usage: git reset –hard [commitID]
This command discards all history and goes back to the specified commit.\
