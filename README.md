# Git

## Remove and add remote origin

```bash
git remote remove origin
git remote add remote/main https://github.com/g-kolyada/repo.git
git branch --set-upstream-to=remote/main main
git push --set-upstream remote/main main
git pull
git branch --all -l
```
