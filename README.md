
### 1. **Create a Local Git Repository**
```bash
# Initialize a new Git repository
git init
```

### 2. **Configure Your Git Identity**
```bash
# Set your global username
git config --global user.name "Your Name"

# Set your global email address
git config --global user.email "youremail@example.com"
```

### 3. **Create a Remote Repository on GitHub**
- Go to GitHub and create a new repository. You'll be provided with a URL to clone or push your repository.

### 4. **Add a Remote Repository (Link Local to GitHub)**
```bash
# Add a remote repository to your local repository
git remote add origin https://github.com/username/repository-name.git
```

### 5. **Check the Status of Your Repository**
```bash
# Check the status of your working directory (shows untracked, modified files, etc.)
git status
```

### 6. **Add Files to Staging**
```bash
# Add all files to the staging area
git add .

# Add a specific file to the staging area
git add filename
```

### 7. **Commit Changes**
```bash
# Commit your changes with a message
git commit -m "Your commit message"
```

### 8. **Push Changes to GitHub**
```bash
# Push changes to the remote repository (GitHub)
git push -u origin master

# Push changes to the specific branch
git push origin branch-name
```

### 9. **Pull Changes from GitHub**
```bash
# Fetch and merge changes from the remote repository (GitHub) to your local repository
git pull origin master

# Pull changes from a specific branch
git pull origin branch-name
```

### 10. **Clone a Repository from GitHub**
```bash
# Clone a remote GitHub repository to your local machine
git clone https://github.com/username/repository-name.git
```

### 11. **Create a New Branch**
```bash
# Create a new branch and switch to it
git checkout -b new-branch-name
```

### 12. **Switch Branches**
```bash
# Switch to an existing branch
git checkout branch-name
```

### 13. **Merge Branches**
```bash
# Merge a branch into the current branch
git merge branch-name
```

### 14. **View Commit History**
```bash
# View the commit history of your project
git log
```

### 15. **Delete a Branch Locally**
```bash
# Delete a local branch after it has been merged
git branch -d branch-name
```

### 16. **Delete a Remote Branch**
```bash
# Delete a branch from the remote repository (GitHub)
git push origin --delete branch-name
```

### 17. **View Remote Repositories**
```bash
# List all remote repositories
git remote -v
```

### 18. **Revert to a Previous Commit**
```bash
# Revert to a previous commit (hard reset to a specific commit)
git reset --hard commit-hash
```

### 19. **Undo Local Changes (Unstaged)**
```bash
# Discard changes in the working directory (unstaged)
git checkout -- filename
```

### 20. **Undo Staged Changes**
```bash
# Unstage a file (moves from staged to untracked state)
git reset filename
```
