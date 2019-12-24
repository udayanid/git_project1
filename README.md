# git_project1

#How to add an  existing local project into github repository
## step1
get into you project folder and add whatever the files you want to add into that project folder

### step2
git init
--Initialized empty Git repository in <<working_directory>>

### step 3
git status

### step 4
git add <<filename>> or git add .

### step 5
git status

### step 6
git commit -m "<<commit message>>"

  #### git config --global user.email "you@example.com"
  #### git config --global user.name "Your Name"
  #### git status

### step7 
create a repository in github account same as in local project directory

### step 7
git remote add origin <<gitup_repo_url>>
 
 #### verify remote git url
 git remote -v
 
### step 8
git push origin master
git push -f origin maste

### step 9
git fetch origin master

### step 10 
to get changes from repository into local project directory
git pull origin master




