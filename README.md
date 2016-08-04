# test-repo
Basics about git and GitHub.

## Start repository from scratch
In GitHub:
* Select "Create new repo"
* Create a name for your repo and write a brief description
* Select "public" or "private"
* Check the box to "initialize with a README"
* Click the "create repository" button

In your computer:
* Create folder with the same name than the repo on GitHub
* Navigate to this new directory
* Initialize a local Git repo: > git init
* Point your local repo at the remote repo in GitHub: git remote add origin https://github.com/anna-alemany/name-repo.git

## Fork another user's repo
In GitHub:
* Fork

To make a local copy in your computer (clone):
* Navigate to the desired directory, where we want the repo to appear, and type: > git clone https://github.com/anna-alemany/name-repo.git
** ATENTION: no need to create the directory with the name of the repo. It will be cloned automatically.

## Changes on repository
* Add: git add . // git add -u // git add -A
* Commit: git commit -m "message"
* To push changes into remote repo: git push
* Create branch: git checkout -b branchname
* To see which branch are you in: git branch
* To switch back to the master branch: git checkout master
