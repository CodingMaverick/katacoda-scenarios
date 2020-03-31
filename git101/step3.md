To save, or commit, files into your Git repository you first need to add them to the staging area. Git has three areas, a working directory, a staging area and the repository itself. Users move, otherwise referred to as promote, changes from the working directory, to a staging area before committing them into the repository.

One of the key approaches with Git is that commits are focused, small and frequent. The staging area helps to maintain this workflow by allowing you to only promote certain files at a time instead of all the changes in your working directory.

## Task

- Let's create a new text file with a basic greeting: `echo "Hello World from Git" >> helloworld.txt`{{execute}}

- Now, use the command `git add helloworld.txt`{{execute}} to add helloworld.txt to the staging area.

> If you make an additional change after adding a file to the staging area then the change will not be reflected until you add the file again.

- Now you can check which files have been changed by executing `git status`{{execute}} again.