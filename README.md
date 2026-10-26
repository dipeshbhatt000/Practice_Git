# Practice_Git

Welcome to my Git practice repository! This project serves as a dedicated sandbox for learning and mastering **Git and GitHub version control workflows**. 

The primary goal of this repository is to practice core Git commands, branching strategies, and collaboration workflows in a safe environment.

---

## 🚀 Features & Milestones
- **Basic Git operations**: Practicing staging, committing, and viewing project histories.
- **Branching & Merging**: Experimenting with feature branches, standard merges, and resolving merge conflicts.
- **Remote Workflows**: Syncing local progress with GitHub via pushing, pulling, and fetching.
- **Tracking & Ignoring**: Using `.gitignore` files to properly exclude system or build-specific files from version tracking.

---

## 📁 Repository Structure

```text
Practice_Git/
├── .gitignore          # Rules for files that Git should ignore
├── README.md           # Project documentation (this file)
└── file.md             # A sandbox file used to practice tracking and editing text
```

---

## 🛠️ Getting Started

If you want to clone this repository and use it for your own practice, follow these simple steps:

### 1. Clone the repository
Open your terminal and run the following command to download the repository to your local machine:
```bash
git clone [https://github.com/dipeshbhatt000/Practice_Git]
```

### 2. Navigate into the directory
```bash
cd Practice_Git
```

---

## 💻 Common Git Cheat Sheet

Here are the essential commands used and practiced in this repository:

### Checking Status & History
* `git status` — Check the current state of your working directory and staging area.
* `git log --oneline` — View a clean, condensed history of your commits.

### Saving Changes
* `git add <filename>` — Stage specific changes for the next commit.
* `git add .` — Stage all modified and new files.
* `git commit -m "Your descriptive commit message"` — Commit your staged changes to project history.

### Working with Branches
* `git branch` — List all local branches.
* `git checkout -b <branch-name>` — Create a new branch and switch to it immediately.
* `git merge <branch-name>` — Merge changes from a specified branch into your current active branch.

### Syncing with GitHub
* `git push origin <branch-name>` — Upload your local branch commits to GitHub.
* `git pull` — Fetch and integrate remote changes into your current working branch.

---

## 📝 License
This project is open-source and available for anyone to use for educational and learning purposes.
