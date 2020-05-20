## Git Cheat Sheet

### Information Commands
* `git status` - status of current git repo
* `git config -l` - List configuration of repo
* `git config --list` - List configuration of repo
* `git log` - Log of commits in this repo
* `git log --oneline` - Compact log listing
* `git branch` - Display branch info

### Basic Commands
* `git init` - Initialize a repo in current working directory
* `git add .` - Stage current directory for commits
* `git commit -m "stuff"` - Commit staged data, with message "stuff"
* `git commit` - Commit staged data, enter message in vi editor

### Branching Commands
* `git branch branchName` - Create branch `branchName`
* `git checkout branchName` - Go to branch `branchName`
* `git checkout -b branchName` Create and checkout `branchName`
* `git pull origin master` - Pull `master` branch into current branch
