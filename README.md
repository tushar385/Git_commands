# Git Commands

## Installation
sudo apt install git

git --version

## Connect with github account
git config --global user.name "abc123"

git config --global user.email "abc123@gmail.com"

git config --list

## clone git repository to your local system
git clone https://github.com/abc123/git_project.git

## To check any changes made in your local system
git status

#### Types of status
1. untracked -- New file is added
2. modified -- Any file is altered
3. staged -- Intermediate place before commit (Before commit file has to go through staging)
4. unmodified

## Stage changes of untracked or modfied changes
git add file_name  ( To stage a single file)

git add .  ( To stage all file at once)

## Commit changes of stageing
git commit -m "message" ( by commit chnages will not reflect in github UI, so also have to push)

## Push 
git push origin main

------------------------------------------------------------------------------------------------------------------

## To check if the current folder is a git connected folder or not
ls -a  (it will have a .git file)

## To initialize current folder as a git folder
git init

## To connect cwd with github repository
git remote add origin https://github.com/abc123/git_project2.git

## To verify cwd is connected to which github repository
git remote -v
