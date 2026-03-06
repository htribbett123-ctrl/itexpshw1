## ✅ README Section: Git Workflow Lab Steps

## The full lab report, including screenshots and documentation, is available here:
https://github.com/htribbett123-ctrl/itexpshw1/blob/main/ITEXPSHW1_Lab_Process.pdf

🔧 1. Created and Configured Public GitHub Repository
• 	Set up a new public repository on GitHub.
• 	Prepared the repo for local development.


## 💻 2. Cloned Repository to Local Machine
• 	Cloned the remote repository using Git Bash.
• 	Encountered a directory permission issue because the working directory was  (not writable).
• 	Resolved the issue by navigating to the home directory:
## cd ~
## pwd   # Verified I was in my home directory


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



