# Learning Git and GitHub

* Note: Looking up 'git cheatsheet' on duckduckgo turns up a useful list of commands!
* These are the notes I took while learning my way around Git. This is my first Git repository!  

## Git notes
* $ touch <file_name> : creates a file with the specified name in the working folder. This is a bash command.
* $ git init : initializes a repository
* $ git add <file_name> : adds the specified name to the repository
* $ git status : shows which files are currently in the repository.
* $ git rm --cached <file_name> : removes the file from the repository, but keeps it in the working folder
* $ git add *<file_extension> : adds all the files with the extension to the staging area
* $ git add . : adds all the files to the staging area.

Note that if you modify a file in the staging area, you will need to add it again!

## Commit

$ git commit : commits all the files in the staging area.
//Easier way to commit:
$ git commit -m 'You can add comments in quotes'

$ git ignore : creates a space where files to be ignored can be added. We can include any file or folders to .gitignore.

## Create a branch
* $ git branch <branch_name>
* $ git checkout <branch_name> : switch to the branch
	$ git checkout master : switch to the master branch

Branches can be merged with the master with git merge
* $ git merge <branch_name>

Once the repository is uploaded to GitHub, you can use $ git push to update the repository
You can clone the repository by copying the link from GitHub and $ git clone <link_name>

Have fun!
