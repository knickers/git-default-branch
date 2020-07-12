# Create Repo

- Create repo on git host, do not let it create or initialize any files for you.

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
