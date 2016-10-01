# Review time

> spark the wicks an', However I master the trick just like Nixon - Raekwon


## Things to look out for

Keep taking and organizing more notes. Gotta keep a solid reference for yourself through this. All of these readme files are lacking a little bit. Keep the markdown notepad open!

I've made each of these into a trello task. Check em off as you go along.

## Tasks

### 01-git

Well I've renamed all the branches... You gonna have to deal with that. Protip: you can just delete the old ones in this case. However you have to pull and rebranch them all.

https://github.com/PuddletownDesign/russ/blob/01-git/task2.md

### 02-vim

Just work on filling this in while you learn vim and get your snippets dialed in.

https://github.com/PuddletownDesign/russ/blob/02-vim/README.md

### 03-html-basic

https://github.com/PuddletownDesign/russ/blob/03-html-basic/task2.md

### 04-markdown

https://github.com/PuddletownDesign/russ/blob/04-markdown/task2.md

### 05-css-basic

https://github.com/PuddletownDesign/russ/blob/05-css-basic/task2/task2.md




## Repositories w/ GitHub:

	1. create repository link at GitHub website.
	2. git clone <address> while in the destination directory.
	3. cd /reposName/
	4. git remote -v (shows push and pull repos)
	5. git pull --all (before creating branches AS MASTER)
	6. git checkout -b "title" (creates branch and goes)
	7. git checkout "title" (switches branches)
	8. git add "filename" (adds file to staging area)
		* ```git add .``` also works
	9. git commit -m "added documentation"
	10. git push "repos" "title"
		*mv README.md task.md && touch README.md

### main concept commands:
	* git branch
	* git branch branch_name
	* git checkout branch_name
	* git checkout -b branch_name
	* git merge branch_name
	* git branch -d branch_name
=======
# Git

Git is a distributed versioning tool.


## Versioning

`reset` - resets from an SHA
	
Get the SHA from running `git log` after reset HEAD goes back to previous commit. Can be used to reset to a previous commit in your commit history.

**example: `git reset 5d692065cf51a2f50ea8e7b19b5a7ae512f633ba`**
	
`reset HEAD [filename]` - Unstages file changes in the staging area.
	
`checkout HEAD [filename]` - Discards changes in the working directory.
	
`git show HEAD` - Shows the most recent commit
	
`git checkout HEAD [filename]` - checks out the last unstaged version of the file


## Git branching

`git branch` - Lists all a Git project's branches.

`git branch [branch_name]` - Creates a new branch.

`git branch -d [branch_name]` - Deletes a branch

`git checkout [branch_name]` - Used to switch from one branch to another.

`git merge [branch_name]` - Used to join file changes from one branch to another.

`git branch -d branch_name` - Deletes the branch specified.
	

## Git Remote

`git clone [remote_repo] [folder_to_clone_into]` - Creates a local copy of a remote.

`git fetch` - pulls down changes in the remote but doesn't merge them.
	
`git merge origin/master` - performs a fastward style merge, bringing local repo up to the current remote commit.
	
`git remote -v` - Lists a Git project's remotes.

`git fetch`  - Fetches work from the remote into the local copy.

`git push origin [branch_name]` - Pushes a local branch to the origin remote.


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

