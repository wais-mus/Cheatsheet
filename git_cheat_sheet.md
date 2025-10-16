# 🧩 Git Cheat Sheet

## 🔧 Setup & Configuration
| Command | Meaning | Example |
|----------|----------|---------|
| `git config --global user.name "Your Name"` | Sets your global Git username. | `git config --global user.name "Wais Mustafa"` |
| `git config --global user.email "you@example.com"` | Sets your Git email (for commits). |  |
| `git init` | Initializes a new Git repository in current folder. | `git init` |
| `git clone <repo-url>` | Downloads a remote repository to your machine. | `git clone https://github.com/wais-mus/system-admin-automation.git` |

---

## 🧱 Core Workflow
| Command | Meaning | Example |
|----------|----------|---------|
| `git status` | Shows tracked/untracked file status. |  |
| `git add .` | Stages all changes for commit. |  |
| `git commit -m "Message"` | Saves staged changes with a message. |  |
| `git push origin main` | Uploads commits to the remote repo. |  |
| `git pull origin main` | Fetches and merges latest changes from remote. |  |

---

## 🌿 Branching & Merging
| Command | Meaning | Example |
|----------|----------|---------|
| `git branch` | Lists all branches. |  |
| `git checkout -b feature1` | Creates and switches to new branch. |  |
| `git merge feature1` | Merges changes from another branch. |  |
| `git branch -d feature1` | Deletes a branch (after merge). |  |

---

## 🧰 Undoing & Cleaning
| Command | Meaning | Example |
|----------|----------|---------|
| `git reset --hard` | Discards all local changes. |  |
| `git rm --cached <file>` | Unstage or remove file from tracking. |  |
| `git log --oneline` | Shows concise commit history. |  |

---

## 🧠 Tips
- Always use meaningful commit messages.  
- Pull before pushing (`git pull --rebase origin main`).  
- Use `.gitignore` to skip tracking sensitive/system files.  

📘 **Learn more:** [Git Branching Game](https://learngitbranching.js.org)
