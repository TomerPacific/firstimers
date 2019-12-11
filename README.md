# firstimers
A repository to allow people to try out the core concepts of Git

## Where to Begin

-  **Fork** this repository

![Fork](https://github.com/TomerPacific/firstimers/blob/master/assets/fork.jpg?raw=true)

- **Clone** the forked repository, generating a copy of this repository.

![Clone](https://github.com/TomerPacific/firstimers/blob/master/assets/clone.jpg?raw=true)

- Open a terminal window (or command prompt) and write: ```git clone git@github.com:{YOUR_GIT_USERNAME}/firstimers.git```. This will download the repository to your computer. 

- You now have a local copy of the repository. Let's make some changes. Go inside the repository using the following command : ```cd firstimers```

- Executing the ```ls``` command, you will notice there are two directories: assets and src. Cd into the src directory

- Before we can make any changes, we must create a branch in which our changes will be pushed to. To do this run this command : ```git checkout -b YOUR_BRANCH_NAME```

![Checkout](https://github.com/TomerPacific/firstimers/blob/master/assets/firstimers-checkout.jpg?raw=true)

- Here you will find a file named ```change_me.md```. Open this file in a text editor and add a new line with text to it

- Head back over to the terminal and execute the ```git status``` command

![Status Before Add](https://github.com/TomerPacific/firstimers/blob/master/assets/firstimers-status.jpg?raw=true)

- Now you can see that the ```change_me.md``` file has been modified. To add it to our commit, execute ```git add change_me.md```

![Add](https://github.com/TomerPacific/firstimers/blob/master/assets/firstimers-add.jpg?raw=true)

- If you execute ```git status``` again, you will now see that the file is staged

![Status After Add](https://github.com/TomerPacific/firstimers/blob/master/assets/firstimers-status-after-add.jpg?raw=true)

- Execute the ```git commit -m "Your commit message"``` to commit your changes

![Commit](https://github.com/TomerPacific/firstimers/blob/master/assets/firstimers-commit.jpg?raw=true)

- Finally we can execute ```git push```

![Push Before Upstream](https://github.com/TomerPacific/firstimers/blob/master/assets/firstimers-push-upstream.jpg?raw=true)

- Woah! It lookes like we have a problem. We need to set up a remote upstream to push to

![Push Upstream](https://github.com/TomerPacific/firstimers/blob/master/assets/firstimers-push-upstream-2.jpg?raw=true)

- If we head back to the repository, we will see this notification :

![Pull Request Message](https://github.com/TomerPacific/firstimers/blob/master/assets/firstimers-pr.jpg?raw=true)

- We can now open a **Pull Request** by clicking the button Compare & pull request

![Pull Request](https://github.com/TomerPacific/firstimers/blob/master/assets/firstimers-pr-open.jpg?raw=true)
