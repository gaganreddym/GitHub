# 🌱 Beginner’s Guide to Using GitHub

Welcome! 👋  
This guide will help you learn the basics of using **Git** and **GitHub** to manage and share your projects.

---

## What is GitHub?

GitHub is a platform that uses **Git**, a version control system, to track changes in your code.  
It helps developers **collaborate**, **backup projects**, and **manage versions** easily.

---

## Prerequisites

Before you start:
- Create a [GitHub account](https://github.com/)
- Install [Git](https://git-scm.com/downloads)
- Know basic terminal 
---

## Step 1: Create a Repository on GitHub
1. Log in to your GitHub account.  
2. Click the **“+”** button in the top-right → select **“New repository”**.  
3. Give it a name (e.g., `GitHub`).  
4. Choose **Public** or **Private**.  
5. Click **Create repository**.

---

## Step 2: Clone Repository and Connect Locally
1. **Open your GitHub repository** and copy the **HTTPS URL**  
   (Example: `https://github.com/gaganreddym/GitHub.git`)

2. **Open a folder** on your PC where you want to store your project, then **open Git Bash** in that folder.

3. **Clone the repository**:
   ```bash
   git clone https://github.com/gaganreddym/GitHub.git

## Step 3: Clone Repository and Connect Locally
1. Create a new file in your project folder note.txt
2. Add the new file to Git
   (`git add note.txt`)
4. Check the current status
   (`git status`)
5. Commit your changes with a message
   (git commit -m "new commit")
6. View Repository Overview
    (git log --all --decorate --oneline --graph)
7. Push Changes to GitHub
   (git push origin) or git push origin main --force

 ### Summary of Common Git Commands

| Command                   | Description                     |
| ------------------------- | ------------------------------- |
| `git init`                | Initialize a new Git repository |
| `git clone <url>`         | Clone an existing repository    |
| `git add <file>`          | Stage a file for commit         |
| `git commit -m "message"` | Commit staged changes           |
| `git status`              | Show current file states        |
| `git push origin main`    | Push commits to GitHub          |
| `git pull origin main`    | Fetch and merge changes         |
| `git log`                 | View commit history             |

