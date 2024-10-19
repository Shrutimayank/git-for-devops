Basic Commands
Initialize a new repository:
bash

git init
Clone an existing repository:
bash

git clone <repository-url>
Configuration
Set your username:
bash

git config --global user.name "Your Name"
Set your email:
bash

git config --global user.email "your.email@example.com"
Staging and Committing
Stage changes:
bash

git add <file>
Stage all changes:
bash

git add .
Commit staged changes:
bash

git commit -m "Your commit message"
Branching
Create a new branch:
bash

git branch <branch-name>
Switch to a branch:
bash

git checkout <branch-name>
Create and switch to a new branch:
bash

git checkout -b <branch-name>
Viewing Changes
Show the status of the repository:
bash

git status
View commit history:
bash

git log
View changes between commits:
bash

git diff
Remote Repositories
Add a remote repository:
bash

git remote add origin <repository-url>
Push changes to a remote repository:
bash

git push origin <branch-name>
Pull changes from a remote repository:
bash

git pull origin <branch-name>
Undoing Changes
Unstage a file:
bash

git reset <file>
Discard changes in a file:
bash

git checkout -- <file>
Reset to the last commit (discard all changes):
bash

git reset --hard HEAD
