## git-explore

`ssh-keygen -t ed25519 -C "skyinnk.tech@gmail.com"`

[Click here to download the latest version of Git](https://git-scm.com/)

`git --version` to find git version

`git-update-git-for-windows` dounload and install sellect defult

`.git ignore`

`git remote remove origin` To remove a remote origin in Visual Studio Code,
`git remote -v` To Verify that the remote origin has been removed by running

## basic- first steps

> Initialize a local Git repository

`git init` - Initialize a local Git repository

> Remove Git from a specific repository or directory

- For Windows Command Prompt

`rd /s /q .git`

- For Git Bash or Unix-like terminals (Linux/macOS)

`rm -rf .git`

> git working

- `git status` Check status
- `git add -A` or `git add .` Add all new and changed files to the staging area

- `git add [file name]` Add new files to the staging area ex:`git add style.css` Add the 'style.css' to the staging area

- `git rm --cached quote.js` unstage a file (or folder)
- `git rm -f new.html ` delete a file (or folder) after adding

- `git commit -m "the first commit"` Commit changes

- `git log` View changes
- `git log --summary` View changes (detailed)
- `git log --oneline` View changes (briefly)

- `git checkout [comit id]` switching to '5987ccb' commit
- `git checkout [master]` switching to master
- `git switch master` or

## NOTE

…or create a new repository on the command line

- echo "# git-testnote" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M master
- git remote add origin git@github.com:skyGwork/git-testnote.git
- git push -u origin master

…or push an existing repository from the command line

- git remote add origin git@github.com:skyGwork/git-testnote.git
- git branch -M master
- git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

## Getting & Creating Projects

- `git clone ssh://git@github.com/[username]/[repository-name].git` - Create a local copy of a remote repository i.e `git@github.com:skyGwork/css-sass-masterclass.git`

- `git branch` List branches (the asterisk denotes the current branch)

- `git branch -a` List all branches (local and remote)
- `git branch [branch name]` Create a new branch
- `git branch -d [branch name]` Delete a branch
- `git push origin --delete [branch name]` Delete a remote branch

- `git checkout -b [branch name]` Create a new branch and switch to it

- `git checkout -b [branch name] origin/[branch name]` Clone a remote branch and switch to it
- `git branch -m [old branch name] [new branch name]` Rename a local branch
- `git checkout [branch name]` Switch to a branch
- `git checkout -` Switch to the branch last checked out
- `git checkout -- [file-name.txt]` Discard changes to a file

- `git merge [branch name]` Merge a branch into the active branch
- `git merge [source branch] [target branch]` Merge a branch into a target branch

- `git stash` Stash changes in a dirty working directory
- `git stash clear` Remove all stashed entries

- `git push origin [branch name]` Push a branch to your remote repository
- `git push -u origin [branch name]` Push changes to remote repository (and remember the branch)
- `git push` Push changes to remote repository (remembered branch)
- `git push origin --delete [branch name]` Delete a remote branch
- `git pull` Update local repository to the newest commit
- `git pull origin [branch name]` Pull changes from remote repository

- `git remote add origin ssh://git@github.com/[username]/[repository-name].git` Add a remote repository
- `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` Set a repository's origin branch to SSH
- `git diff [source branch] [target branch]` Preview changes before merging
