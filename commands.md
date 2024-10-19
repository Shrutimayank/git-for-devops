Basic Commands
Initialize a new repository:

git init
Clone an existing repository:


git clone <repository-url>
Configuration
Set your username:


git config --global user.name "Your Name"
Set your email:


git config --global user.email "your.email@example.com"
Staging and Committing
Stage changes:


git add <file>
Stage all changes:


git add .
Commit staged changes:


git commit -m "Your commit message"
Branching
Create a new branch:


git branch <branch-name>
Switch to a branch:


git checkout <branch-name>
Create and switch to a new branch:


git checkout -b <branch-name>
Viewing Changes
Show the status of the repository:


git status
View commit history:


git log
View changes between commits:


git diff
Remote Repositories
Add a remote repository:


git remote add origin <repository-url>
Push changes to a remote repository:


git push origin <branch-name>
Pull changes from a remote repository:


git pull origin <branch-name>
Undoing Changes
Unstage a file:


git reset <file>
Discard changes in a file:


git checkout -- <file>
Reset to the last commit (discard all changes):


git reset --hard HEAD
