# Git Commands Notes

### 1. **Create a New Directory**
   - `mkdir git-for-devops`: This creates a folder called `git-for-devops`.

### 2. **List Files**
   - `ls`: Shows all files and folders in the current directory.

### 3. **Change Directory**
   - `cd git-for-devops/`: Moves you into the `git-for-devops` folder.

### 4. **Print Working Directory**
   - `pwd`: Displays the full path of your current location.

### 5. **Initialize a Git Repository**
   - `git init`: Turns the current folder into a Git repository, allowing you to track changes.

### 6. **List All Files (Including Hidden Ones)**
   - `ls -a`: Shows all files, including hidden ones (starting with `.`).

### 7. **Create/Edit a File Using Vim**
   - `vim hellodosto.txt`: Opens or creates `hellodosto.txt` in the Vim text editor for editing.

### 8. **Check Git Status**
   - `git status`: Shows the current state of your files in Git, such as which ones are modified or untracked.

### 9. **Create a New File**
   - `touch hellodosto.txt`: Creates an empty file named `hellodosto.txt`.

### 10. **Stage a File for Commit**
   - `git add hellodosto.txt`: Stages the file `hellodosto.txt`, making it ready for commit.

### 11. **Commit Changes**
   - `git commit -m "adding file"`: Saves your changes with a message (`"adding file"`) that describes the update.

### 12. **Edit Global Git Configuration**
   - `git config --global --edit`: Opens the global Git configuration file, where settings like your name and email are stored.

### 13. **Remove a File from Git**
   - `git rm hellodosto.txt`: Deletes `hellodosto.txt` from both the working directory and Git tracking.

### 14. **Restore a File from the Last Commit**
   - `git restore hellodosto.txt`: Undoes changes to `hellodosto.txt`, returning it to the state from the last commit.

### 15. **Set Git Email**
   - `git config --global user.email "syedaumerubab16@gmail.com"`: Sets your email for Git globally (for all repositories).

### 16. **Create Another File**
   - `touch hello.txt`: Creates an empty file named `hello.txt`.

### 17. **Stage All Changes**
   - `git add .`: Stages all changes in the current directory (new files, deletions, modifications).

### 18. **Remove a File**
   - `git rm hello.txt`: Deletes `hello.txt` from both the working directory and Git tracking.

### 19. **Create Another File**
   - `touch new.txt`: Creates an empty file named `new.txt`.

### 20. **Stage the New File**
   - `git add new.txt`: Stages the file `new.txt` to be committed.

### 21. **Commit the New File**
   - `git commit -m "adding new file"`: Saves the changes with a message `"adding new file"`.

### 22. **Unstage a File (Keep in Working Directory)**
   - `git rm --cached new.txt`: Unstages `new.txt` (removes it from Git tracking) but keeps it in the directory.

### 23. **Restore an Untracked File**
   - `git restore new.txt`: Attempts to restore the untracked file `new.txt` (works if previously tracked).

### 24. **View Commit History**
   - `git log`: Shows the list of commits made in the repository.

### 25. **Edit a File Using Vim**
   - `vim new.txt`: Opens or creates `new.txt` for editing in Vim.

### 26. **Commit Changes to a File**
   - `git commit -m "adding new changes in new file"`: Commits updates to `new.txt` with the message `"adding new changes"`.

### 27. **View All Branches**
   - `git branch`: Lists all branches in the repository.

### 28. **Create and Switch to a New Branch**
   - `git checkout -b dev`: Creates a new branch named `dev` and switches to it.

### 29. **Create Another File**
   - `touch dev-file.txt`: Creates an empty file named `dev-file.txt`.

### 30. **Stage the File for Commit**
   - `git add dev-file.txt`: Stages the file `dev-file.txt` for commit.

### 31. **Commit the New File**
   - `git commit -m "adding file in dev branch"`: Commits the changes with the message `"adding file in dev branch"`.

### 32. **Switch to the Master Branch**
   - `git switch master`: Changes back to the `master` branch.

### 33. **Switch Between Branches**
   - `git checkout dev`: Switches to the `dev` branch.
   - `git checkout master`: Switches back to the `master` branch.
