# 🧠 Git & Repo Essentials Cheat Sheet

---

## 🚀 How to Create a New GitHub Repository (Step-by-Step)

1. **Log in** to your GitHub account.

2. Click the **+ icon** (top right) and select **New repository**.

3. Enter the **repository name** (e.g., `my-project`).

4. Choose **Public** or **Private**.

5. *Optionally* add a **README**, `.gitignore`, or license (you can skip for now).

6. Click **Create repository**.

7. After creation, GitHub shows you instructions to **create or push a repo locally**.

---

## 💻 Setting Up Your Local Repository

### Option A: Start fresh locally and push to GitHub

```bash
# In your project folder
git init

# Add files
git add .

# Commit changes
git commit -m "Initial commit"

# Link your local repo to GitHub
git remote add origin https://github.com/your-username/my-project.git

# Set the main branch and push
git branch -M main
git push -u origin main


'''

🔑 Essential Git Commands
Command	What it Does
git init	Initialize a new Git repo locally
git clone <url>	Download a remote repo to your local machine
git status	Check current repo status (changes, staged files)
git add <file>	Stage a file for commit
git add .	Stage all changes
git commit -m "msg"	Commit staged changes with a message
git push	Upload committed changes to remote
git pull	Fetch and merge changes from remote
git branch	List branches
git branch -M main	Rename current branch to main
git checkout <branch>	Switch to another branch
git remote -v	Show remote repo URLs
git remote add origin <url>	Link local repo to remote repo

🔄 Switching Between Multiple Repositories Locally

Suppose you have multiple projects/repos on your machine.

1. Navigate between repos by changing directories:
# Move to project1 repo folder
cd ~/project1

# Check git status here
git status

# Move to project2 repo folder
cd ~/project2

git status


Each folder is an independent Git repo.

. Opening a repo from anywhere:

Open terminal (Git Bash, PowerShell, or WSL)

Use cd to jump to your repo folder path

Example:

cd ~/Documents/devops/cheatsheet

🔧 Tips for Working Across Multiple Repos

Keep repos organized in separate folders with clear names.

Use descriptive branch names when working on features.

Commit and push regularly to keep remotes up-to-date.

Use git pull often to stay in sync if collaborating.

📚 Summary: Typical Git Workflow in a Repo
# Check repo status
git status

# Stage changes
git add .

# Commit with message
git commit -m "Describe changes"

# Push to remote
git push

# To update local repo with remote changes
git pull
