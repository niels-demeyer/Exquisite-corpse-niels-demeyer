# Exquisite-corpse-niels-demeyer

git collage

# Git Cheat Sheet

## Basic Commands

- `git init`: Initialize a new Git repository
- `git status`: Check the status of your repository
- `git add .`: Add all new and changed files to the staging area
- `git commit -m "Commit message"`: Commit changes
- `git push`: Push changes to a remote repository
- `git pull`: Update local repository to the newest commit

## Branching

- `git branch`: List all local branches
- `git branch branch-name`: Create a new branch
- `git checkout branch-name`: Switch to a branch
- `git merge branch-name`: Merge a branch into the active branch

## Stashing

- `git stash`: Stash changes in a dirty working directory
- `git stash apply`: Apply changes from a stash

## Remote Repositories

- `git clone url`: Clone a remote repository
- `git remote -v`: List all remote repositories
- `git remote add origin url`: Add a remote repository

## Undoing Changes

- `git revert SHA`: Revert a commit by creating a new commit with opposite changes
- `git reset --hard SHA`: Discard all history and changes back to the specified commit

Remember to replace `SHA` with your commit hash and `branch-name` with your branch name.
