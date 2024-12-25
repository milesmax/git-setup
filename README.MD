# This file is intended to help setup git on a new device and act as a cheatsheet

## Installation and initialization
   >1. Install git if not already installed
   >2. Create a repository on github
   >3. Create a directory on the local machine
   >4. configure git username and email
   >5. Run git init
   >6. Run git remote add origin <URL OF GITHUB REPO>
   >7. Install github command line
   >8. Run gh auth login
   >9. Validate with credentials
   >10. git push -u origin main

   
## Pull Request

>Step 1. Clone the repo / update local repo with 
>latest changes
>
>       `git pull origin main`
>    
>Step 2. Switch to the  base branch of the pull request
>
 >      `git checkout main`
>
>Step 3. Merge the head branch into main branch
> 
>       `git merge test-branch`
>
>Step 4. Push the changes
> 
>       `git push -u origin main`


## Delete from local branch

>       `git branch -d <branch-name>`

## Delete remote branch from local CLI

>       `git push -d <remote_name> <branchname>`
  >*In most cases the remote name will be origin*


## Excluding files from git

>.gitignore will ignore files that are ADDED 
> to git
> 
> Place .gitignore in main file directory
> 
> 
>
>Files already in the repo must be removed
>
> *Make sure to .gitignore them too*
>### Remove currently tracked file
>     `git rm --cached <file-path>`


