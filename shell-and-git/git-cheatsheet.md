# git-cheatsheet

## commands

| Command              | Explanation                                                           |
| -------------------- | --------------------------------------------------------------------- |
| git init             | initialize git                                                        |
| git status           | show the status of your files (untracked, modified, staged, commited) |
| git add .            | add all files                                                         |
| git add README.md    | add a specific file, here README.md                                   |
| git commit -m "text" | commit your changes with a description                                |
| git push             | push all staff                                                        |
| git pull             | synchronize the repo                                                  |

## connect to an existing repo on GitHub

1. First create a folder with the same name as the repo.
2. Init the folder with git.
3. Add the remote url.
4. Pull all files from GitHub.

If you get an error you have to follow the instructions to set the main branch.

| Command                                                      | Explanation               |
| ------------------------------------------------------------ | ------------------------- |
| git init                                                     | initialize git            |
| git remote add origin git@github.com:marcel-epp/reponame.git | add the remote repo url   |
| git pull                                                     | get all files from github |

## create a new branch

| Command                         | Explanation                                  |
| ------------------------------- | -------------------------------------------- |
| git switch -c <branchname>      | create a new branch and switch to it         |
| git switch <branchname>         | switch branches                              |
| git branch                      | list your branches                           |
| git branch -a                   | list all branches (local and remote)         |
| git branch -d <branchname>      | delete a branch                              |
| git push -u origin <branchname> | push the branch with all the files to GitHub |

![Git Basic Workflow](images/git-basics-branching-workflow.png)
