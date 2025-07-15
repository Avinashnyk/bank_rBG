right click in the folder and then select git bash





**git init** - for initialization 

right click and open git bash

touch filename.java - to create a file

vim filename.java - open a file 

escape then type "**:wq!**" to exit from the file.

without creating the file with the command touch , we can directly create file with content using vim command.



process of sending the local file to GitHub:

local file from the laptop -> unstage/untracked -> stage/ready to move ->hub



git status = gives the untracking files

**git add .** = push the files to unstage - untrack to track

**git add \*** = push the files to unstage - untrack to track

git add -A = push the files to unstage - untrack to track





**git commit -m "adding files"** - pushes to stage



stage to hub - remote setup - only once . if we want to add more files we can directly add more files without remote setup

&nbsp;

**git remote add origin linkfromgithub**



**git push-u origin master** = to push the files to GitHub.



Task: create a new repository and push files to GitHub



ls - list all files in local repository



even if there is a modification in the file also , need to " add, commit and push " the file again.



&nbsp;

