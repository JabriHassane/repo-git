# repo-git
learn Git

#Definition:
git is a free and open source version control system.
the managment of change to documents, computer programs, large web sites, and other collections of information.
Repository :  Project, or the folder/place where your project is kept.
git is a tool that track your changes.
gthub : webSite to host your repositories onlines

## Git Commande:
repo : repository.
clone : bring a repo down from the internet to ypur lical machine.
add: track your files and changes with Git.
commit : save your changes into Git.
push: push your changes to your remot repo on Github.
pull : pull changes down from the remote repo to your local machine.

## pulling a Project:
copy the the link your repo (code Clone HTTPS)
in commande line paste > git clone https://www.lennu.net/doctrine-many-to-many-with-extra-fields/

## Modifie the repo an push it:
creat a new file test (exp : index.html)
in the Commande line:
> git status
show us the modification we did in our project (files created or updeated or deleted...) but not save in my repo git.
So we use the commande :
> git add "name of files"
after that we check out with using teh commande "git status" to make sure that the changes is correctly done!. and ready to be commited.
So we use the line commande:
>git commit -m "Message"
after that we push our modification into github using:
>git push

## SSH keys:
https://docs.github.com/en/github/authenticating-to-github/checking-for-existing-ssh-keys
Using the SSH protocol, you can connect and authenticate to remote servers and services. With SSH keys, you can connect to GitHub without supplying your username and personal access token at each visit.

## Push an existen project to github

>git init 
>git status --
>git add .
>git status --
creat a new repo in github and copy the link to the repo
>git remote add origin "passt thr link"
>git remote -v 
>git push -u origin master

## Git branching:
A branch in Git is simply a lightweight movable pointer to one of these commits. ... As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically.
En effet la commande git branch n’a fait que créer une nouvelle branche — elle n’a pas fait basculer la copie de travail vers cette branche.

show the branche in my project
>git branch
creat a new branche
>git checkout -b feature-name
change the branche
>git chekout "name branche"

## mergin branche
Merging is a common practice for developers using version control systems. Whether branches are created for testing, bug fixes, or other reasons, merging commits changes to another location. To be more specific, merging takes the contents of a source branch and integrates them with a target branch.
Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. Note that all of the commands presented below merge into the current branch.
>git merge master

## Undo Git
>git reset
>git reset HEAD~1
>git reset --hard "hash key"


