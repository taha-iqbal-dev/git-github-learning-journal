# Advanced Git Interaction

## 1. Skipping The Staging Area

### Command

```bash
git commit -a -m "Update file"
```

### Purpose

Stages and commits all tracked files in one step. Useful when modifying existing files.

## 2. Checking Repository Status

### Command

```bash
git status
```

### Purpose

Displays:

- Modified files
- Staged files
- Untracked files

## 3. Viewing Commit History

### Command

```bash
git log
```

### Purpose

Shows repository commit history.

## 4. Compact Commit History

### Command

```bash
git log --oneline
```

### Purpose

Displays commits in a short format.

## 5. Viewing Detailed Changes

### Command

```bash
git diff
```

### Purpose

Shows exact line-by-line changes before committing.

## 6. Viewing Staged Changes

### Command

```bash
git diff --staged
```

### Purpose

Shows changes that have been added to staging.

## 7. Renaming Files

### Command

```bash
git mv oldname.txt newname.txt
```

### Purpose

Renames a file while preserving Git history.

## 8. Deleting Files

### Command

```bash
git rm file.txt
```

### Purpose

Removes a file and stages its deletion.

## 9. Viewing Specific Commit

### Command

```bash
git show COMMIT_HASH
```

### Purpose

Displays details of a particular commit.

## Commands Practiced

- git status
- git diff
- git diff --staged
- git add
- git commit
- git commit -a
- git log
- git log --oneline
- git mv
- git rm
- git show