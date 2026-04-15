📘 Advanced Git Workflow & Version Control

🎯 Title

Enterprise-Level Git Workflow, Branching & History Management

📌 Objective

This assignment demonstrates advanced Git concepts including version control, branching strategies, and history rewriting.

🧠 Topics Covered

Git & Version Control System (VCS)

Git Branching Strategy

History Manipulation (Rebase, Reword, Squash)

🛠️ Tasks Completed

🔹 Task 1: Repository Initialization

git init
git checkout -b main
git checkout -b develop
git checkout -b feature/login

🔹 Task 2: Branching Workflow

git checkout -b feature/payment
git checkout -b feature/profile
git checkout -b bugfix/login-error

# Merge example
git checkout develop
git merge feature/payment

# Rebase example
git checkout feature/profile
git rebase develop

🔹 Task 3: Commit History Management

# Create commits
echo "file1" > file1.txt
git add .
git commit -m "Add file1"

echo "file2" > file2.txt
git add .
git commit -m "Add file2"

# ... more commits


# Interactive rebase
git rebase -i HEAD~5

Actions used:

pick → keep commit as is

reword → change commit message

squash → combine commits

edit → amend commit

drop → remove commit


📸 Screenshots (to include)

Branch list (git branch)

Commit history (git log --oneline)

Merge result

Rebase editor screen

GitHub repository view

Pull Request/Merge Request view



📦 Deliverables

GitHub Repository Link: https://github.com/auladwd/git-assignment/tree/main

README.md file with commands, screenshots, explanations

Clean commit history

