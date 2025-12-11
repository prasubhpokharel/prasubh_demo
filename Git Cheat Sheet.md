**SETUP**

git config --global user.name "\[firstname lastname]" → Sets your name for Git commits globally.



git config --global user.email "\[valid.email]" → Sets your email for Git commits globally.



git config --global color.ui auto → Enables automatic colored output in the terminal.



**SETUP \& INIT**

git init → Initializes a new Git repository in the current directory.



git clone \[url] → Creates a local copy of a remote repository.



**STAGE \& SNAPSHOT**

git status → Shows which files are staged, unstaged, or untracked.



git add \[file] → Stages a file for the next commit.



git reset \[file] → Unstages a file but keeps its changes.



git diff → Shows unstaged changes since the last commit.



git diff --staged → Shows changes that are staged but not yet committed.



git commit -m "\[message]" → Commits staged changes with a message.



**BRANCH \& MERGE**

git branch → Lists all branches in the repository.



git branch \[branch-name] → Creates a new branch at the current commit.



git checkout → Switches to another branch.



git merge \[branch] → Merges a specified branch into the current branch.



git log → Shows commit history for the current branch.



**INSPECT \& COMPARE**

git log → Shows commit history for the active branch.



git log branchB...branchA → Shows commits in branchA not in branchB.



git log --follow \[file] → Shows commits that changed a file, even if renamed.



git diff branchB...branchA → Shows diff of changes in branchA not in branchB.



git show \[SHA] → Displays details of a specific commit or object.



**TRACKING PATH CHANGES**

git zm \[file] → Likely typo for git rm \[file] – removes a file from the repository.



git mv \[old] \[new] → Renames or moves a file and stages the change.



git log --stat -H → Shows commit logs with moved file indications.



**IGNORING PATTERNS**

git config --global core.excludesfile \[file] → Specifies a global .gitignore file for all repos.



**SHARE \& UPDATE**

git remote add \[alias] \[url] → Adds a remote repository with an alias.



git fetch \[alias] → Downloads branches and commits from a remote.



git merge \[alias]/\[branch] → Merges a remote branch into your current branch.



git push \[alias] \[branch] → Uploads local commits to a remote branch.



git pull → Fetches and merges commits from the tracking remote branch.



**REWRITE HISTORY**

git rebase \[branch] → Reapplies current branch commits on top of another branch.



git reset --hard \[commit] → Resets to a previous commit, discarding all changes.



**TEMPORARY COMMITS**

git stash → Temporarily saves uncommitted changes.



git stash List → Likely typo for git stash list – lists all stashed changes.



git stash pop → Applies and removes the most recent stash.



git stash drop → Discards the most recent stash.

