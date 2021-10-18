# Most Frequent Git Commands

* git init : used to convert current directory to a git repository
* git status  : used to see what files are in the working area and staging area, tracked files,untracked files and changes.
* git add : used to add changes in working directory to staging directory.
    * git add [path]  : stage a directory or a file
    * git add . : stage all files (which are not listed in .gitignore )
* git  commit -m “commit_message” : used to commit changes
* git remote add origin [URL] : used to add remote url to local git repository. Remote url will be stored under user-friendly name - origin.
* git remote -v : used to see the linked remote repositories.
* git push -u origin master : used to send local git repository to remote. When pushing a branch for the first time, This will establish the relationship with the local repository and the remote.
* git push : used to upload all local branch commits to the remote if there is already a git relationship between local and remote. Otherwise you will have to run the above command first.
* git push --set-upstream origin [local_branch] :  push a local branch to remote
* git clone [url] : used to download remote to local including all files, branches and commits.
* git branch :  used to list all branches. Current branch will be indicated from *.
* git branch [branch_name] : used to create a new branch but remains in the current branch.
* git checkout -b [branch_name] : used to create a new branch and switch to it.
* git checkout [branch_name] : used to switch to an already created other branch.
* git checkout -b [branch_name] origin/[branch_name] : used to clone a remote branch to local and switch in to that.
* git branch -d [branch_name] : delete a local git branch
* git push origin --delete [branch_name] : delete a remote branch
* git stash : used to save uncommitted changes (both staged and unstaged) for later use and revert them from your working copy.
* git stash pop : used to reapply previously stashed changes. Changes will be removed from stash and will be reapplied on working copy. 
* git stash apply : used to reapply previously stashed changes. But keep them in your stash.
* git merge [branch_name] : used to merge another branch to current branch
* git merge --abort : used to revert the last merge in current branch
* git merge [source_branch] [target_branch] - used to merge a branch to target branch
* git pull : used to update local working branch from the remote. All remote tracking branches will be updated at the same time. It is a combination of git fetch + git merge.
* git fetch : used to gather any commits from remote branch and keep them in your local repository. A merge won’t be initiated. If you use git fetch instead of git pull, make sure to git merge later.
* git reset --hard : used to move the HEAD pointer and active branch pointer to the recent commit which exists on remote tracking branch.
* git log : used to show the list of commits made to a git repository.
 



