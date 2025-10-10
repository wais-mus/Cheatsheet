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
