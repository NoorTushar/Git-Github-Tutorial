# Steps

1. Install git on your pc
2. Sign in your github account on your vscode
3. Open the project folder in vscode
4. Go to the terminal and use bash option

In the console now write

5. git config --global user.name "NoorTushar"
6. git config --global user.email "tushar.noor.khan@gmail.com"

Now, initialize your project in git

7. git init

Now, Staging (get your files on stage)

8. git add .
   //this will add all the files on stage
   //if you want to add a specific file then say **git add index.js**

9. git commit -m "proper-name-for-commit" //this creates locally

Now before you can upload the files on GitHub repository, create repository and name it like your project folder name for efficiency.

10. Create repository with same project name in GitHub

11. Make sure you have selected the HTTPS option for link generation

Back to console

12. git branch -M main
13. git remote add origin https://github.com/NoorTushar/Git-Github-Tutorial.git
14. git push -u origin main //this sends to cloud

note: -u means upstream and it says that my code will always go and store to main

You have successfully pushed your code to the main branch of your github repository.

## Update and push the code again

15. git add .
16. git commit -m "how-to-update"
17. git push

## Branching

- main branch is only for the final production. so you are not supposed to work here when you are working on a group project.

- lets say you are a team member named Tushar so you create a branch name Tushar

- for collaboration purpose you will use side branches

- so there will be 1. main branch 2. development branch 3. side/ working branches

- after finishing everything, the team leader will pull and merge all the branches together in the main branch.

// creating a branch

18. git branch tushar
