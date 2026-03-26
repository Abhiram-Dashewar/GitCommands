# Git Commands Guide 🚀

This repository is a **complete beginner-friendly guide** to learn Git step by step.

---

## 📚 Table of Contents

1. [About Git](#-about-git)  
2. [About GitHub](#-about-github)  
3. [Step 1: Setup Git](#-step-1-setup-git)  
4. [Step 2: Create or Get Repository](#-step-2-create-or-get-repository)  
5. [Step 3: Track Changes (Add & Commit)](#-step-3-track-changes-add--commit)  
6. [Step 4: Upload Code (Push & Pull)](#-step-4-upload-code-push--pull)  
7. [Step 5: Branching (Work Safely)](#-step-5-branching-work-safely)  
8. [Step 6: Undo Mistakes](#-step-6-undo-mistakes)  
9. [Final Tips](#-final-tips)  

---

## 📖 About Git

Git is a **version control system** that helps you:

- Track changes in your code  
- Restore old versions  
- Work with teams easily  

---

## 🌐 About GitHub

GitHub is a **cloud platform** where you:

- Store your Git repositories  
- Share projects  
- Collaborate with others  

---

## ⚙️ Step 1: Setup Git

### 🔹 Set username & email (Local - only current project)

```bash
git config user.name "Your Name"
git config user.email "your@email.com"
```

👉 Use this if you want **different identities for different projects**

---

### 🔹 Set globally (All projects)

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

👉 Use this for your **main GitHub account**

---

### 🔹 Remove user info

```bash
git config --unset user.name
git config --unset user.email
```

(Global remove)

```bash
git config --global --unset user.name
git config --global --unset user.email
```

---

## 📁 Step 2: Create or Get Repository

### 🔹 Create a new repository

```bash
git init
```

👉 Converts your folder into a Git repository  

---

### 🔹 Clone existing repository

```bash
git clone <repo-url>
```

👉 Downloads project from GitHub  

---

## ➕ Step 3: Track Changes (Add & Commit)

### 🔹 Check status

```bash
git status
```

👉 Shows:
- Modified files  
- New files  
- Files ready to commit  

---

### 🔹 Add files

Add single file:

```bash
git add file.txt
```

Add all files:

```bash
git add .
```

👉 Moves files to **staging area**

---

### 🔹 Commit changes

```bash
git commit -m "Added new feature"
```

👉 Saves your changes permanently  

---

### 🔹 View history

```bash
git log
```

Short version:

```bash
git log --oneline
```

---

## 🚀 Step 4: Upload Code (Push & Pull)

### 🔹 Connect to GitHub

```bash
git remote add origin <repo-url>
```

👉 Links local project to GitHub  

---

### 🔹 First push

```bash
git push -u origin main
```

👉 Uploads code for the first time  

---

### 🔹 Push updates

```bash
git push
```

👉 Sends latest changes  

---

### 🔹 Pull latest code

```bash
git pull origin main
```

👉 Gets updates from GitHub  

---

### 🔹 Fetch changes

```bash
git fetch
```

👉 Downloads changes but **does NOT merge**

---

## 🌿 Step 5: Branching (Work Safely)

Branches help you work without affecting main code.

---

### 🔹 Create branch

```bash
git branch new-branch
```

---

### 🔹 Switch branch

```bash
git checkout new-branch
```

---

### 🔹 Create & switch (shortcut)

```bash
git checkout -b new-branch
```

---

### 🔹 List branches

```bash
git branch
```

---

### 🔹 Merge branch

```bash
git merge new-branch
```

👉 Combines branch into current branch  

---

### 🔹 Delete branch

```bash
git branch -d new-branch
```

---

## 🔥 Step 6: Undo Mistakes

### 🔹 Undo last commit (keep changes)

```bash
git reset --soft HEAD~1
```

---

### 🔹 Undo last commit (delete changes)

```bash
git reset --hard HEAD~1
```

---

### 🔹 Unstage a file

```bash
git reset file.txt
```

---

## ✅ Final Tips

- Always write **clear commit messages**  
- Use branches for new features  
- Always **pull before push**  
- Practice regularly  

---

## 🎯 Simple Workflow (Quick Revision)

```bash
git init
git add .
git commit -m "First commit"
git remote add origin <repo-url>
git push -u origin main
```

---

⭐ Beginner-friendly Git guide ready to use!