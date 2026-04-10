#hello guys
#Command	Use
#git init
#git init	Initialize a new Git repository
#git clone <url>	Download a remote repository
#git status	Show changes and repository status
#git add <file>	Add a file to staging
#git add .	Add all changes to staging
#git commit -m "msg"	Save changes with a message
#✅ Branching
#Command	Use
#git branch	List branches
#git branch <name>	Create a new branch
#git checkout <name>	Switch to a branch
#git checkout -b <name>	Create and switch to a branch
#git branch -d <name>	Delete a branch
#✅ Merging & Rebasing
#Command	Use
#git merge <branch>	Merge a branch into current branch
#git rebase <branch>	Rebase current branch over another
#✅ Remote Commands
#Command	Use
#git remote -v	Show remote URLs
#git remote add origin <url>	Add remote repository
#git push origin <branch>	Upload branch changes
#git push -u origin <branch>	Push & set upstream
#git pull	Download and merge latest changes
#git fetch	Download changes without merging
#✅ Viewing History
#Command	Use
#git log	View commit history
#git log --oneline	One-line history
#git diff	Show file differences
#git show <commit>	Show a specific commit
#✅ Undo / Reset
#Command	Use
#git reset <file>	Unstage a file
#git reset --soft HEAD~1	Undo last commit, keep changes
#git reset --hard HEAD~1	Undo last commit & delete changes
#git revert <commit>	Create a new commit to undo a commit
#✅ Stash
#Command	Use
#git stash	Save uncommitted changes temporarily
#git stash list	Show stashes
#git stash apply	Restore a stash
#✅ Tags
#Command	Use
#git tag <name>	Create a tag
#git push --tags	Push all tags
#✅ Clean
#Command	Use
#git clean -n	Preview files to be removed
#git clean -f	Remove untracked files

---------------------------------------------------------------------------------
✅ Basic Docker Commands
Command	Use
docker --version	Check Docker version
docker info	Display system-wide information
✅ Images
Command	Use
docker images	List all Docker images
docker pull <image>	Download image from Docker Hub
docker build -t <name> .	Build image from Dockerfile
docker rmi <image>	Delete an image
docker history <image>	Show image layers
docker tag <src> <target>	Rename or retag an image
✅ Containers
Command	Use
docker run <image>	Run a container
docker run -d <image>	Run in detached mode
docker run -it <image> sh	Run interactively inside container
docker ps	List running containers
docker ps -a	List all containers
docker stop <container>	Stop a running container
docker start <container>	Start an existing container
docker restart <container>	Restart a container
docker rm <container>	Delete a container
docker logs <container>	View container logs
docker exec -it <container> sh	Execute command inside container
✅ Container Management
Command	Use
docker inspect <container>	Get detailed container info
docker top <container>	Show running processes
docker stats	Show resource usage of containers
docker cp <container>:<path> <local>	Copy from container to host
docker cp <local> <container>:<path>	Copy from host to container
✅ Volumes
Command	Use
docker volume create <name>	Create a volume
docker volume ls	List volumes
docker volume rm <name>	Delete a volume
