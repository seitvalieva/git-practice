This repository was created for practicing working with git commands from the command line interface
https://www.youtube.com/watch?v=8Udwdb2Mbd4

git init 
    to initialize your local repository as a git repository
git add .
    to stage all changes in all files
git commit -m "first commit"
    to commit the staged files and changes
git status
    
git log
    to review the history of commits
git diff 7435 c286d7
    to view the difference between 2 commits
Q
    to exit history

git remote add origin https://github.com/seitvalieva/git-practice.git
    to connect your local repo with the remote one

git config --global user.name "github_username"
git config --global user.email "your_email_on_github"

git push -u origin master
    to push/send commited changes from your local repo to remote one

git pull
    to download changes from remote repo to local one

git branch
    to display all available branches

git branch branch_name
    to create a new branch 

git checkout branch_name    // example: git checkout master
    to switch to another branch
