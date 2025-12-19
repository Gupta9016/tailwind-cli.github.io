# Local to Remote Repo

## Method 1

```bash
# Create a git repo
git repo create

# Clone the remote repo
git clone <link>

# Add all files or specific file(s)
git add .

# Or add a specific file
git add <filename>

# Commit changes with a message
git commit -m "msg"

# Push changes to the main branch
git push origin main


## Method : 2
git init

# Add remote repository link
git remote add origin <paste-link>

# Add all files
git add .

# Commit changes with a message
git commit -m "tailwind-cli"
git push


git branch ---> check branch
git branch <branchname> -->new branch
git checkout <branchname>--> to navigate between branch


# Push changes to the main branch
git push origin main
