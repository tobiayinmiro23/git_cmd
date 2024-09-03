to clone a repository
git clone <repo link>

to add file
git add <file name>

to remove an added file
git rm --cached  <file name>

to remove an added file and delete it from the folder
git rm -f  <file name>

to commit the changes made
git commit -m <commit message>

to reverse a commit
git revert <commitid>

lists all the branches
git branch  

Create a new branch called ＜branch＞
git branch <branch>

Create a new branch and switch to it
git checkout -b [branch name]	

for deleting a particular local branch forcefully even if it has unmerged changes
git branch -D <branch>

Rename the current branch to ＜branch＞
git branch -m <branch>

Push a local branch to your remote repository branch
git push origin [branch name]
git push --set-upstream origin one	

List all branches local and remote. 
git branch -a

for deleting a remote branch
git push origin --delete <branch>
git push origin :<branch>

to switch to a remote branch
git checkout -b <branch name> origin/<branch name>

to merge a branch to another go to the reciepient branch and run the cmd
git merge <branch to be merged>











to push a locale repo to remote repo
git remote add new-remote-repo https://github.com/tobiayinmiro23/git-test.git
git push new-remote-repo <branch name>

to connect to the remote server
git remote add origin https://github.com/tobiayinmiro23/git-test.git

to checkout (switch to) a remote branch first of all
1. git fetch --all
2. git checkout --track origin/<branch>
