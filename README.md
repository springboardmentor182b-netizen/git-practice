# git-practice

-Clone the repo
    git clone <url>
    git config --global <username>
    git config --global <email>

Before starting your new task,

-creating your feature branch
  create from the website, put the main-group branch as base branch.

-before making the changes everyday
  git branch
  git status - shows the changes made till now
  git checkout <branchname> - if we are not on our feature branch
  
-after making the changes daily
  git add .
  git add <filename>
  add unwanted files/folders to .gitignore file
  git commit -m <message>

- after the task is finished and before you raise the PR

-pull or fetch the latest code
-commit your changes
-resolve merge conflicts if any
-push them to git

  git fetch - local branches are updated
  git merge origin/main-group-A
  - get merge conflicts.....
  - accept incoming changes
      - we want to remove our code and add their code
      - all the files you have not made changes to, you will do accept incoming.
  - accept current changes
      -we want our code and remove their code
      - all the files that you are sure that no one else has worked on...
  - accept both changes
      - there are two different codes, one code part you have not made changes tooo....


  Once resolved...
    git add .
    git add <filename>
    add unwanted files/folders to .gitignore file
    git commit -m "merge conflicts resolved"
  
    git push origin <branchname>
  

-raise the PR
  Create new pull request
  base branch = ypur group main branch
  current branch = your feature branch

**
Tasks to be done by everyone.
- clone this repository
- create a readme file and add your name in that folder
- Common edit file....
  - add name in that common edit file.
  - **
