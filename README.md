# git.txt

GIT CONFIG 
git config --global user.name "Maria Rafalovich"
git config --global user.email "rafalovich.mariya@gmail.com"
to check  - git config --list

INIT PROJECT
- go to your localhost project folder  with terminal
- git init 
- git remote add origin <YOUR BITBUCKET PROJECT>
- git status
- git add . 
- git status
- git commit -m "first comment"
- git status
- git push --set-upstream origin master 
- git push 


FOR EVERY FUTURE CHANGES
- git status 
- git add.
- git commit -m "I've changed ......"
- git push

Alert
https://www.feednotifier.com

FOR GET CHANGES FROM THE SERVER 
-git pull

FOR CLONE THE ENTIRE PROJECT 
git clone <YOUR BITBUCKET PROJECT>

TO IGNORE FILE TO UPDATE
we need create a file .gitignore with: *.gif *.jpg *.ico *.txt
