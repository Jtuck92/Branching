## Git Cheatsheet

Summary of useful `git` commands.

### Basic Commands
* `git init` - Initialize local git repository
* `git status` - Show status of working directory
* `git add .` - Add everything in current directory
* `git commit -m "Some Message"` - Commit current work to local repository
* `git log` - Show git commit history
* `git log --oneline` - Show git commit history (compact)
* `git config -l` - List git configuration

### Branching Commands
* `git branch` - List branches in current repository
* `git branch someBranch` - Create branch `someBranch`
* `git checkout someBranch` - Move to branch `someBranch`
* `git checkout -b otherBranch` - Create and checkout `otherBranch`
* `git pull origin main` - Pull remote `main` into current branch
* `git push origin newBranch` - Push current committed branch to remote

### Remote Commands
* `git remote add origin URL` - Set remote repo alias `origin` for github `URL`
