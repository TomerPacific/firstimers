# How To Sync A Forked Branch

## Introduction

So sometime ago you forked someone elses repository. Now you need to make sure your forked repository has the latest changes from the original repository.

## Steps

- **Head over to the forked repository directory in the terminal**

- **Check that you have an upstream remote set up using `git remote -v`**
![Remote](https://github.com/TomerPacific/firstimers/blob/master/assets/gitRemote.jpg?raw=true)

- **If you don't see an upstream to the original repository, then you need to add one. You can do so by running: `git remote add upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git`**

- **Using this repository as an example, the command would look like this: `git remote add upstream https://github.com/Tomerpacific/firstimers.git`**

- **After running the above command, run `git remote -v` again to see that the upstream remotes have been added**

- **Run the command `git fetch upstream`**
