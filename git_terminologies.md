`git --version`
`git init`
`git status`


- Initialising a Repo (`git init`)
- Checking the status (`git status`)
- add the files to Git's tracking system (`git add <filename or directory>`)
  ( `git add .` ) => stages all untracked changes. 
- Staging area: This is a preview area, where you can either continue to commit or remove it before commiting.
- remove from staging area ( `git rm --cached <file>...`)
- Diff : Looking into changes of the current file. (`git diff`)
  == after tracking the files/ staging we cannot find the diff if we want the diff then we use
- cached Diff : for checking the difference of added files (`git diff --cached`)
- commiting the chages (`git commit -m "message of commit"`)
- commit log: What all changes you and your team has made (`git log`)

- what are remotes?
- Adding the remotes.
- pushing the code to remote server.(`git push`)
- Pulling the latest changes from remote server to local machine. (`git pull`)

- Different terminology
  -Branches/Tags
    - commits
      - One or More file changes (addition, deletion or updates )

- to create branch (`git checkout -b branchName`).
- to switich to another branch (`git checkout branchName`).
- list number of branches (`git branches`).
- to delete a branch. (`git branch -D branchName`).
- to update (github) that branch is deleted (`git push origin :branchName`)
- list all tags (`git tag` / `git tag -a v1.0 -m "Trying out tags"`)
- To push tags (`git push origin v1.0`)
- going back in time (`git reset --hard Head~2`) ==> learn more by doing things.


============================================================================================

Day-2:

- Introduction to Issues.
- creating an issue.
- Assigning issues to collaborators.
- Getting an issue assigned to you.
- What are pull requests?
- How to create a pull request?
- Forking a repository.
- Raising a pull request.
- Reviewing a pull request.
- Different merging strategies.
  - merge commit
  - squash commit
  - rebase
- Merging a pull request.
- choosing the right strategy.


