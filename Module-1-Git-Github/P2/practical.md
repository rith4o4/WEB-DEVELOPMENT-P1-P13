# P2: Portfolio Repository with an Initial Commit

## Aim
To create a portfolio project, initialize Git, stage project files and record the initial version in a commit.

## Concepts
Git tracks changes in a project. The staging area holds changes selected for the next commit. A commit records a snapshot of the staged files.

## Procedure
1. Create a portfolio directory and its starter HTML, CSS and JavaScript files.
2. Navigate into the portfolio directory.
3. Initialize a Git repository.
4. Stage the project files and create the initial commit.
5. Check the repository status.

## Commands
```bash
mkdir -p My-Portfolio
cd My-Portfolio
touch index.html style.css script.js
git init
git branch -M main
git add .
git commit -m "Initial commit"
git status
```

## Result
The portfolio project was created, initialized as a Git repository and saved in an initial commit.

## Screenshot
See `screenshots/` for the terminal output.
