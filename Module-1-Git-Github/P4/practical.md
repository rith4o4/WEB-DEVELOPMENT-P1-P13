# P4: GitHub README and Version Tags

## Aim
To document a project using a README file and mark a project version using a Git tag.

## Concepts
A README explains a repository's purpose, contents and usage. A Git tag is a named reference to a particular commit, often used to mark a release.

## Procedure
1. Create or open the project repository.
2. Create `README.md` and add the project title, description, technologies and usage information.
3. Stage and commit the README.
4. Create a version tag on the commit and verify it.
5. If publishing to GitHub, push the branch and tag.

## Commands
```bash
touch README.md
# Add project documentation to README.md
git add README.md
git commit -m "Add project README"
git tag v1.0
git tag
git show v1.0
git push origin main
git push origin v1.0
```

## Result
Project documentation was added and a version tag was created for the documented commit.

## Screenshot
See `screenshots/` for the terminal output.
