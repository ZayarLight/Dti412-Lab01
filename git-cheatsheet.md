# Git Command Cheat Sheet

## Check Git Version

```bash
git --version
```

Purpose: Display the installed Git version.

---

## Configure Username

```bash
git config --global user.name "Your Name"
```

Purpose: Set the global Git username.

---

## Configure Email Address

```bash
git config --global user.email "your@email.com"
```

Purpose: Set the global Git email address.

---

## View Git Configuration

```bash
git config --list
```

Purpose: Display all Git configuration settings.

---

## Clone a Repository

```bash
git clone repository-url
```

Example:

```bash
git clone https://github.com/username/dti412-lab01.git
```

Purpose: Download an existing repository from GitHub.

---

## Check Repository Status

```bash
git status
```

Purpose: Show the current status of the working directory.

---

## Add All Files

```bash
git add .
```

Purpose: Stage all modified and new files.

---

## Add a Specific File

```bash
git add filename
```

Example:

```bash
git add profile.md
```

Purpose: Stage a specific file.

---

## Commit Changes

```bash
git commit -m "Commit message"
```

Example:

```bash
git commit -m "Add developer profile"
```

Purpose: Save staged changes to the local repository.

---

## View Commit History

```bash
git log --oneline
```

Purpose: Display a compact commit history.

---

## Push Changes to GitHub

```bash
git push origin main
```

Purpose: Upload commits to the GitHub repository.

---

## Pull Latest Changes

```bash
git pull origin main
```

Purpose: Download and merge changes from GitHub.

---

## Display Current Branch

```bash
git branch
```

Purpose: Show the current branch.

---

## Create a New Branch

```bash
git branch branch-name
```

Example:

```bash
git branch feature-login
```

Purpose: Create a new branch.

---

## Switch Branches

```bash
git checkout branch-name
```

Example:

```bash
git checkout feature-login
```

Purpose: Switch to another branch.

---

## Create and Switch to a New Branch

```bash
git checkout -b branch-name
```

Example:

```bash
git checkout -b feature-login
```

Purpose: Create and switch to a new branch in one command.

---

## Merge a Branch

```bash
git merge branch-name
```

Example:

```bash
git merge feature-login
```

Purpose: Merge another branch into the current branch.

---

## Delete a Branch

```bash
git branch -d branch-name
```

Example:

```bash
git branch -d feature-login
```

Purpose: Delete a local branch.

---

## Rename Current Branch

```bash
git branch -m main
```

Purpose: Rename the current branch.

---

## Remove a File

```bash
git rm filename
```

Example:

```bash
git rm oldfile.txt
```

Purpose: Remove a file from Git tracking.

---

## Useful Workflow

```bash
git status
git add .
git commit -m "Update project files"
git push origin main
```

Purpose: Common workflow for saving and uploading changes to GitHub.