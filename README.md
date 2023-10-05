
### Initialize/create a new repository

If you've already created the project folder, the first command you need to run is
```
git init
```
this will transform the current directory into a Git repository


If you want to create a whole new Git repository in the specified directory (the folder you're in),
you'll need to use the command
```
git init <directory name>
```


### Add and commit files

Before you can commit any changes, you'll need to stage which file(s) you want to commit using
```
git add <file name>
```
or
```
git add --all
```
which will stage those files, and you'll be able to commit them using
```
git commit -m "commit message"
```

by using these commands you'll update your local VC (version control)


To skip a few steps
```
git commit -a
```
will instruct git to stage all modified files

### Push commits to GitHub

To upload the local repository to a remote repository, use
```
git push
```
however this command will not stage new files.



git pull --rebase


git checkout -b feature


git merge master




git clone vs git fork


```
git fork
```
direct copy, no connection to the github repo


```
git clone
```
already connected to the github repo you cloned it from


```
nvm clean install
```


```
git stash
```

```
git stash pop
```
take the changes off of the stash, and remove them from the stack

```
git stash apply
```
take the changes off of the stash, but keep them in the stack


resets the local repo to wherever the master branch is at
```
git reset --hard HEAD
```


```
git log
```

to add a new push url and delete the old one
```
git remote set-url --add --push >URL<
```
```
git remote set-url --delete >URL<
```

to set a new fetch url
```
git remote set-url >URL<
```
