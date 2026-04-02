# Study-basic-tech-of-Github
1. Branch let one repository have a different version at the same time
2. Pull request is done.
3. Forking the repository means "cloning" a repository online, so I use the word " clone is something wrong.

# Create a new repository from local 
1. In the terminal, open your local file, which you want to update in GitHub. For example, cd example.
2. Git init
3. Git add .   %Stage all changes in the current folder and its subfolders for the next commit
4. Git commit -m "description of change" %commit your change and explain what you changed
5. Git push   %Update your change on GitHub online
6. Git pull   %Update your local file from the online repository,

# .gitignore
1. .gitignore will not remove files already checked. To fix it, we need to do the following:
   -  git -rm --cached .  %remove from the git index only, not from the local computer disk.
   -  git add .
   -  git commit -m ""
   -  git push
