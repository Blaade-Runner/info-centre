# Method #1
## Git Stash

### Check current branch
git branch

### Stash current changes
git stash

### Can check the stash list
git stash list

### Pull latest code from current branch
git pull origin [current_branch_name]

### Create a new branch & switch to it
git checkout -b [new_branch_name]

### Check git pointing to new branch
git branch

[ex -
develop
master
* new_branch_name ]

### Apply the stashed changes
git stash apply
#### or
git stash pop

### Now add changes to new branch
git add .
git commit -m ""
git push origin [new_branch_name]
