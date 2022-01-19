# Git-Commands


#for creating new repo 
git init
->it will create new rep and a The .git folder manages project's repo. 

#config
git config --global user.name "myname"
git config --global user.email "myemailid"

#Use To see in which branch I am  on. And also which files are in stageing 
git status

#for adding file
#files will go to staging state
git add filename   #it will filename file
git add . #it will add all new files

#for commit
git commit -m "message"

#to get list of all the commits made to a repository
git log

#to create new file in our local
touch filename

#for commit I changed the content of file,git diff,command showing what's differences I made in that file.
#No diff showing when I add(In staging)
git diff

#To know what changes in stage
#it will show same content like git diff before staging
git diff --staged

#to unstage the change
git restore --staged file.txt

#to see what are the branches available
git branch

#to create new branch
git branch branchname

#to switch from one branch to another
#it has same status as master branch(before no changes)
git switch branchname






