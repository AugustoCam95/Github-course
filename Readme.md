# Github course

A short text file for a course of git remenber to create a paste for it( use mkdir git-course, for example).

## Initial configurations

```
git config --global user.name "name"
git config --global user.email email@example.com
git config --global core.editor editor
```

use "git config --list" to see your configurations

### Start a repo

```
 git init
 git status
 git add <file1>...<fileN>
 git status
 git commit -m "menssage"
 git push -u origin master 
```

Use "git status" to see any modifications or updates


### Visualize commits

```
	git log
	git log -graph
	git log --decorate
	git log --author="name"
	git shortlog
	git shortlog -sn
	git show (commit code) 
```

### Changes on files

´´´
	git diff
	git diff --name-only
´´´

### Removing changes

´´´
	git reset HEAD (file)
	git checkout (file)
	git reset --soft
	git reset --mixed
	git reset --hard
´´´

## Main book
* [Git book](https://git-scm.com/book/en/v2) - The Git Book
