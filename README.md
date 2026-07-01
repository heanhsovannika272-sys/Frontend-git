#first create
1. git init # initialize git to project
2. git add <filename> # file will add to repository
   git add . # add all file
3. git commit -m "message" # commit message
4. git branch -M main # create main branch name "main"
5. git remote add origin <repository-url> # add remote repository
6. git push -u origin main # push code to repository
#update code
1. git add .
2. git commit -m "update message"
3. git push -u origin main

#check branch

git branch


#change branch

git fetch origin
git checkout <branch-name>

#create new branch

git branch <branch-name>
git checkout <branch-name>

#push branch to remote

git add .
git commit -m "message"
git push -u origin <branch-name>

#pull code from dev to main bracnh

git pull origin dev
