# Git Merging

Git merge combines changes from one branch into another.

Most commonly:

Feature Branch → Main

This preserves development history while integrating completed work.

# Merge Commands

## Merge Branch

```bash
git merge feature-login
```

Combines the selected branch into the current branch.


## Abort Merge

```bash
git merge --abort
```

Stops a merge in progress after conflicts occur.


## Commit Graph

```bash
git log --graph --oneline --all
```

Visualizes merges and branch history.

# Merge Conflicts

A merge conflict happens when Git cannot automatically determine which changes should be kept.

Developers must manually choose the correct version.

## Workflow

- Create conflicting changes
- Merge branches
- Resolve conflict
- Commit resolved version

Learning to resolve conflicts is an essential Git skill.

# Merge Conflict Commands

## Start Merge

```bash
git merge feature-login
```

---

## View Status

```bash
git status
```

Shows conflicted files.

---

## Abort Merge

```bash
git merge --abort
```

Cancels merge.

---

## Finish Merge

```bash
git add .

git commit
```

Commits the resolved merge.