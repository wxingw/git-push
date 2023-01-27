# Find leftover .git folder in some sub directories 

find ./ -name '.git'

# Delete it

rm -r yourfolder/.git/

# Use the init command to initialize the local directory as a Git repository

git init -b main

# Sets the new remote

git remote add origin https://github.com/wxingw/git-push.git

# Verifies the new remote URL

git remote -v

# Add the files in your new local repository. 

git add READM.md

# Commit the files 

git commit -m "update README.md"

# Pushes the changes

git push -f origin main
