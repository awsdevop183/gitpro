**Git is a version control system.**

**Git for DevOps Engineers**

**Git Commands**

# Add file or files to staging

git add . or git add file_name
# Use below command to save changes 
git commit -m "Commit Message"

# Print commit logs in oneline
git log --oneline

# Use status to check files or status
git status
# Use push to update changes in remote repository
git push origin main

### Use .gitignore file to ignore files and folders

# Level One heading
## Level Two heading
### Level Three heading

# Rename Git branch Madhu to Jaffa
git branch -M madhu jaffa


# Add remote repository to your repository

git remote add origin "url comes here"

# Update remote url 

git remote set-url origin new.git.url/here

# Use force command to forcefully replace commits( be cautious while using this command)
# Use this command if you are 100% sure about what you are doing

git push --force