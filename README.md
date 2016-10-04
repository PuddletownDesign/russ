# Git

Git is a distributed versioning tool.


## Versioning

Get the SHA from running `git log` after reset HEAD goes back to previous commit. Can be used to reset to a previous commit in your commit history.

**example: `git reset 5d692065cf51a2f50ea8e7b19b5a7ae512f633ba`**


`reset` - resets from an SHA
	
Unstages file changes in the staging area.

**example `git reset HEAD [filename]`**


`reset HEAD [filename]`

Discards changes in the working directory.

`checkout HEAD [filename]`

Shows the most recent commit

	
`git show HEAD`

checks out the last unstaged version of the file

	
`git checkout HEAD [filename]`



## Git branching

Lists all a Git project's branches.

`git branch`:

Creates a new branch.

`git branch [branch_name]`

Deletes a branch

`git branch -d [branch_name]`

Used to switch from one branch to another.

`git checkout [branch_name]`

Checkout a remote branch from origin

`git checkout -b test origin/test`

Used to join file changes from one branch to another.

`git merge [branch_name]` 

Deletes the branch specified.


`git branch -d branch_name` 

## Git Remote

Creates a local copy of a remote.

`git clone [remote_repo] [folder_to_clone_into]`

pulls down changes in the remote but doesn't merge them.

`git fetch`

performs a fastward style merge, bringing local repo up to the current remote commit.
	
`git merge origin/master`

Lists a Git project's remotes.	
	
`git remote -v`

Fetches work from the remote into the local copy.

`git fetch` 

Pushes a local branch to the origin remote.

`git push origin [branch_name]`


## Repositories w/ GitHub:

1. create repository link at GitHub website.
2. git clone <address> while in the destination directory.
3. cd /reposName/
4. git remote -v (shows push and pull repos)
5. git pull --all (before creating branches AS MASTER)
6. git checkout -b "title" (creates branch and goes)
7. git checkout "title" (switches branches)
8. git add "filename" (adds file to staging area)
9. git commit -m "added documentation"
10. git push "repos" "title"
	* mv README.md task.md && touch README.md


