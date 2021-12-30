# Terminal & Github cheatsheet

## Terminal basic commands

`cd folderName`: is used to navigate to the folder

`cd ..`: go back

`cd -`: go back to the previous

`ls`: is used to list all items in a folder

`ls-la`: is used to list all items in a folder with details

`pwd`: is used to print the current working directory to know where we are in the folder structure

`mkdir`: create new dirctory 

`touch`: create new file

`code .`: create new file

`npx create-react-app my-app `: create new **react project**

## Github basics

**Fork**
to fork any repository, you just have to click on the right side button that has the `FORK` label on it, and you should double check that you forked by checking the user name in the link if it has your username.

## Git terminal basic commands

`git clon SSH`: is used to clone a repository given a specific link

`git status`: is used after every git command we do to get the status of the git repository

`git add .`: is the first step to be able to commit and push a git repository. We should add all file in the working directory to **staging** status by using the `git sataus` notation

`git commit -m "message"`: is used to **commit** the files, and save their history. You can only use this command if you have staged the files using the `git add` command.

`git push`: is used to **push** the files if you are authorized to push.

> **COMMON MISTAKE!**
> If you didn't fork a repo, and you cloned it and you tried to push, it will not let you push, because you don't own the repo.
