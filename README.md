# main
## sub
___
![](gitcode.png)
```bash
#  Git Setup
git --version
git config --global user.name "Your Name"
git config --global user.email "you@email.com"

#  Initialize / Clone
git init
git clone <repository_url>

# Check Status & History
git status
git log --oneline

#  Add & Commit
git add .
git commit -m "Initial commit"

#  Branching
git branch
git checkout -b new-branch
git merge branch-name

#  Remote Operations
git remote add origin <repo_url>
git push origin main
git pull origin main

#  Undo Changes
git restore file.py
git restore --staged file.py
git reset --soft HEAD~1

#  Stash
git stash
git stash apply

#  Delete
git branch -d branch-name
git rm file.py