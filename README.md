# Day 1
#Demo
First Day

#Update
Update 

#update 3
update 3 in vs

# Day 2
# Git Commands
1) git clone <url> : clone a repo
2) git add . : add your files to repo
3) git status : check status of the repo
4) git commit -m "Message" : commit your repo
5) git push origin main : push the repo to github

#Go back to the root folder to see another folder whose repo is created locally

# Branching commands
1) git branch : shows all the branches and the star indicates the current branch
2) git checkout -b <branch-name> : creates a new branch
3) git checkout <branch name> : switch in between branches
4) git diff <branch name> : shows the changes (in red color) while you are in main branch
5) git diff : shows the changes (in red color) while you are in new branch
6) q : to get out of unchnaged type in cmd
7) git branch -d <branch name> : delete a branch
8) git merge main : merge main to the current branch to stay updated with the status of main 
9) git push --set-upstream origin <branch-name> : to push a new branch

#Added this text while I am on the feature1 branch
#--set-upstream is same as -u

#a test for feature3 <git merge master>
#updating from feature3 the above test shows merge main is to merge main to the current branch to stay updated with the status of main
#now will push this updated lines in feature3 and pull from main

#added a new line on the same place of test for a merge conflict hence when i write <git merge main> it should display a conflict
#testing merge conflict

#yes got a conflict, accepted both changes and will move to the undoing git part

# Day 3
# Undoing in git

1) git reset : undoing a stage (undoing git add .)
just write git reset if you want specify a file name, can check using git status command

2) git reset HEAD~1 : undoing a commit
points to the previous commit and unstages the changes too

# Some more commands
1) git log : displays the log of commits
2) git reset <commit-hash-code> : takes back to that commit
3) git reset --hard <commit-hash-code> : erases the latest updates