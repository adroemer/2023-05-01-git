
# 2023-05-01-git

- 'git init':initialize git repository (repo)
	- do not nest git repos
- 'git status' : tells you things about what's going on in the repository
- add is the process to add a file to the Git staging area
- commit is the process to save the files from the Git staging area to the version control
	- 'git commit -m "MY MESSAGE" : quick oneliner message 
- 'git log' : log view with the full log
	- git log --oneline  : one line view
	- 'git log --oneline -all' : shows all of log, not just HEAD

- 'HEAD': tells you where you are
- 'git diff' : shows you new changes to the repo
	- 'git diff --staged' : shows you changes in the staging area
	- 'git diff <HASH> <FILE> :compare two states in the repo
- 'git checkout <HASH>': move HEAD to <HASH>
	- YOU WILL BE IN a detached HEAD state
	-'git switch main': switches back to main HEAD
- 

