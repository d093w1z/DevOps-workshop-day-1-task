## DevOps and Cloud Automation workshop at PCCOER - Xenstack

### Command list:

#### Git:
- `git init` : Initialise current directory for git.
- `git clone <repo url>` : Clone the repo and create a local repo.
- `git add -A` : Stage all changes made in the current repo.
- `git commit` : Commits the staged changes. Opens an editor to specify commit message.
- `git commit -m "commit message"` : Same as `git commit` but does not open the text editor. Instead uses the specified message `"commit message"`.
- `git status` : List which files are staged, unstaged, and untracked.
- `git log` : Displays repo history.
- `git diff` : Shows changes between commits
- `git reset` : Resets the staging area but keeps the files as is.
- `git checkout -- <filename>` : Discard all unstaged changes in `filename`.
- `git branch` : List all brances
- `git branch <branchname>` : Create branch
- `git checkout <branch name>` : Switch current branch to `branchname`
- `git merge <branchname>` : Merge `branchname` with current branch
- `git branch -d <branchname>` : Deletes branch specified by `branchname`.
- `git push --set-upstream <remote name> <branch>` :
- `<any command in git> -h` : Shows help for that git command

#### Vagrant:
- Default login creds:
   - username: `vagrant`
   - password: `vagrant`
- `vagrant init` : initialises current directory with default VM box.
- `vagrant init <name>` : initialises current directory with specified VM box.
- `vagrant up` : Starts the VM box.
- `vagrant ssh` : SSH login shell for VM box.
- `vagrant status` : Displays status of current VM box.
