## Remote acsess from GitHub repository

To add a new repository from GitHub use command: **git clone _link_from_GitHub_from_button_CODE_**. 

Command **cd folderNameFromGitHub_** switch you to the remote repository.

Command **git remote add orogin _linkInGitHub_** connects new local repository with a remote one. After this command do **git branch -M main** in order to assign main brunch.

To send changes at first time in local reporitory to the remote one use command **git push -u origin main**. After that just use command **git push**. 

To download data from remote repository and merge it with local one use command **git pull**. 

## Pull request

1. Mare **fork** of repository of interest at GitHub
2. Command _git clone_ of our version on this reporitory
3.  Create a new branch where you will add new data
4.  Do **git push** to send new data to your GitHub account
5.  On GitHub press _pull request_ button. 