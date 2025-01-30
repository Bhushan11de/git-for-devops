Git Commands Guide
1. Setup and Configuration
Initialize a new Git repository:

git init

Set user name:

git config --global user.name "Your Name"

Set user email:

git config --global user.email "youremail@example.com"

2. Creating and Managing Repositories
Clone an existing repository:

git clone <repository-url>

Check the status of the repository:

git status

3. Working with Files
Add files to staging:

git add <file-name>

Add all files to staging:

git add .

Commit changes:

git commit -m "Commit message"

4. Branching and Merging
Create a new branch:

git branch <branch-name>

Switch to a branch:

git checkout <branch-name>

Create and switch to a branch:

git checkout -b <branch-name>

Merge a branch:

git merge <branch-name>

5. Remote Repositories
Add a remote repository:

git remote add origin <repository-url>

Push changes to the remote repository:

git push origin <branch-name>

Pull changes from the remote repository:

git pull origin <branch-name>

6. Viewing History and Logs
View commit history:

git log

View a summary of changes:

git log --oneline

7. Stashing Changes
Stash changes:

git stash

Apply stashed changes:

git stash apply

8. Undoing Changes
Unstage a file:

git reset <file-name>

Revert a commit:

git revert <commit-hash>

Reset to a previous commit:

git reset --hard <commit-hash>

9. Miscellaneous
Show changes:

git diff

Remove a file from Git:

git rm <file-name>

Show commit details:

git show <commit-hash>
