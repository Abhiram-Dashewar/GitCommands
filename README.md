# Git Commands Guide 🚀

This repository is a simple guide to help beginners understand and use Git effectively.

## About Git

Git is a version control system that helps you track changes in your code, manage different versions, and collaborate with others without overwriting each other’s work.

## About Github

GitHub is a cloud-based platform where you can store your Git repositories, collaborate with others, track changes, and manage projects (like code, issues, and pull requests) all in one place.

## 📚 Table of Contents

* [⚙️ Configuration Commands](#configuration-commands)
* [📁 Repository Setup](#repository-setup)
* [➕ Add & Commit](#add--commit)
* [🚀 Push & Pull](#push--pull)
* [🌿 Branching](#branching)

---

## ⚙️ Configuration Commands

### Local Configuration

* #### Setting up User locally (Only this repo)

```bash
git config user.name "Your github username"
git config user.email "Your github email"
```

* #### Removing User locally (Only this repo)

```bash
git config --unset user.name
git config --unset user.email
```

### Global Configuration

* #### Setting up User Globally (All repos)

```bash
git config --global user.name "Your github username"
git config --global user.email "Your github email"
```

* #### Removing User Globally (All repos)

```bash
git config --global --unset user.name
git config --global --unset user.email
```

---

## 📁 Repository Setup

### Initiating git in your repo

```bash
git init
```

### Cloning any Existing repo

```bash
git clone <REPO-URL>
```

---

## ➕ Add & Commit

### Add files to staging area

```bash
git add <file-name>
git add .   # add all files
```

### Check status

```bash
git status
```

### Commit changes

```bash
git commit -m "Your commit message"
```

### View commit history

```bash
git log
git log --oneline
```

---

## 🚀 Push & Pull

### Add remote repository

```bash
git remote add origin <REPO-URL>
```

### Push code to GitHub

```bash
git push -u origin main
```

### Push changes (after first push)

```bash
git push
```

### Pull latest changes

```bash
git pull origin main
```

### Fetch changes (without merging)

```bash
git fetch
```

---

## 🌿 Branching

### Create a new branch

```bash
git branch <branch-name>
```

### Switch to a branch

```bash
git checkout <branch-name>
```

### Create & switch branch (shortcut)

```bash
git checkout -b <branch-name>
```

### List all branches

```bash
git branch
```

### Merge branch

```bash
git merge <branch-name>
```

### Delete branch

```bash
git branch -d <branch-name>
```

---

## ✅ Bonus Tips

### Undo last commit (keep changes)

```bash
git reset --soft HEAD~1
```

### Undo last commit (remove changes)

```bash
git reset --hard HEAD~1
```

### Remove file from staging

```bash
git reset <file-name>
```

---

🔥 Now your README is complete and beginner-friendly!

If you want, I can also:

* Add **real examples**
* Convert this into a **PDF for submission**
* Or make it look **pro-level (like top GitHub repos)**
