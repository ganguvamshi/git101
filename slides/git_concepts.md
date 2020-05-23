## Git: Repository
A _repository_ or _repo_ is a collection of
- files
- folders
- history
- all your commits
- place where all your hard work is stored


## Git: Repository
- Can live on local/remote server (_GitHub_/_Gitlab_/_bitbucket_)
- `Clone`: copying remote server to local machine
- `push`: pushing your local changes to remote server
- `pull`: pulling the new changes from remote to local


## Git: Snapshots 
- The way git keeps tracks of your code history
- Records all how your files looks like at a given point in time
- can go back to visit any snapshot


## Git: Staging
- Once changes are done, files are added to staging area before commiting
- can unstage/stage the files before commiting
  


## Git: Commit
- Process of creating snapshot
- A project is made up of bunch of commits
- Each commit has 3 pieces
  - Information about how files are changed
  - reference to the parent commit
  - hash code name (like: `fb23adafeafa.....`)


## Git: Branches
- All commits live on some branch
- Multiple branches can be created to work on
- The main branch in a project is called the `master` branch
- A new branch is created before starting to work on a new feature, and later merged into the `master` branch once the development is finished on that branch
- both local/remote have their own branches.
