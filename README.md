# Git & GitHub Learning Repository

Welcome! 👋  
This repository exists as a **sandbox for learning Git and GitHub**.  
Nothing here is “production code” — the goal is to practice workflows, make mistakes, and understand how version control works.

If you’re new to Git or GitHub, you’re in the right place.

---

## What Is **Git**?

**Git** is a *version control system*.  
It helps you:

- Track changes to files over time
- Go back to previous versions
- Work on multiple features at once
- Collaborate with other people without overwriting each other’s work

Think of Git as a **time machine for your code**.

---

## What Is **GitHub**?

**GitHub** is a website that hosts Git repositories.

Git:
- Runs on your computer
- Tracks file history locally

GitHub:
- Stores repositories online
- Makes collaboration easy
- Adds tools like pull requests, issues, and code reviews

👉 You can use Git *without* GitHub, but GitHub makes teamwork (and sharing) much easier.

---

## Basic Git Concepts

### Repository (repo)
A **repository** is a folder tracked by Git.  
It contains:
- Your files
- A hidden `.git/` directory with all the history

---

### Commit
A **commit** is a snapshot of your files at a point in time.

- Each commit has a message describing *what changed*
- Commits form a history you can move backward and forward through

Good commit messages are small and descriptive.

---

### Branch
A **branch** is a parallel version of the code.

- `main` (or `master`) is usually the default branch
- Branches let you experiment without breaking main
- You can merge a branch back when it’s ready

---

### Remote
A **remote** is a copy of your repository stored somewhere else (like GitHub).

- `origin` is the default name for the GitHub remote
- You push commits to the remote
- You pull changes from the remote

---

## Common Git Commands

### Check status
```bash
git status
```
shows 
- which files have changed
- whats staged
- whats untracked

### Commit changes
```bash
git commit -m "Describe what you changed"
```

Creates a snapshot of staged files.

### View history
```bash
git log
```
Shows commit history.

### Show whats changed since last commit
```bash
git diff
```

### Create a branch
```bash
git branch new-branch
git checkout new-branch
```

Or in one step:

```bash
git checkout -b new-branch
```

### Switch branches
```bash
git checkout branch-name
```
or
```bash
git switch branch-name
```

### Push to GitHub
Formally the command is
```bash
git push origin branch-name
```
or mostly in shorthand
```bash
git push
```

### Pull from GitHub
```bash
git pull
```
---
---

# Typical Workflow

1. Make changes to files

2. Check what changed:
```bash
git status
```

3. Stage changes:
```bash
git add .
```

4. Commit changes:
```bash
git commit -m "Short description of changes"
```

5. Push to GitHub:
```bash
git push
```

6. Repeat often — small commits are better than big ones.

---
## GitHub Vocabulary

### Pull Requests (PRs)

A pull request is a request to merge one branch into another.

Used to:

- Review code

- Discuss changes

- Run automated checks

Even for solo work, PRs are a great habit.

### Issues

Issues are used to:

- Track bugs

- Propose ideas

- Write TODOs

Think of them as a shared task list.

### Forks

A fork is a copy of someone else’s repository under your account.

Used when:

- You don’t have write access

- You want to experiment freely

Making Mistakes Is Normal

**Everyone HAS and WILL**:

- Commits the wrong file

- Writes bad commit messages

- Breaks something

That’s how you **learn** Git. This repo is intentionally safe for experimentation.

---

## Goals of This Repository

Practice Git commands

Learn GitHub workflows

Understand commits, branches, and remotes

Get comfortable fixing mistakes

If you’re confused at any point — that means you’re learning 🙂

---
## Resources

https://git-scm.com/docs

https://docs.github.com

For help on the command line you can always type:
```bash
git help <command>
```
