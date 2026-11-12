# P3 - Feature-branch Git workflow

## Aim
Practise making a change on a separate branch instead of working directly on the main branch.

## Steps and commands

```bash
git switch main
git pull
git switch -c feature/about-section
```

Make a small change to the project, then check and commit it:

```bash
git status
git add .
git commit -m "Add about section"
git push -u origin feature/about-section
```

After pushing, open the repository on GitHub and create a pull request from `feature/about-section` into `main`. Review the changes and merge the pull request when everything looks correct.

## Useful commands

- `git branch` lists local branches.
- `git switch BRANCH_NAME` changes branches.
- `git diff` shows changes that have not been staged.
- `git log --oneline` shows recent commits.

## Result
The feature was developed on its own branch and can be reviewed before it is merged into the main branch.
