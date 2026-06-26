# Undoing Changes Commands

## Restore Changes

```bash
git restore filename
```

Restores a modified file to its last committed state.


## Unstage Changes

```bash
git reset HEAD filename
```

Removes a file from the staging area without deleting changes.


## Amend Last Commit

```bash
git commit --amend
```

Updates the most recent commit.


## Revert a Commit

```bash
git revert HEAD
```

Creates a new commit that undoes the previous commit.


## View Commit History

```bash
git log
```

Displays commit history.


## View Short Commit History

```bash
git log --oneline
```

Displays compact commit history.


## View Commit Details

```bash
git show COMMIT_HASH
```

Shows the contents of a specific commit.