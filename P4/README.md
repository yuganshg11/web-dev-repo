# P4 - GitHub README and version tags

## Aim
Write a useful README for a project and mark a version with a Git tag.

## README sections

A project README should explain what the project is, what it contains, how to open or run it, and any details someone needs before using it.

## Commands

After updating the project's README and committing the change:

```bash
git add README.md
git commit -m "Write project README"
git tag -a v1.0 -m "First lab version"
git push origin main
git push origin v1.0
```

To check the tag:

```bash
git tag
git show v1.0
```

A tag is a named point in Git history. It is useful for marking a version that you may want to find again later.

## Result
The project has documentation and a version tag named `v1.0`.
