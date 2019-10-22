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

- Here you will find a file named ```change_me.md```. Open this file in a text editor and add a new line with text to it

- Head back over to the terminal and execute the ```git status``` command

- Now you can see that the ```change_me.md``` file has been modified. To add it to our commit, execute ```git add change_me.md```

- If you execute ```git status``` again, you will now see that the file is staged

- Execute the ```git commit -m "Your commit message"``` to commit your changes

- Finally we can execute ```git push```
