1. git init `<repo name>` - to initialise a new git in the local machine, it will start tracking the project

2. Create new repo in [github.com]
(github.com), copy the link of the repo
3. git remote add origin `<github repo link>` - this adds the "remote" to "origin"
3.1. git remote -v - to confirm that remote has been added
4. Now the local repo and github repo have been linked
5. git add . - this adds the changed files to the staging area
6. git commit -m "message" - this commits the changes added to the staging area, to head but not to the remote repository
7. git push origin master - sends changes to the master branch of the remote repository
8. 