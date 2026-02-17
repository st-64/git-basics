# 🚀 Git & GitHub Basics - My Learning Notes

Welcome to my Git learning repository! Here I am documenting the core commands and concepts of Version Control.

## 🧠 Git vs. GitHub (The Difference)

- **Git:** A tool installed on my laptop (Local) to track changes. It's like a "Time Machine" for code.
- **GitHub:** A website (Cloud) where we upload our Git repositories. It's like "Google Drive" for code.

---

## 🛠️ Essential Commands Cheat Sheet

### 1. Setup & Configuration

- `git config --global user.name "Your Name"`: Tell Git who you are.
- `git config --global user.email "email@example.com"`: Set email for commits.

### 2. Starting a Project

- **`git init`**: Turns a normal folder into a Git Repository (Creates hidden `.git` folder).
- **`git clone <link>`**: Downloads an existing project from GitHub to your laptop.

### 3. The 3-Stage Workflow

1.  **Working Directory:** Where I write code.
2.  **Staging Area:** `git add .` (Putting files in the box).
3.  **Repository:** `git commit` (Sealing the box with a label).

### 4. Saving Changes

- `git status`: Shows which files are changed or untracked.
- `git add <filename>`: Adds a specific file to staging.
- `git add .`: Adds **ALL** changes to staging.
- `git commit -m "Message"`: Saves the snapshot with a descriptive message.

### 5. Syncing with GitHub

- `git push origin main`: Uploads code to GitHub (First time).
- `git push`: Uploads code (Daily use).
- `git pull`: Downloads new changes from GitHub to my laptop.

---

## 🚦 Important Flags

- **`-m`** (Message): Used in commit to add a note.
- **`-u`** (Upstream): Connects local branch to remote branch permanently.
- **`-a`** (All): Shortcut to add and commit tracked files together.

## 🛑 How to Ignore Files

Create a `.gitignore` file and write names of files/folders you don't want to upload (e.g., `node_modules/`, `.env`).

---

### 📅 Author

**Subhendu** - Aspiring Full Stack Developer 🚀
