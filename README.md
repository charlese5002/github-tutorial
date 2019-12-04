# GitHub Tutorial

_By: Charlie Eydman_

---
## Git vs. GitHub

***Git:*** Git is a control system that regulates and tracks changes in files or code. Is is also used for collaborating with other people and sharing code.

***Github:*** Github is a company that hosts the program Git and is currently owned by Microsoft.

---
## Initial Setup
***Github Account:*** To setup/create a github account go to this link: [Create An Account](https://github.com/join?source=header-home). Then enter a username, password, and email.

***IDE Setup:*** To setup your IDE go to this link and follow the directions: [IDE Setup](https://github.com/hstatsep/ide50)

***SSH Key:*** A SSH-Key short for ssh-keygen is used to authenticize a user to their remote device. It is needed to identify yourself without using a username and password and is unique to you.

---
## Repository Setup


When in the repository, commands like `init`, `add`, and `commit`are commonly used because they regulate the code. It is also very important not to get a directory condused with a repository. A directory is just a folder while a repository is a folder that stores code and development items.

***Github Repository:*** To setup your first Github reporitory, click the plus icon on the top right of your github home screen and click new repository. Then enter a repository name and click Create Repository on the bottom.

***Remote:*** To setup your remote type `git remote add orgin git@github.com:[username]/[repository name].git` and then type `git push -u orgin master`.

---
## Workflow & Commands

***Commands like `git status`, `git add`, `git commit`, `git add` regulate and help with orginization and workflow of code. Here is what each one means and how to use them:***

* `git init` is a command that initiates git in your repository and converts it to a Git repository. It is used mostly when starting a new project.

* `git status` is a command that shows the current state of your stageing directory. `git status` can be used anytime you want to check if your files are staged or unstaged.

* `git add` is a command that adds either a specific file or all files to the stageing directory. This command is used when you want to save changes to your file and is a 2-step command with `git commit` being the other one.

* `git commit` is a command that saves your file to the local repository. It is also like updating a new version of the file and you can add a note in the command: `git commit -m "_____"`. This command can be used when you want to save your changes to a file and is the 2nd step in the 2-step saving.

* `git push` is a command that uploads your local repository to a remote one. This command is used when you want up load your local repository that is using git to the remote one which is github.

---
## Rolling Back Changes

***Undo/Roll Back Changes:*** There are 2 ways to undo and roll back changes to a file. The first would be to simply change your file to what you want it to be and then typing `git add`, `git commit`, and `git push`. The second way to roll back changes is to type `git log` find the version that you want to go back to. Then type `git revert _____`and the file will return to the version that you selected. After either doing so, your file should say what you want it to say.

---
## Error Handling

***`git init` Removal:*** If you have typed `git init` and initialized git in the wrong directory, simply type `rm -rf git.`.


***Remove Repository:*** To at anytime remove a repository, type the command `rmdir (file name)`. This command will ask you to type `y` or `n` for yes and no to complete the action. If you want remove something without question or git confirming it type `rm -rf` in the beginning of your command.