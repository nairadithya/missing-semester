---
title: An Introduction To Git.
author: Adithya Nair
theme: uncover 
paginate: true
math: mathjax
---

# An Introduction to Git

By Adithya Nair

---
# Missing Semester
An initiative where students teach students.

---
# Topics To Take Up
1. Self-Hosting
2. Vim motions 
3. Bash Scripting
4. RegEx
5. Unit Testing

---
# The Purpose Of This Presentation
- Teach the basics of version control and collaborative programming
- Equip all of you with the ability to manage your own projects with ease.

---
# Problems I Noticed
- Sending code through WhatsApp
- Losing progress and code changes.
- Making duplicates of files that get lost.
---
# What Is Git? 
* Git tracks the changes you make to your files
* Git is local
* Git tends to only add data

---


---
# Necessary Vocabulary 
- Commit
- Repository
- Branch
- Staging
---

# How Does Git Work? 

---
# Git is a camera, for your filesystem.

---
# Git is also a time machine

---
# The Three States
1. Modified
2. Staged
3. Commited

---
# The Basic Git Workflow
1. You modify files.
2. Stage only the changes which should be part of the next commit 
3. Commit, storing that snapshot permanently to your Git directory.

---
# Doubts?

---
# Installation

---
# Email And Name
```sh 
git config --global user.name "Adithya Nair"
git config --global user.email "adithyanair121@gmail.com"
```
---
# Initialize A Repo
```shell
git init
```
---
# Cloning A Repo
```shell
git clone <repo-name>
```

---
# Check Status
```sh 
git status
# For a shortened status
git status -s 
```

---
# Adding Files
```sh 
git add <file-name>
```
---
# Ignoring Files
```sh 
.gitignore

*.out
```

---
# Committing Files
```sh 
git commit
# Inline the commit message within the shell
git commit -m "<Message>"
```

---
# Checking Logs
```sh 
git log 
# For a shorter log
git log -s
```
---
# Create A New Branch
```sh 
git branch <branch-name>
```
---
# Switch To A Branch
```sh 
git checkout <branch-name>
# You can also use
git switch <branch-name>
```
---
# Rollback Changes
```sh 
git revert <commit>
```
Note that the commit's hash must be used, not its message. You find the hash by looking at the logs.

---
# Merge Branches
```sh 
git checkout <branch-to-merge-to>
git merge <branch-to-be-merged-with>
```
---
# Delete Branches
```sh 
git branch -d <branch-name>
```
---
# Demo Workflow
A quick demonstration of how I use git.

---
# Meta Information
- This presentation was built with a framework called Marp
- Notes were organized using Emacs Org-Mode
---
# References
- [MIT Lecture On Git](https://www.youtube.com/watch?v=2sjqTHE0zok)
- [Pro Git](https://git-scm.com/book/en/v2)
