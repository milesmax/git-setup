This file is intended to help setup git on a new device

Steps
1. Install git if not already installed
2. Create a repository on github
3. Create a directory on the local machine
4. configure git username and email
5. Run git init
6. Run git remote add origin <URL OF GITHUB REPO>
7. Install github command line
8. Run gh auth login
9. Validate with credentials
10. git push -u origin main

PULL REQUEST

Step 1. Clone the repo / update local repo with latest changes
git pull origin main

Step 2. Switch to the  base branch of the pull request
    git checkout main

Step 3. Merge the head branch into main branch
git merge test-branch

Step 4. Push the changes
git push -u origin main

DELETE LOCAL BRANCH
git branch -d <branch-name>

DELETE REMOTE BRANCH FROM LOCAL CLI

1. git push -d <remote_name> <branchname>
2. In most cases the remote name will be origin