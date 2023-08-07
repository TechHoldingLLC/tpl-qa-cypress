# tpl-qa-cypress
This repository is managed by the QA team for POCs and Learning.

GitHub Code Guidelines: 
How to Create a branch and push your code/changes in Git?

REMEMBER: BEFORE PUSHING YOUR CODE TO THE DEV OR MAIN, TAKE PULL FOR THE LATEST CHANGES.

**Git Commands:**

1. First, go to the location in your local system using your terminal where you want to take a clone of the repo
   For Eg. cd Documents ==> cd Automation ==> cd Folder Name
2. Then take a clone using git commands
   **git clone "SSH Link"** or **git clone "HTTPS Link"**
3. Go to the cloned folder using cd commands and then check the branch using
   **git branch**
4. If you want to add/update your code then create a new branch using
   **git checkout -b "branch_name"**
5. Once the new branch is created you will be automatically switched to a new branch and if not so, you need to switch to that branch. Using the below-mentioned command, you can go to the newly created branch
   **git checkout "branch_name"**
6. Once you update your code or modify your scripts, you can check the status of all the changes using the below-mentioned git command git status
You will see some updated files after hitting git status. Now you need to add and commit. Use the following commands to commit your changes
   **git add .**
   **git commit -m "Comments"**
7. Now push the changes to your branch using
   **git push origin branch_name or git push**
   (use the origin command only when you want to make your branch an origin branch like develop)
