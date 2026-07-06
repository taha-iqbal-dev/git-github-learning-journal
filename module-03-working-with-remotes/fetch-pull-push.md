# Fetch vs Pull vs Push

## git fetch

Downloads changes from GitHub.

Does not modify your working files.

```bash
git fetch origin
```

---

## git pull

Downloads changes.

Automatically merges them.

```bash
git pull origin main
```

---

## git push

Uploads local commits to GitHub.

```bash
git push origin main
```

---

## Workflow

```
GitHub
↓

Fetch

↓

Review

↓

Pull

↓

Local Repository

↓

Commit

↓

Push

↓

GitHub
```