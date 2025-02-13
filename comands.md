# Git Commands Guide

## 1. Initializing a Repository
```sh
git init
```

## 2. Checking Repository Status
```sh
git status
```

## 3. Adding Files to Staging Area
```sh
git add <file-name>
git add .  # Add all changes
```

## 4. Committing Changes
```sh
git commit -m "Commit message"
```

## 5. Viewing Commit History
```sh
git log
git log --oneline
```

## 6. Creating and Switching Branches
```sh
git branch <branch-name>
git checkout <branch-name>
git checkout -b <new-branch>
```

## 7. Merging Branches
```sh
git checkout master
git merge <branch-name>
```

## 8. Pushing Changes to Remote Repository
```sh
git push origin <branch-name>
```

## 9. Pulling Changes from Remote Repository
```sh
git pull origin <branch-name>
```

## 10. Cloning a Repository
```sh
git clone <repository-url>
```

## 11. Viewing Remote Repositories
```sh
git remote -v
```

## 12. Stashing Changes
```sh
git stash
git stash pop
```

## 13. Resetting Changes
```sh
git reset --soft HEAD~1  # Undo last commit but keep changes
git reset --hard HEAD~1  # Undo last commit and discard changes
```

## 14. Deleting Branches
```sh
git branch -d <branch-name>  # Delete local branch
git push origin --delete <branch-name>  # Delete remote branch
```

## 15. Checking Differences Between Files
```sh
git diff <file-name>
git diff --staged
```

