# P2 - Portfolio repo with an initial commit

## Aim
Create a GitHub repository for a portfolio project and save the first version with Git.

## Steps

1. Create a new repository on GitHub.
2. Open the project folder in Terminal.
3. Start Git in the folder.
4. Add the project files to the staging area.
5. Make the first commit.
6. Connect the local project to the GitHub repository and push it.

## Commands

```bash
git init
git status
git add .
git commit -m "Add initial portfolio files"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

Replace the remote URL with the URL of your own repository. If a remote named `origin` already exists, check it with `git remote -v` instead of adding it again.

## Result
The project is tracked by Git and its first commit is pushed to GitHub.
