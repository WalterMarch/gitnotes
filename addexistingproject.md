# add existing Project to GitHub

https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/

Create new repo on GitHub without gitignore, liscense or readme.
init the local repo 
add and commit the files
copy the remote repository URL
in your local repo, add the remote:
```
git remote add origin remote_repository_URL
```
push the changes from the local to the remote (github):
```
git push origin master
```
