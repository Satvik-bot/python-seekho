1. 
# 📘 Git Commands Cheat Sheet

A quick reference for common Git commands.

---

## 🔍 `git status`
Displays the state of the working directory and the staging area.  
It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git.

```bash
git status
```

---

## 🌿 `git branch`
Lists all local branches in the current repository.  
You can also use it to create or delete branches.

```bash
git branch -a
```

---

## 📥 `git fetch`
Downloads changes from a remote repository but does not merge them into your working directory.

```bash
git fetch
```

---

## 🔄 `git checkout`
Switches to a specified branch or commit.

```bash
git checkout branch-name    # Switch branches
git checkout -b new-branch  # Create and switch to a new branch
```

---

## ➕ `git add`
Adds changes in the working directory to the staging area.

```bash
git add file.txt         # Add specific file
git add .                # Add all changes in the current directory
```

---

## 📝 `git commit`
Records the staged changes in the repository with a message.

```bash
git commit -m "Your commit message"
```

---

## 🚀 `git push`
Uploads your local changes to the remote repository.

```bash
git push origin branch-name
```

---

## 🔄 `git pull`
Fetches and merges changes from the remote repository into the current branch.

```bash
git pull origin branch-name
```
