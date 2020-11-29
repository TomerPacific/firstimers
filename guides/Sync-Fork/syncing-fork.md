# How To Sync A Forked Branch

## Introduction

So sometime ago you forked someone elses repository. Now you need to make sure your forked repository has the latest changes from the original repository.

## Steps

### Head over to the forked repository directory in the terminal

### Check that you have an upstream remote set up using `git remote -v`

### If you don't see an upstream to the original repository, then you need to add one. You can do so by running: `git remote add upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git`

### Run the command `git fetch upstream`
