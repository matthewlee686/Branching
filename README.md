## Git Cheat Sheet

* 'git init' - Initialize a local git repo in working    directory
* 'git status' - Show State of local repo
* 'git log' - List commit history
* 'git log --oneline' - Compact commit history
* 'git add .' - Stage current directory in git index
* 'git commit -m "msg" ' -
* 'git config -l' - List git and repo configuration
* 'git diff sha' - Show diffs between current commit and commit id 'sha'
* 'git diff oneBranch otherBranch' - Show diffs between 'oneBranch' and 'otherBranch' 


## Branching
* 'git branch' - Look at available Branches
* 'git branch (new branch name)' - Creates a new Branch
* 'git checkout (branch name)' - Switches to that Branch

--Some change
--More Changes

### Remote Repos
* 'git remote add alias url' - Add 'alias' as name for remote repo 'url' in project configuration
* 'git push alias aBranch' - push local commits to remote repo  'alias''s branch 'aBranch'
* 'git pull alias aBranch' - pull remote 'aBranch' from 'alias' into current local branch
