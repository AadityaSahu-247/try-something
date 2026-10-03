# Git Basic Workflow

## 1. Check Commit History

```bash
git log
```

To see a shorter version:

```bash
git log --oneline
```

---

## 2. Make Changes

Open your project in VS Code and modify your files.

---

## 3. Check What Changed

```bash
git status
```

This shows modified, deleted, and untracked files.

---

## 4. Add Changes to Staging

```bash
git add .
```

This stages all changes in the current directory.

---

## 5. Create a Commit

```bash
git commit -m "Updated code"
```

A commit saves your staged changes in Git history.

---

## 6. Push Changes to GitHub

```bash
git push
```

This sends your local commits to the remote GitHub repository.

---

## Complete Workflow

```text
Make changes
     ↓
git status
     ↓
git add .
     ↓
git commit -m "message"
     ↓
git push
```

## Important Git Commands

| Command                     | Purpose                     |
| --------------------------- | --------------------------- |
| `git status`                | Check current changes       |
| `git add .`                 | Stage all changes           |
| `git commit -m "message"`   | Save changes as a commit    |
| `git push`                  | Upload commits to GitHub    |
| `git log`                   | View commit history         |
| `git log --oneline`         | View compact commit history |
| `git branch`                | View branches               |
| `git branch -d branch-name` | Delete a local branch       |
| `git checkout branch-name`  | Switch branches             |
| `git switch branch-name`    | Switch branches             |


