hello guys
git init
Command	Use
git init	Initialize a new Git repository
git clone <url>	Download a remote repository
git status	Show changes and repository status
git add <file>	Add a file to staging
git add .	Add all changes to staging
git commit -m "msg"	Save changes with a message
✅ Branching
Command	Use
git branch	List branches
git branch <name>	Create a new branch
git checkout <name>	Switch to a branch
git checkout -b <name>	Create and switch to a branch
git branch -d <name>	Delete a branch
✅ Merging & Rebasing
Command	Use
git merge <branch>	Merge a branch into current branch
git rebase <branch>	Rebase current branch over another
✅ Remote Commands
Command	Use
git remote -v	Show remote URLs
git remote add origin <url>	Add remote repository
git push origin <branch>	Upload branch changes
git push -u origin <branch>	Push & set upstream
git pull	Download and merge latest changes
git fetch	Download changes without merging
✅ Viewing History
Command	Use
git log	View commit history
git log --oneline	One-line history
git diff	Show file differences
git show <commit>	Show a specific commit
✅ Undo / Reset
Command	Use
git reset <file>	Unstage a file
git reset --soft HEAD~1	Undo last commit, keep changes
git reset --hard HEAD~1	Undo last commit & delete changes
git revert <commit>	Create a new commit to undo a commit
✅ Stash
Command	Use
git stash	Save uncommitted changes temporarily
git stash list	Show stashes
git stash apply	Restore a stash
✅ Tags
Command	Use
git tag <name>	Create a tag
git push --tags	Push all tags
✅ Clean
Command	Use
git clean -n	Preview files to be removed
git clean -f	Remove untracked files