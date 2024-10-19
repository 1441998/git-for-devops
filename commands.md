# Git Commands Documentation

## 1. **Directory and File Operations**
- `mkdir git-for-devops`: Creates a new directory named `git-for-devops`.
- `ls`: Lists all files and directories in the current directory.
- `cd git-for-devops/`: Changes the working directory to `git-for-devops`.
- `pwd`: Displays the current working directory.
- `ls -a`: Lists all files, including hidden files.
- `touch hellodosto.txt`: Creates an empty file named `hellodosto.txt`.
- `vim hellodosto.txt`: Opens or creates the file `hellodosto.txt` for editing in Vim.
- `touch hello.txt`: Creates an empty file named `hello.txt`.
- `touch new.txt`: Creates an empty file named `new.txt`.
- `touch dev-file.txt`: Creates an empty file named `dev-file.txt`.

## 2. **Repository Initialization**
- `git init`: Initializes a new Git repository in the current directory.

## 3. **Status Check**
- `git status`: Displays the state of the working directory and the staging area. It shows changes that are staged, unstaged, or untracked.

## 4. **Staging Files**
- `git add hellodosto.txt`: Adds the file `hellodosto.txt` to the staging area.
- `git add .`: Stages all the changes (new, modified, deleted) in the current directory.
- `git add new.txt`: Stages the file `new.txt` for commit.
- `git add dev-file.txt`: Stages the file `dev-file.txt` for commit.

## 5. **Committing Changes**
- `git commit -m "adding file"`: Commits the staged changes with the message `"adding file"`.
- `git commit -m "adding new file"`: Commits the changes for `new.txt` with the message `"adding new file"`.
- `git commit -m "adding new changes in new file"`: Commits the changes for `new.txt` with the message `"adding new changes in new file"`.
- `git commit -m "adding file in dev branch"`: Commits the changes for `dev-file.txt` with the message `"adding file in dev branch"`.

## 6. **Removing and Restoring Files**
- `git rm hellodosto.txt`: Removes `hellodosto.txt` from both the working directory and the staging area.
- `git rm hello.txt`: Removes `hello.txt` from both the working directory and the staging area.
- `git rm --cached new.txt`: Unstages `new.txt` from the index but keeps the file in the working directory.
- `git restore hellodosto.txt`: Restores `hellodosto.txt` to the state from the last commit.
- `git restore hello.txt`: Restores `hello.txt` to the state from the last commit.
- `git restore new.txt`: Restores `new.txt` to the state from the last commit or staging area.

## 7. **Branch Management**
- `git branch`: Lists all branches in the repository.
- `git checkout -b dev`: Creates a new branch `dev` and switches to it.
- `git checkout dev`: Switches to the branch `dev`.
- `git checkout master`: Switches back to the `master` branch.
- `git switch master`: Switches to the `master` branch.

## 8. **Log and History**
- `git log`: Displays the commit history in reverse chronological order.
- `history`: Lists all commands executed in the current session.

## 9. **Configuration**
- `git config --global --edit`: Opens the global Git configuration file for editing.
- `git config --global user.email "syedaumerubab16@gmail.com"`: Sets the global Git email to `"syedaumerubab16@gmail.com"`.
