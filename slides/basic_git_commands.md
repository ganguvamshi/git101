## Git process

Here we see how a typical git process looks like 

### Initialize/Clone a repo
- `git init` : initialized a brang new Git repo and begins tracking an existing directory
- `git clone`: creats a local copy of a remote project. It includes all project files, history and branches


### Adding files to staging
- once the changes are done, files are added to the staging 
- `git add` stages a change. 
- necessary to stage and take snapshot of the changes to include them in history
- `git add file1.txt` stages a particular file(s)
- `git add .` stages all modified/changed files


### Creating Snapshot
- `git commit` saves the snapshot to the project history and completes the change-tracking process
- `git commit -m "your message" ` adds the message to the commit.
-  _tip_ : create descriptive message to reflect the changes done. 


### Checking status
- `git status` shows teh status of changes as untracked, modified or staged
- `git status -s` can be used for short hand status messages
- `git log` show all the history of all the snapshots and commits of your repo
 


### create branches
- `git branch` shows all the local branches
- `git branch <branch name>`: creates a new branch
- `git checkout <branch name>`: for changing into a specific branch


### merging branches
- `git merge <branch name>` merges the dev code of <branch name> into `master` branch
- you need to be in `master branch` for merging <branch name> into master branch
- Typically, when using GitHub, you push the local changes to remote branch (possibly to the same branch name) and raise a `merge request` for merging into `master` branch


### pulling changes
- `git pull` updates the local repo from its remote counterpart. 
- use this command to fetch the new changes made by other teammates to the remote repo and you can reflect those changes into your local environment


### pushing changes
- `git push` updates the remote repository with nay commites made locally to branch.

check here for more information of [Git commands](https://git-scm.com/docs)