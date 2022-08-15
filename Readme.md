# Git Config
## Configuration level
### local
```
git config --local user.name "Nisawara"
git config --local user.email "j.nisawara@gmail.com"
```

### Global
```
git config --global core.editor "code --new-window--wait"
```

### System 
```
git config --system -e
```

### Git log
### Filter
```
git log --since=2022-08-14
git log --since="1days ago"
git log --since=1.days
git log --until=1.dyas
git log --since=2.weeks --until=1.days
git log --after=1.weeks --before=1.days
git log --grep="readme"
git log --author="Nisawara"
git log --962a0..HEAD
git log Readme.md
```

### Format
```
git log -p
git log --stat 
git log --format=oneline
git log --oneline
git log --oneline --graph --decorate
```
## Git Show
```
git show ac8
git show HEAD
git show HEAD^
git show HEAD^^
git show HEAD^^^
git HEAD~5
```

## Git Blame
```
git blame readme.md
```

## Git ls-tree
```
git ls-tree HEAD
git ls-tree main
git ls-tree 962a0
```
## Git add commit
```
git add .
git add Readme.md
git commit -m "commit message"
git commit -am "add and commit"
git commit --amend 
git commit --amend -m "commit and add new message"
git remote add origin <URL of remote repository>
git remote -v
```

## Git Remove(git rm)
```
git rm <filename>
git rm --cached <filename>

```
## Git diff
```
git diff //working area and index
git diff --cached //repo
git diff 
git diff ac8..48d
git diff HEAD..HEAD~2 //Move back
git diff HEAD~2..HEAD // Move forword
```