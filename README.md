
How to use GitHub in the Terminal
=================================

This tutorial assumes you have GIT installed and you have familisarised yourself with creating a repo on GitHub.

**List of basic commands:**  

**git status** - gives you a status, literally, anything bad will tell you!
**git clone** - (followed by the https://etc) use this to grab the URLs off GitHub to copy the folders from GitHub onto your local machine  
**git checkout** (followed by name of a branch) - use this to switch or create a branch on the terminal/command line  
**git commit** - m "description here" - use this to commit changes you have made and to add a description  
**git add** - to add files, do this before using the commiting command  
**git push** - pretty much what it says on the tin, pushes everything you have done back to the repository  
**git merge** - use git checkout to enter the master branch or whatever, use this command to merge changes you have been working on to add into the current branch you are in  


# How to make clones, check status, commiting and pushing without making a new branch. (STAGE 1, we will get to merging later.)

Step 1
------
* Go to the folder where you want your repo to be on your computer
* I assume you have created a repo on GitHub.com? If not, go to it. Then come back to here, grab the URL of your repo, then you can start creating branches on here.  

Step 2
------
* Once inside the folder you want to be in, type in git clone https://github.com/YOUR-USERNAME/name-of-repo-here  
* This will essentially copy what is on the repo onto your local machine.  

Step 3
------
* Make some changes!  

Step 4
------
* Now you have made some changes you can see where you stand with what changes you have made by typing in git status  
* This will show what files have been modified and need to be added in order to be pushed back up into the repo.  
* Type in git add [name of page you have changed] then hit return  
* It is of good practice to leave messages to see what commits you have made in the past so other members of your team or outsiders can see what changes have been made (version control!!) so type in git commit -m "type in a description here" - this also locks changes into the rep  
* Finally you need to push the changes you have made on your local and push it back to GitHub by simply pressing git push  

Step 5 
------ 
**Done!**

How to merge one branch with another
=================================

When you have finished working on a branch ie a 'develop' branch, you will want to merge the changes you have done to the master branch, this is relatively simple.  

Step 1
------

* Checkout to the branch that will receive the merge - git checkout master  

Step 2
------
* Type in the command git merge [then type in here the name of the branch that you were working in]  

Step 3
------
* Hit return and the changes made in 'develop' will be merged with the master  

Step 4
------
* All you have to do now is do a git push to push the code into GitHub.com!  

How to delete branches locally and remotely
==============================

* Use the command git branch -d [name of branch] to delete a branch you have made locally  
* If you want to delete a branch locally and remotely use the command git push origin -- delete [name of branch]  






