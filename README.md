# Basic Git Commands

```bash
# Initialize Repository
git init

# Clone Repository
git clone <repository-url>

# Stage Changes
git add <file>         # Stage a specific file
git add .              # Stage all changes

# Commit Changes
git commit -m "commit message"

# Check Status
git status

# View Commit History
git log

# Branch Management
git branch                   # List all branches
git branch <branch-name>     # Create a new branch

# Switch Branch
git checkout <branch-name>

# Merge Branch
git merge <branch-name>

# Pull from Remote
git pull

# Push to Remote
git push

# View Remote Repositories
git remote -v

# Stash Changes
git stash

# Reset
git reset --hard             # Discards all changes in the working directory
