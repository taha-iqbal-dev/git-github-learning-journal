# Git Rebase

Rebase moves your commits on top of another branch.

```bash
git rebase main
```

Advantages

- Cleaner history
- Linear commits
- Preferred before Pull Requests

Disadvantages

- Can rewrite history
- Avoid rebasing shared branches

# Rebase vs Merge

## Merge

```bash
git merge feature
```

Creates a merge commit.

Preserves history.

---

## Rebase

```bash
git rebase main
```

Creates a clean linear history.

Avoid rebasing public branches.