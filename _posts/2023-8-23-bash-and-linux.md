---
toc: true
comments: true
layout: default
title: Custom To-Do list
description: This is a to-do list generator to get used to html, css, and js
courses: { csa: {week: 1} }
type: hacks
---

## Common Bash/Linux commands

```
cd <direc name > # to get into a specific directory
cd .. # to get to previous directory in heptarchy
cd # to get to home directory
ls # to list out items in a directory

sudo <command> # to run as administrator *caution

git pull # update local repository with branch associated with from github 
git checkout <branch name> # to change to a diffrent branch
git checkout  -b <brnach name> # to create a new branch with certain name
git push # to "push" or send changes to github or similar services
git commit <commit message> # to commit changes

pip --version # to check the version of python
java --version # to check version of openjdk

```

## Review Versions
- To review versions of installed packages usually the command should work - 
```
<package> --version
```

"sudo" may be needed

## Update repository through git command line

```
# first commit changes
git commit <commit message>
# Then either stash or rebase with changes from branch if conflicts
git stash
git pull
# OR
git pull --rebase
git push


## If you want to save changes you can also send changes to a new branch
git branch -b <branch name>
git push
# and when you want these changes in the main branch just send a merge request from github itself 
```