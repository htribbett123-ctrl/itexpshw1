## ✅ README Section: Git Workflow Lab Steps
 
## The full lab report, including screenshots and documentation, is available here:
https://github.com/htribbett123-ctrl/itexpshw1/blob/main/ITEXPSHW1_Lab_Process.pdf

# Git Workflow Lab (ITEXPS Homework 1)

![Git Workflow](https://img.shields.io/badge/Git-Workflow-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![ITEXPS](https://img.shields.io/badge/ITEXPS-Lab%201-purple)


This repository demonstrates a complete Git workflow including cloning, staging, committing, branching, merging, and pushing changes to GitHub.

## Table of Contents
- Overview
- Steps Completed
- Git Commands Used
- Branching Workflow
- What I Learned


## Git Commands Used
- `git clone`
- `git add`
- `git commit`
- `git push`
- `git branch`
- `git switch`
- `git merge`

## Branching Workflow

main
│
└─── f1 (feature branch)
        └── Added 3.txt → merged back into main

        main ──●──────────────●───────────●
         \ 
          ●──●──●  f1  (feature work)
                 \ 
                  ●── merge into main
                  


## 🔧 1. Created and Configured Public GitHub Repository
• 	Set up a new public repository on GitHub.
• 	Prepared the repo for local development.


## 💻 2. Cloned Repository to Local Machine
• 	Cloned the remote repository using Git Bash.
• 	Encountered a directory permission issue because the working directory was  (not writable).
• 	Resolved the issue by navigating to the home directory:
##  '''cd ~'''
## '''pwd'''   # Verified I was in my home directory


• 	Navigated into the project folder to continue work.

## 📄 3. Added Initial Files
• 	Created two text files:  and , each containing two lines of text.
• 	Staged the files:
## git add .

## 📝 4. Committed Initial Structure
• 	Committed staged files with the message:
## git commit -m "Initial Structure"

## 🚀 5. Pushed Changes to GitHub
• 	Pushed the initial commit to the remote repository:
## git push


## 🌿 6. Implemented Feature Branch Workflow
• 	Verified I was on the  branch.
• 	Created a new feature branch named :
## git branch f1
## git switch f1

## ➕ 7. Added New File on Feature Branch
• 	Created a new file  with two lines of text.
• 	Staged and committed the file:
## git add 3.txt
## git commit -m "Add 3.txt"

# 🔄 8. Merged Feature Branch into Main
• 	Switched back to the main branch:
## git switch main

• 	Merged the feature branch:
## git merge f1

## ⬆️ 9. Pushed Final Changes
• 	Pushed the merged updates (including ) to GitHub:
## git push


## What I Learned
- How to resolve Git Bash permission issues by navigating to the correct directory.
- How to stage and commit files properly.
- How to create and switch between branches.
- How to merge a feature branch into the main branch.
- How to push updates to a remote GitHub repository.

