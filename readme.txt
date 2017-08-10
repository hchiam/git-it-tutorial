Hello!
Aloha!

KEY COMMANDS: http://jlord.us/git-it

mkdir <FOLDERNAME>
cd <FOLDERNAME>
ls
git init

git status
git diff
git add <FILENAME>
git add .
git commit -m "<your commit message>"

git config --global user.username <USerNamE>

git remote add <REMOTENAME> <URL>
git remote set-url <REMOTENAME> <URL>
git pull <REMOTENAME> <BRANCHNAME>
git remote -v
git push <REMOTENAME> <BRANCH>

git remote add <REMOTENAME> <URL>
git remote -v

# BRANCHING:
git branch <BRANCHNAME>
git checkout <BRANCHNAME>
# or just:
git checkout -b <BRANCHNAME>
# list of branches:
git branch
# rename branch currently on:
git branch -m <NEWBRANCHNAME>

# SEE/PULL COLLABORATOR CHANGES
git status
# Pull in changes from a remote branch
git fetch --dry-run
# See changes to the remote before you pull in (I used origin as <REMOTENAME>)
git pull <REMOTENAME> <REMOTEBRANCH>

# Merge a branch into current branch:
git merge <BRANCHNAME>
# Change the branch you're working on
git checkout <BRANCHNAME>
# Delete a local branch
git branch -d <BRANCHNAME>
# Delete a remote branch (I used origin as <REMOTENAME>:)
git push <REMOTENAME> --delete <BRANCHNAME>
# Pull from a remote branch
git pull <REMOTENAME> <BRANCHNAME>
