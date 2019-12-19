### ⚫ Merge a branch with other

#### ⚫ Stay in master

**Don't mess with *Master***

➥   git branch checkout **master**

#### ⚫ Create a new feature branch to make new changes & switch to it

➥   git branch **new_branch**

➥   git checkout **new_branch**

**OR**

➥   git checkout -b **new_branch**

#### ⚫ Make some changes or add new files in **new_branch**

**add, commit & push the new change**

#### ⚫ Confirm there is no changes

➥   git status

##### Now all new changes are in **new_branch** not in **master**.
##### Want to merge the lastest change to **master**

#### ⚫ Go back to **master** & merge with **new_branch**

➥   git checkout **master**

➥   git merge **new_branch**

***Check the changes in **master*****

➥   git status

***Push your changes***

➥   git push origin **master**

            



***Bingoo*** you're done
