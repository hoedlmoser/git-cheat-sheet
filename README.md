# git-cheat-sheet
Hoedlmosers' personal Git Cheat Sheet

## read
https://git-scm.com/book/en/v2

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

## add
```
git add <somefile(s)>
```

## commit

```
git commit -am "<nice comment>"
```

## push (upload)

```
git push
```

## branch-ing
```
# be up-to-date
git pull

# create branch and push
git checkout -b <new-branch>
git push origin <new-branch>
git branch -a

# commit as usual

# merge
git checkout master
git merge <new-branch>

# delete
git branch -d <new-branch>
git push origin :<new-branch>
```
