# P3: Feature-Branch Git Workflow

## Aim
To practise creating a feature branch, making a change on it, and merging the feature into the main branch.

## Concepts
A branch provides an independent line of development. `git switch` changes branches, and `git merge` integrates another branch into the current branch.

## Procedure
1. Start with a Git repository containing at least one commit.
2. Create and switch to a feature branch.
3. Make a small change to a project file, then stage and commit it on the feature branch.
4. Switch back to `main` and merge the feature branch.
5. Verify the branch list and commit history.

## Commands
```bash
git branch feature-navbar
git switch feature-navbar
# Make and save a change in a project file
git add .
git commit -m "Add navbar feature"
git switch main
git merge feature-navbar
git branch
git log --oneline --graph --all
```

## Result
A feature branch was created, updated and merged into the main branch.

## Screenshot
See `screenshots/` for the terminal output.
