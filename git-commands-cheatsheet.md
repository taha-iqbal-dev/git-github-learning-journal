# Git Command Cheatsheet

## Repository

```bash
git init
git clone
git status
git log
git log --oneline
git log --graph --all
```


## Staging

```bash
git add .
git add filename
git restore --staged file
```


## Commits

```bash
git commit -m ""
git commit -a -m ""
git commit --amend
```


## Undo

```bash
git checkout file
git restore file
git reset HEAD file
git revert HEAD
```


## Branches

```bash
git branch
git branch new-branch
git checkout branch
git checkout -b branch
git merge branch
git branch -d branch
git branch -D branch
```


## Remotes

```bash
git remote -v
git remote show origin
git remote get-url origin
git fetch origin
git pull origin main
git push origin main
git push origin feature-branch
```


## Rebase

```bash
git rebase main
git rebase --continue
git rebase --abort
```


## SSH

```bash
ssh-keygen
ssh -T git@github.com
```


## Helpful

```bash
git diff
git show
git stash
git stash pop
git tag
git blame
git clean -fd
```