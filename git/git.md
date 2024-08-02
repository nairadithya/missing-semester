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
- A system to manage all projects in an accessible way that allows for cross-pollination.

---
# Problems I Noticed
- Sending code through WhatsApp
- Losing progress and code changes.
- Making duplicates of files that get lost.
---
# What Is Git? 

---
# The Three States
1. Modified
2. Staged
3. Commited

---
# Git Is A Time Machine

---
# A DSA Detour
Git uses linked lists to keep track of commits.

---




# Installation Process
This is for Windows users, Mac and Linux users don't have to do anything.

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
# Meta Information
- This presentation was built with a framework called Marp
- Notes were organized using Emacs Org-Mode
---
# References
- [MIT Lecture On Git](https://www.youtube.com/watch?v=2sjqTHE0zok)
- [Pro Git](https://git-scm.com/book/en/v2)