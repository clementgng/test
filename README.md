#test
This is a report for my test webpage

use touch to create files
	ex- touch index.html
	
use mkdir to create directories same as unix(touch doesn't allow to create directories)

git init
	initializes an empty repo
	
git config [--global] user.[name/email] 'name/email here'
	user config??

git add [*/.]
	similar to check out in P4, git add will checkout changes to be committed
	
git status
	view status of changes
	
git rm [--cached] [-r] [-f]
	git rm --cached will remove file(s) from pending changelist
	use -r for recursive
	use -f for force..
	use -rf to DELETE AND REMOVE files
	
git commit [-m 'commit message']
	use -m to commit and add commit comment ex git commit -m 'add new file called junk.txt'
	
git ls-tree -r [branch name]
	view all non-hidden files/folders in branch
	
git remote add [name goes here] [link to github.com punlic repo]
	mark for add from local git repo to github.com public repo
	ex- git remote add origin https://github.com/clementgng/test

	git push -u [name goes here] [master]
	
git clone [repo name]
	clone a repo to a new folder(must be under new folder)
	
git pull
	grab latest revisions from repo