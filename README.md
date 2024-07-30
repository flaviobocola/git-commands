here you can find a list of the commands I know of / I find that might be usefull to speed up your git/github experience.

enjoy :D

## GIT-related commands

| command | purpose |
| ------ | ----- |
| 'git init' | initializes your local git |
| 'git add ...' | add file in staging area |
| 'git add .' | add all the modified/new files to the staging area |
| 'git commit -m "*message*"' | commit the changes |
| 'git commit -m "*message*" *file name/s* | commit the file/s specified without staging |
| 'git commit -a -m "*message*" | commit all new and modified files (that gits knows abt) without staging |
| 'git checkout -f' | removes changes |

### GIT-branch related commands

| command | purpose |
| ------ | ----- |
| 'git branch' | shows all the local branches |
| 'git branch -a' | shows local + cloud-repo branches|
| 'git branch *name*' | create a branch with the selected name |
| 'git branch -d *name*' | delete the branch with the selected name |
| 'git branch -m *old name* *new name*' | rename the branch with the selected names |
| 'git branch switch *name*' | switch to branch with the selected name |
| 'git switch -c *name*' | create branch with selected name and switch to it |

### GIT-changes related commands

| command | purpose |
| ------ | ----- |
| 'git checkout -- *name of file*' | delete file changes |
| 'git restore --staged "*file name*" | restore a file in the index to match the version in HEAD |
| 'git restore --source *source name*~*num* *file name* | move num commits back o f the *source name* branch and restore the index *file name* to
match the old version|
| 'git restore "*.c"' | restore all C source files to match the index version |
| 'git restore . (for git >= 2.23, else is git checkout .)' | restore all changes to your working copy |
| 'git stash' | move all the changes to a "dirty" workspace |
| 'git stash pop' | get back the changes |
| 'git stash clear' | clears stash's workspace |
| 'git revert *commit ID* | load the selected commit |

### GIT-log related commands

| command | purpose |
| ------ | ----- |
| 'git log' | view changes |
| 'git log oneline' | view changes (without details) |
| 'git log -p' | show the changes |
| 'git log --summary' | view changes (detailed) |
