# Git

## create a new repository on the command line

echo "# Git" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/shuntianfu/Git.git

git push -u origin main

## push an existing repository from the command line

git remote add origin https://github.com/shuntianfu/Git.git

git branch -M main

git push -u origin main

## import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
