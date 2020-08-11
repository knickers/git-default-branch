# Create Repo

Create a repo on your git host (e.g. github, gitlab), do not let it create or initialize any files for you. Then run these on the client command line:

```shell
git init
git checkout -b main
git remote add origin git@github.com:username/repo.git
git add your.files
git commit -m "first commit"
git push -u origin main
```

# Rename Repo

```shell
$ git branch -m main
```
