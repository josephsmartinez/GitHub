# Basic Commands to know
```
git status
git commit -am "message"
git add .
git reset HEAD [file name]
git checkout -- [file name]
git log
git --oneline --graph

git config --global alias.hist "log --online --graph --decorate --all"
git config --global --list
git hist
git hist -- [file name]

### Using git
git mv [old file] [new file name]
git rm [file name]
git commit -m "deleted file"

git add -u
```

### Excluding files within repo
```
touch .gitignore
vm .gitignore
```
```
*.log
```
```
git add .gitignore
git commit -m "Adding ignore file"
```
