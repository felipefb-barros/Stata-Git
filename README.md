# Stata-Git

# Stata - Git
> Basic Stata and Git Workflow
## Setting Directory
```bash
clear
capture cd "/Users/Your project directory"

ls
```
## Creating the Readme file 
```bash
! echo "# github-tutorial"  >> README.md
```
## Next we initialize the Git code
```bash

! git init

```

##  Next we add the README.md file and commit it
```bash
! git add README.md
! git commit -m 'my first upload'
```

## Add the github path

```bash
! git remote add origin https://github.com/Your path.git

! git push --set-upstream origin master
```

## Adding Files 

```bash
! git status
! git add file/ 
  ! git commit -m "your description"
! git push
```
