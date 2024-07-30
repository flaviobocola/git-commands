here you can find a list of the commands I know of / I find that might be usefull to speed up your git/github experience.

enjoy :D

---

## GIT-related commands

| command | purpose |
| ------ | ----- |
| 'git init' | initializes your local git |
| 'git add ...' | add file in staging area |
| 'git add .' | add all the modified/new files to the staging area |
| 'git commit -m "*message*"' | commit the changes |
| 'git commit -m "*message*" *file name/s* | commit the file/s specified without staging |
| 'git commit -a -m "*message*" | commit all new and modified files (that gits knows abt) without staging |
| 'git checkout -f' | remove changes |
| 'git show HEAD' | show where the HEAD points |

---

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

---

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

---

### GIT-log related commands

| command | purpose |
| ------ | ----- |
| 'git log' | view changes |
| 'git log oneline' | view changes (without details) |
| 'git log -p' | show the changes |
| 'git log --summary' | view changes (detailed) |

---

## GITHUB-related commands

| command | purpose |
| ----- | ----- |
| 'git remote add origin *url*' | connect the local repo with a cloud one indicated with the *url*, also you will refer to it as origin |
| 'git remote set-url origin *url*' | set the *url* of origin |
| 'git push origin *local branch name*' | push a branch to the remote repository |
| 'git push -u origin *local branch name*' | 'push a branch adding a tracking reference (used by argument-less git-pull and others |
| 'git push' | 'push the changes on the cloud repo adding the tracking reference |
| 'git push origin --delete *cloud branch name* | delete *cloud branch name* branch |
| 'git pull' | update local on cloud base |
| 'git pull origin *local branch name* | local branch update |
| 'git reset --hard *source name*~*num* *file name* | delete the cloud commit done *num* before the latest one|

---

little bonus: [here](https://explainshell.com/explain?cmd=git+branch+-M+main)'s a site where you can see what every command does
