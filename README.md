# Use default branch name `main`

## When creating a new repository

Create a repo on your git host (e.g. github, gitlab), do not let it create or initialize any files for you.

Then run these on the client command line:
```shell
git init
git checkout -b main
git remote add origin git@github.com:username/repo.git
git add your.files
git commit -m "first commit"
git push -u origin main
```

## When renaming an existing repository

```shell
git branch -m master main
git push -u origin main
```

Change default branch in github settings:
```
https://github.com/username/repo/settings/branches
```
