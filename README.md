
# git_project1

# How to add an  existing local project into github repository
## step1
get into you project folder and add whatever the files you want to add into that project folder

### step2
git init

--Initialized empty Git repository in <<working_directory>>

### step 3
git status

### step 4
git add "<<filename>>" 
git add .

### step 5
git status

### step 6
git commit -m "<<commit_messages>>"

  #### git config --global user.email "you@example.com"
  #### git config --global user.name "Your Name"
  #### git status

### step7 
create a repository in github account same as in local project directory

### step 7
To point git remote url

git remote add origin "<<gitup_repo_url>>"
 
 #### verify remote git url
 git remote -v
 
### step 8
git push origin master

git push -f origin master

### step 9
git fetch origin master

### step 10 
to get changes from repository into local project directory

git pull origin master




Reference:https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners


# How to Clone a Git project?
git clone https://github.com/udayanid/git_project1.git

-------------------------------------------------------------------------
…or create a new repository on the command line
echo "# Fluorescent-Rest-archetype" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/udayanid/Fluorescent-Rest-archetype.git
git push -u origin master
                
…or push an existing repository from the command line
git remote add origin https://github.com/udayanid/Fluorescent-Rest-archetype.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
