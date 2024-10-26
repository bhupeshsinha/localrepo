# This is my Local Repo

    1. git status
    2. git add .
    3. git commit -m "ADD readme"
    4. git push

    WORK FLOW
    create GitHub Repo -> Clone -> Changes -> git add . -> git commt -m"message" -> git push

    BRANCHES
    1. git branch   (to check branch, also list down all the branches)
    2. git branch -M <new name of branch>   (to rename the branch)
    3. git checkout <-Target branch name>   (to move from one branch to other branch)
    4. git checkout -b <-new branch name>   (to create a new branch)
        example: git checkout -b feature1
                 git branch
                 git checkout main  (move from feature1 --> main)
                 git branch
                 git checkout feature1 (move from main --> feature1 )
                 git checkout -b feature2
                 git branch
                 git branch -d feature1     //to delete a specific branch

