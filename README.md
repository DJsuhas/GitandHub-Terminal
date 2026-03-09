# Git, GitHub, and Terminal Guide

## Introduction

Modern software development requires tools that help developers track code changes, collaborate with teams, and manage projects efficiently. Three essential tools used by developers are:

- **Git** – Version Control System  
- **GitHub** – Cloud platform for hosting Git repositories  
- **Terminal** – Command Line Interface used to interact with the system

---

# 1. Git

## What is Git?

Git is a **distributed version control system (DVCS)** used to track changes in source code during software development. It helps developers maintain different versions of a project and collaborate efficiently.

Git stores the **entire history of code changes**, allowing developers to revert to previous versions when needed.

---

## Key Features of Git

- Tracks changes in source code
- Maintains project history
- Allows multiple developers to collaborate
- Supports branching and merging
- Works locally without internet

---

## Git Architecture

```
Working Directory
       │
       ▼
   Staging Area
       │
       ▼
   Local Repository
       │
       ▼
   Remote Repository (GitHub)
```

### Explanation

**Working Directory**  
This is the area where developers create and modify files.

**Staging Area**  
Files are prepared here before committing them to the repository.

**Local Repository**  
This stores the complete project history on the developer’s machine.

**Remote Repository**  
The online version of the repository hosted on platforms like GitHub.

---

# 2. GitHub

## What is GitHub?

GitHub is a **web-based platform that hosts Git repositories** and allows developers to collaborate on projects.

It provides tools for **version control, code review, project management, and team collaboration**.

---

## Key Features of GitHub

- Online hosting of repositories
- Collaboration using Pull Requests
- Issue tracking
- GitHub Actions for CI/CD
- Project management tools
- Code review system

---

## GitHub Workflow Diagram

```
Developer
   │
   ▼
Local Repository (Git)
   │
   │ git push
   ▼
Remote Repository (GitHub)
   │
   │ Pull Request
   ▼
Team Review & Merge
```

---

# 3. Terminal

## What is Terminal?

The **Terminal** is a command-line interface (CLI) that allows users to interact with the computer using commands instead of graphical interfaces.

Developers use the terminal to run programs, navigate files, execute Git commands, and manage development environments.

---

## Basic Terminal Commands

| Command | Description |
|--------|-------------|
| `pwd` | Shows the current directory |
| `ls` | Lists files and folders |
| `cd foldername` | Changes directory |
| `mkdir foldername` | Creates a new folder |
| `touch filename` | Creates a new file |
| `rm filename` | Deletes a file |

---

# 4. Git Workflow

The typical Git workflow followed in software development:

```
Create Repository
        │
        ▼
Clone Repository
        │
        ▼
Make Changes
        │
        ▼
git add
        │
        ▼
git commit
        │
        ▼
git push
        │
        ▼
GitHub Repository Updated
```

---

# 5. Common Git Commands

| Command | Purpose |
|--------|--------|
| `git init` | Initialize a new Git repository |
| `git clone` | Copy repository from GitHub |
| `git add` | Add files to staging area |
| `git commit` | Save changes to repository |
| `git status` | Check repository status |
| `git log` | View commit history |
| `git branch` | Manage branches |
| `git merge` | Merge branches |
| `git push` | Upload code to GitHub |
| `git pull` | Fetch latest updates |

---

# 6. Example Git Setup

```bash
# Initialize repository
git init

# Add files to staging area
git add .

# Commit changes
git commit -m "Initial commit"

# Add remote repository
git remote add origin https://github.com/username/repository-name.git

# Push code to GitHub
git push -u origin main
```

---

# 7. Why Developers Use Git and GitHub

- Efficient version control
- Easy collaboration with teams
- Maintains project history
- Backup of source code
- Industry-standard development workflow

---

# Conclusion

Git, GitHub, and Terminal are essential tools for modern software development. Learning these tools helps developers manage code efficiently and collaborate effectively in real-world projects.
