This is a newer version of the readme file
git --version
git config --list
git status
git commit -m "Message goes here"
git add . (monitor all files for changes)
git push origin master (set up remote repo, for publishing changes. git remote add origin ssh@github.com:username/repo_name)
Create an entirely new folder and to make it a git repo, begin by git init command. From there on we can track changes into the folder
git remote -v (to check if remote repo is connected to)
git push -u(set default remote repo, so that from next time onwards we can type just "git push") origin master
git branch (to show the current branch)
git checkout -b branch-name feature-branch
git diff branchname
git merge feature-readme-instructions
git status
PR(Pull request) from feature branch to master branch
