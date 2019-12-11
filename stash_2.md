**https://stackoverflow.com/questions/20537223/when-should-i-use-git-stash**

### Part 1:
git stash # for hide you changes without commit
git checkout some_branch # for work with other tasks and come back on your branch
git stash list # for see your list with hidden changes

    You can see:
    stash@{0}: WIP on {branch_name}: {SHA-1 of last commit} {last commit of you branch}
    stash@{0}: WIP on master: 085b095c6 modification for test

git stash apply # for apply your last changes from stash list
git stash apply stash@{12} # if you will have many stashes you can choose what stash will apply

git stash drop stash@{0} # for remove from stash list
or
git stash pop stash@{1} # for apply choosed stash and drop it from stash list

### Part 2:
You can hide your changes with this command but it is not necessary.
You can continue on the next day without stash.
This commands for hide your changes and work on different branches or for implementation some realisation of your code and save in stashes without branches and commitsor your custom case!
And later you can use some of stashes and check wich is better.

### Part 3:
Stash command for local hide your changes.
If you want work remotely you must commit and push.
