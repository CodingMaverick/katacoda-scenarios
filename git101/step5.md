Sometimes there are particular files or directories you never want to commit, such as local development configuration. To ignore these files you create a `.gitignore` file in the root of the repository.

The `.gitignore` file allows you to define wildcards for the files you wish to ignore, for example `*.tmp` will ignore all files with the extension `.tmp`.

Any files matching a defined wildcard will not be displayed in a git status output and be ignored when attempting the git add command.

## Task

- Create a temporary file: `echo "This is temporary" >> temporary.tmp`{{execute}}
- Create a `.gitignore` file that ignores all .tmp files: `cat *.tmp >> .gitignore`{{execute}}
- Add all the new files: `git add .`{{execute}}
- Check the status of your repository: `git status`{{execute}}
- Commit to the repository: `git commit -m "My second git commit"`{{execute}}
