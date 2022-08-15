# Git Config
## Configuration level
### local
```
git config --local user.name "Nisawara"
git config --local user.email "j.nisawara@gmai.com"
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