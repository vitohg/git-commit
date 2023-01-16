# How to commit with git

### Change branch
```
git branch -M "main"
```

#

### First commit
```
git init
git add filesname or git add .
git status
git commit -m "first commit"
git remote add origin <link>
git push -u origin main
```

#

### Remote remove
```
git remote remove origin
```

#

### Change commit
```
git add filesname or git add .
git commit -m "commit"
git pull --rebase origin main
git push origin main
```

<br>

# Change username and email in git 
```
git config --list
git config --global user.name "yourname"
git config --global user.email "youremail"
```

<br>

# Copy someone else's repository
```
git clone <link>
git pull
``` 

#

<br>

<div align="center">
END
</div>