# first create
1. git init # initialize git to project
2. git add <filename> # file will add to repository
   git add . # add all file
3. git commit -m "message" # commit message
4. git branch -M main # create main branch name "main"
5. git remote add origin <repository-url> # add remote repository
6. git push -u origin main # push code to repository
# update code
1. git add .
2. git commit -m "update message"
3. git push -u origin main

# check branch

git branch


# change branch
1. git fetch origin
2. git checkout <branch-name>
# create new branch

1. git branch <branch-name>
2. git checkout <branch-name>

# push branch to remote

1. git add .
2. git commit -m "message"
3. git push -u origin <branch-name>

# to work with local branch

# create new branch
1. git branch <new-branch>
2. git checkout <new-branch>

# when finish code in new branch
1. git add .
2. git commit -m "message"

# switch from new branch to main branch
1. git checkout main

# merge new branch to main branch
1. git merge <new-branch>
