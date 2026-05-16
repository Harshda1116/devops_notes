# Git Basics

## What is Git?

Git is a distributed version control system used to track changes in source code and collaborate with developers.

---

## Why Git is Important

- Tracks code changes
- Helps in collaboration
- Supports branching and merging
- Maintains project history
- Essential for DevOps workflows

---

# Git Configuration

## Check Git Version

```bash
git --version
```

---

## Configure Username

```bash
git config --global user.name "Your Name"
```

---

## Configure Email

```bash
git config --global user.email "your-email@example.com"
```

---

# Basic Git Commands

## Initialize Git Repository

```bash
git init
```

---

## Check Repository Status

```bash
git status
```

---

## Add Files

Add single file:

```bash
git add filename
```

Add all files:

```bash
git add .
```

---

## Commit Changes

```bash
git commit -m "commit message"
```

---

## View Commit History

```bash
git log
```

---

## Remove File from Staging

```bash
git restore --staged filename
```

---

## Check Remote Repository

```bash
git remote -v
```