# Git Branching

Git branches allow developers to work on different features independently without affecting the main project.

## Concepts

- Create branches
- Switch branches
- Delete branches
- Feature branches
- Branch workflow

Branching enables parallel development and safer experimentation.

# Branching Commands

## List Branches

```bash
git branch
```

Displays all local branches.


## Create Branch

```bash
git branch feature-login
```

Creates a new branch.


## Switch Branch

```bash
git checkout feature-login
```

or

```bash
git switch feature-login
```

Moves to another branch.


## Create and Switch

```bash
git checkout -b feature-login
```

Creates and switches in one command.


## Delete Branch

```bash
git branch -d feature-login
```

Deletes a merged branch.


## Force Delete

```bash
git branch -D feature-login
```

Deletes regardless of merge status.


## View Branch Graph

```bash
git log --graph --oneline --all
```

Displays commit tree.