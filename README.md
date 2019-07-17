# Git commands

## Clone existing remote repository to the desktop
1. Create new folder for the project
2. Open cmd in the new created folder (type "git" to see if you have git installed)
3. Run command "git init" to create new empty repository. If done correctly you should receive message "Initialized empty Git repository in C:/Users/biser.ivanov/someFolder/someFolder/.git/
4. In the github website click "Clone or download" and from there you can copy the repository url
5. In the cmd run the command "git pull paste-repository-url-here"
6. Now you should have your repository downloaded locally

## Push update from the local repository to the remote
1. After you have finished work on the project open cmd in the repository root folder
2. You can run command "git status" optionally to check the state of the repository
3. Run command "git add ." which will commit all the changes in all the files
4. Run command "git commit -m "some message""
5. To see difference from the updates optionally run "git diff"
6. If there is issue with credentials run following commands to get prompted for username and password

git config --local credential.helper ""

git push origin master

7. If there are no issues just run
git push origin master
