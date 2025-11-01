````markdown
# 🧩 Basic Git Workflow (Beginner-Friendly)

## 1️⃣ Check Status
```bash
git status
````

**What you’ll see:**

```
On branch main
Changes not staged for commit:
  modified: README.md
Untracked files:
  new_script.py
```

> Shows which files have been changed or are untracked.

---

## 2️⃣ Add Files

```bash
git add .
```

**What you’ll see:**
*No output (silently stages all files).*

> Use `git add <filename>` to stage specific files.

---

## 3️⃣ Commit Changes

```bash
git commit -m "feat: add regression analysis script"
```

**What you’ll see:**

```
[main 3f2a6c1] feat: add regression analysis script
 2 files changed, 45 insertions(+)
 create mode 100644 analysis.py
```

**Common Commit Types:**

| Type        | Meaning                              |
| ----------- | ------------------------------------ |
| `feat:`     | New feature                          |
| `fix:`      | Bug fix                              |
| `docs:`     | Documentation update                 |
| `refactor:` | Code restructuring                   |
| `style:`    | Code style or formatting             |
| `test:`     | Adding or updating tests             |
| `chore:`    | Config, dependencies, or maintenance |

---

## 4️⃣ Push to GitHub

```bash
git push origin main
```

**What you’ll see:**

```
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), done.
To https://github.com/virajparmaj/Smart-Stock.git
   1a2b3c4..3f2a6c1  main -> main
```

> ✅ Your latest changes are now live on GitHub!

```
```
