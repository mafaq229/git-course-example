# Example Git Repository

We are learning how to make commits

1. make some changes
2. git add filename.py -- "stage" the changes that we want to persist to our git history
3. git commit -m "adding ..." -- creates a commit

# created the repo locally
local repository -> "remote" repository (git add remote <name> <URL>)

# created the repo remotely
git clone <URL>

# create a branch locally
git checkout <branch>
git checkout -b <new branch>
git add...; git commut -m "..." (several times)
git push --set-upstream origin <new branch>
git pull [origin <new branch>]

# create a new branch remotely
using the GitHun UI to create <branch>
git fetch --all
git checkout <branch>