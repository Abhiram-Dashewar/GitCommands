# Git Commands Guide 🚀

This repository is a simple guide to help beginners understand and use Git effectively.

---

## 📖 About Git

Git is a version control system that helps you:

* Track changes in your code
* Go back to previous versions
* Work with teams without conflicts

---

## 🌐 About GitHub

GitHub is an online platform where you:

* Store your Git projects (repositories)
* Share code with others
* Collaborate using pull requests and issues

---

## 📚 Table of Contents

* [Configuration Commands](#configuration-commands)
* [Repository Setup](#repository-setup)
* [Add and Commit](#add-and-commit)
* [Push and Pull](#push-and-pull)
* [Branching](#branching)

---

## ⚙️ Configuration Commands

### 🔹 Local Configuration (Only current repository)

Set username and email:

```bash
git config user.name "Your Name"
git config user.email "your@email.com"
```

Remove user:

```bash
git config --unset user.name
git config --unset user.email
```

👉 Use this when working on different projects with different identities.

---

### 🔹 Global Configuration (All repositories)

Set globally:

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

Remove globally:

```bash
git config --global --unset user.name
git config --global --unset user.email
```

👉 Use this for your main GitHub account.

---

## 📁 Repository Setup

### Initialize a new repository

```bash
git init
```

👉 Converts your folder into a Git repository.

---

### Clone an existing repository

```bash
git clone <repo-url>
```

👉 Downloads a project from GitHub to your system.

---

## ➕ Add and Commit

### Check file status

```bash
git status
```

👉 Shows modified, staged, and untracked files.

---

### Add files to staging area

```bash
git add file.txt
git add .
```

👉 Prepares files before committing.

---

### Commit changes

```bash
git commit -m "Your message"
```

👉 Saves your changes with a message.

---

### View commit history

```bash
git log
git log --oneline
```

👉 Shows previous commits.

---

## 🚀 Push and Pull

### Add remote repository

```bash
git remote add origin <repo-url>
```

👉 Connects local project to GitHub.

---

### Push code (first time)

```bash
git push -u origin main
```

👉 Uploads code to GitHub.

---

### Push updates

```bash
git push
```

👉 Sends latest commits to GitHub.

---

### Pull latest changes

```bash
git pull origin main
```

👉 Downloads and merges updates from GitHub.

---

### Fetch changes

```bash
git fetch
```

👉 Downloads changes but does NOT merge.

---

## 🌿 Branching

### Create a branch

```bash
git branch new-branch
```

---

### Switch branch

```bash
git checkout new-branch
```

---

### Create & switch (shortcut)

```bash
git checkout -b new-branch
```

---

### List branches

```bash
git branch
```

---

### Merge branch

```bash
git merge new-branch
```

👉 Combines branch into current branch.

---

### Delete branch

```bash
git branch -d new-branch
```

---

## 🔥 Bonus Commands

### Undo last commit (keep changes)

```bash
git reset --soft HEAD~1
```

---

### Undo last commit (delete changes)

```bash
git reset --hard HEAD~1
```

---

### Unstage a file

```bash
git reset file.txt
```

---

## ✅ Final Tip

* Always write clear commit messages
* Use branches for new features
* Pull before pushing to avoid conflicts

---

⭐ Now your README navigation works perfectly and is beginner-friendly!
