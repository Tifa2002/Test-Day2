# How to Remove Branches Locally
git branch -d dev
git branch -d test

# How to Remove Branches Remotely
git push origin --delete dev
git push origin --delete test

# How to checkout another branch without commit changes 
git stash
git checkout <branch-name>
git stash apply

# How to list tags
git tag

# How to delete tag locally and remotely
Locally : git tag -d v1.7
Remotely : git push origin --delete v1.7

# Profile Image


