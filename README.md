to make this a git file use the term `git init`.

then track them using `git add .`.

then see the status using `git status`.

then commit using `git commit -m "create README.md`.

then create a repo in git hub with the name local-file-git

then copy the ssh and paste it at <ssh> : `git remote add origin <ssh>`

then push the file using `git push orign main` || `git push -u origin master`

## Branches in git
1. To create a new branch use, `git checkout -b <descriptive-branch-name>`
2. To check which branch you are on, use `git branch`
3. To switch brances, use `git checkout <branch-name>`
4. After adding, committing the new branch, push it using `git push origin <branch-name>`
5. create pull request on github an merge it.
6. You will notice after switching to master branch in your local file, that the changes do not appear.
7. To resolve that, use `git pull`
8. to delete the side branch, use `git branch -d <branch-name>`
