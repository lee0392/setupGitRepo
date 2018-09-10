# Set Up Git Repo
Simple steps to create and manage Git Repo

1. Create a repository in GitHub
Go to https://github.com/

Select Start a project and Specify a repository name in the text box(For eg 'My First Repo') . Click create repository.

2. Set Git to your username and password. These two commands are one time setup.

git config --global user.name "Pranalee Jadhav"
git config --global user.email pranalee@example.com

3. To make your local repository as git hub repository

git init

4. To add local files to git

git add .

5. To Commit the files to repository

git commit -m "my first commit"

6. To add the local repository as an origin for the targeted git hub repository (the one created in step 1)

git remote add origin <<repository link>>

7. To push the files from local repository to the git hub repository

git push -u origin master
