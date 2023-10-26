# How To Sync A Forked Branch

## Introduction

So sometime ago you forked someone elses repository. Now you need to make sure your forked repository has the latest changes from the original repository.
The steps below will show how one can do that using the repository **authpass** as an example. This can be done in two ways:

  1. Through the command line
  2. Through GitHub


### Through The Command Line

### Steps

- **Head over to the forked repository directory in the terminal**

- **Check that you have an upstream remote set up using `git remote -v`**
![Remote](https://github.com/TomerPacific/firstimers/blob/master/assets/gitRemote.jpg?raw=true)

- **If you don't see an upstream to the original repository, then you need to add one. You can do so by running: `git remote add upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git`**

- **Using authpass repository as an example, the command would look like this: `git remote add upstream https://github.com/authpass/authpass.git`**

![Upstream](https://github.com/TomerPacific/firstimers/blob/master/assets/addUpstream.jpg?raw=true)

- **After running the above command, run `git remote -v` again to see that the upstream remotes have been added**
![AfterUpstream](https://github.com/TomerPacific/firstimers/blob/master/assets/remoteAfterUpstream.jpg?raw=true)

- **Run the command `git fetch upstream`**
![FetchUpstream](https://github.com/TomerPacific/firstimers/blob/master/assets/fetchUpstream.jpg?raw=true)

- **Check out to the default branch of the repository (either main or master) using `git checkout master`**

- **Merge the changes from the upstream's default branch (main or master) to the local default branch (main or master) using `git merge upstream/master`**

### Through GitHub

### Steps

- **Head over to the forked repository in your GitHub account**

- **Press on the Sync fork option in the top right corner under the green Code button**
![SyncFork](https://github.com/TomerPacific/firstimers/blob/master/assets/sync_github_1.jpg?raw=true)

- **Press the green button that says Update branch**
![SyncForkUpdateBranch](https://github.com/TomerPacific/firstimers/blob/master/assets/sync_github_2.jpg?raw=true)