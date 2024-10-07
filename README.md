Here’s a list of basic Git commands with a brief explanation of what each one does:

### 1. **`git init`**
   - Initializes a new Git repository in the current directory.
   - Example: 
     ```bash
     git init
     ```

### 2. **`git clone`**
   - Clones (copies) an existing repository (usually from a remote source) into a local directory.
   - Example: 
     ```bash
     git clone https://github.com/username/repository.git
     ```

### 3. **`git status`**
   - Displays the state of the working directory and the staging area (shows tracked/untracked files, changes ready to commit, etc.).
   - Example: 
     ```bash
     git status
     ```

### 4. **`git add`**
   - Adds changes from the working directory to the staging area (to prepare for commit).
   - Example:
     ```bash
     git add <file>      # Adds a specific file
     git add .           # Adds all files
     ```

### 5. **`git commit`**
   - Records/stages the changes that were added using `git add` to the local repository. A commit message is usually required.
   - Example:
     ```bash
     git commit -m "Commit message here"
     ```

### 6. **`git log`**
   - Shows a list of all previous commits in the repository with details (e.g., author, date, commit message).
   - Example:
     ```bash
     git log
     ```

### 7. **`git branch`**
   - Lists all local branches in the repository. You can also use it to create new branches.
   - Example:
     ```bash
     git branch          # Lists all branches
     git branch <branch> # Creates a new branch
     ```

### 8. **`git checkout`**
   - Switches between branches or restores files in the working directory to a specific state.
   - Example:
     ```bash
     git checkout <branch>   # Switches to a branch
     git checkout <file>     # Restores file to a specific commit state
     ```

### 9. **`git merge`**
   - Merges changes from one branch into the current branch.
   - Example:
     ```bash
     git merge <branch>
     ```

### 10. **`git pull`**
   - Fetches changes from the remote repository and merges them into the local repository (effectively doing `git fetch` followed by `git merge`).
   - Example:
     ```bash
     git pull origin main
     ```

### 11. **`git push`**
   - Pushes changes from the local repository to the remote repository.
   - Example:
     ```bash
     git push origin main
     ```

### 12. **`git remote`**
   - Manages remote repository references (e.g., list, add, remove remote repos).
   - Example:
     ```bash
     git remote -v          # Lists remotes
     git remote add origin https://github.com/user/repo.git
     ```

### 13. **`git diff`**
   - Shows the differences between your working directory and the staging area, or between commits.
   - Example:
     ```bash
     git diff               # Shows unstaged changes
     git diff --staged      # Shows staged changes
     ```

### 14. **`git fetch`**
   - Fetches changes from the remote repository but does not merge them into the local branch (unlike `git pull`).
   - Example:
     ```bash
     git fetch origin
     ```

### 15. **`git reset`**
   - Unstages changes or reverts commits. Used to modify the state of the current branch and undo changes.
   - Example:
     ```bash
     git reset <file>       # Unstages a file
     git reset --hard       # Resets the entire working directory to the last commit
     ```

### 16. **`git rm`**
   - Removes files from the working directory and stages their deletion.
   - Example:
     ```bash
     git rm <file>
     ```

### 17. **`git stash`**
   - Temporarily saves changes in a dirty working directory so you can work on something else, then reapply them later.
   - Example:
     ```bash
     git stash              # Stashes changes
     git stash pop          # Applies stashed changes
     ```

### 18. **`git rebase`**
   - Reapplies commits from one branch onto another. This is often used to keep a feature branch up to date with changes in the main branch.
   - Example:
     ```bash
     git rebase <branch>
     ```

### 19. **`git tag`**
   - Adds a tag to specific commits (often used for marking releases).
   - Example:
     ```bash
     git tag v1.0
     git push origin v1.0   # Pushes tag to remote
     ```

### 20. **`git revert`**
   - Creates a new commit that undoes the changes introduced by a previous commit (without removing that commit from history).
   - Example:
     ```bash
     git revert <commit>
     ```

These basic commands will help you navigate most daily tasks with Git!
