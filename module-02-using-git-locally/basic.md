# Git Basics 

## Initialize a Repository

```bash
git init
```

Creates a new Git repository in the current directory.

## Clone a Repository

```bash
git clone <repository-url>
```

Downloads a repository from GitHub to your computer.

Example:

```bash
git clone https://github.com/username/project.git
```

# Repository Information

## Check Repository Status

```bash
git status
```

Shows:

* Modified files
* Staged files
* Untracked files
* Current branch

## View Commit History

```bash
git log
```

Displays detailed commit history.

## View Compact Commit History

```bash
git log --oneline
```

Displays commits in a short format.

# Staging Changes

## Stage a Specific File

```bash
git add filename.txt
```

Adds a file to the staging area.

## Stage All Files

```bash
git add .
```

Stages all modified and new files.

# Committing Changes

## Create a Commit

```bash
git commit -m "Your message"
```

Creates a snapshot of staged changes.

Example:

```bash
git commit -m "Add Module 1 notes"
```

# Viewing Changes

## Compare Files

```bash
git diff
```

Shows unstaged changes.

## Compare Staged Changes

```bash
git diff --staged
```

Shows staged changes waiting to be committed.

# Working with Files

## Create a File

```bash
touch filename.txt
```

Creates a new file.

## View File Contents

```bash
cat filename.txt
```

Displays file contents.

# Basic Git Workflow

Step 1:

```bash
git status
```

Step 2:

```bash
git add .
```

Step 3:

```bash
git commit -m "Meaningful message"
```

Step 4:

```bash
git push
```

# Good Commit Messages

Examples:

```text
Initial repository setup
Add Module 1 notes
Create diff demonstration
Add patch demonstration
Complete Module 1
```

Avoid:

```text
update
new
final
test
```

# Commands Learned

```bash
git init
git clone
git status
git add
git commit
git log
git log --oneline
git diff
```

# Typical Workflow Example

```bash
git status

git add .

git commit -m "Add version control notes"

git push origin main
```

This workflow is the foundation of all Git usage.