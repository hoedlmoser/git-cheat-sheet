# git-cheat-sheet
Hoedlmosers' personal Git Cheat Sheet

## init already created repo

if I already created my repository in gui with readme and license, but all the source is local, init can be done as following

```
git init
git remote add origin your-git-url
git fetch
git reset --mixed origin/master
git checkout -- LICENSE
git checkout -- README.md
```

## commit

```
git commit -am "<nice comment>"
```

## push (upload)

```
git push
```
