## Few essential git command

# Intialise a local/remote repository
Option 1|Option 2
---|---
Existing local repository | Remote repository hosted on Gihub
`git init` initialise local folder <br/> adds .git folder | `git clone ssh_url` clone remote repository to local file system <br/> adds .git folder </br> adds remote

# Track changes in local repo
need to add file to index/staging area

# Commit changes
`git commit` 

# Push changes to remote repository on github
`git push` if the project was setup using git clone as git will already know where to push the files on github.
else
`git remote add origin ssh_url` You need to create your new remote repository on Github and then use the command.

# Copy changes from the remote to your local computer.
git pull

## Branches
