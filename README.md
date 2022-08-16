# Intro to git


## First time setup
```
git config --global user.name "John Doe"  
git config --global user.email "johndoe@example.com"
```

## Create own from scratch
```
git init
```

## Add files 
```
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin https://github.com/SSGjakobviking/demo-git.git  
git push -u origin main
```

## Clone existing repository
```
git clone https://github.com/path/to/repo
```