The command `git diff` enables you to compare changes in the working directory against a previously committed version. By default the command compares the working directory and the HEAD commit.

If you wish to compare against an older version then provide the commit hash as a parameter, for example `git diff <commit>`. Comparing against commits will output the changes for all of the files modified. If you want to compare the changes to a single file then provide the name as an argument such as `git diff helloworld.txt`.

## Task

- Let's add some text to the helloworld.txt file: `echo "Git is sooo easy!" >> helloworld.txt`{{execute}}
- Check if there's any differences between the repository and your files: `git diff`{{execute}}
- Add and Commit the changes: `git add helloworld.txt`{{execute}} `git commit -m "Yet another commit"`{{execute}}
