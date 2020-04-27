# 2020 04-27 Git Basics class 
..
- init : create a git repository in current directory
	 you should do this only once in a repository (i.e., no nested git repos)
- status : tels you whats  going on with the current repository
- add : adds file to the staging area
- commit : commits the changes to the repository
	`commit -m` : it allows you to put message and bypass the editor
	`commit -am" : it adds and commits the file at the same time"
- log : look at all the commit history you have been doing
    - log --online : simple online log view
- 'diff' : look at differencess between current status and what git knows
-  'checkout' : moving our head 
- 'HEAD' : place we are looking at right now on our computer

- remote : This is the place where git repo is stored (ex: github)
  - 'git remote add origin <url>' - to add repo to origin
  - 'git push origin master' from our pc to remote (origin)

