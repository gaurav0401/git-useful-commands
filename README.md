# github-guide

Git is a version control system which helps to control different versions of the  project.Git is a tool.
<br>
GitHub is a service/website which allows to store and manage source code in a form of repositories.
<br>

### Git Most Used Commands

- <b> <i> git --version </i>: </b> it shows the version of the git.
- <b> <i> git config</i>:</b> used to set  the configuration values on the local or global level. 
- <b><i> git config --global user.name 'name'</i>: </b> used to set the name of the person/organisation who is making a commit. (Note: global config is used for currently logged-in user and all repositories. And local config is used for specific repository.)
- <b><i> git config --global user.email 'email id'</i>: </b> used to set the email  of the account for which we are going to make changes.
- <b><i> git config --list </i> :</b>   it shows the list of all  git configurations.  
- <b><i>git clone <'link'> </i> </b> used to clone repository on local machine.
- <b><i> git status </i> :</b> it display the state of code.
-  <b><i> git status </i> :</b> it display the state of code. <br>
 &nbsp;&nbsp;&nbsp;  (NOTE: there are 4 types of status: <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1. untracked:new files which are not tracked by git yet.<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2. modified : changed <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3. staged : file is ready to be comitted <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4. unmodified :unchaged)
-  <b><i> git add 'file name' </i> :</b> used to add new or changed files in working area  to git staging area. <br>
-  <b><i> git add . </i> :</b> used to  add all new or changed files in working area  to git staging area at once. <br>
- <b><i> git commit -m 'message' </i> :</b> it is a record of change. <br>
- <b><i> git push origin 'main (i.e) name of branch' </i> :</b> used to upload content from local repo to remote repo. <br>
- <b><i> git init</i> :</b> used to create new git repo. <br>
- <b><i> git remote add origin  'link'</i> :</b> used to add new repo to git . <br>
- <b><i> git remote -v </i> :</b>to verify remote <br>
- <b><i> git branch </i> :</b>to check branch<br> &nbsp; &nbsp; &nbsp;(A branch is a pointer to a specific commit. It is also known as a version of repository.)
- <b><i> git branch -M main</i> :</b>to rename branch.  (master is a by default branch.)<br>
- <b><i> git push-u origin main </i> :</b> used to push code on same branch in future using 'git push' only <br>
- <b><i> git checkout 'branch name'</i> :</b>to navigate to another branch. <br>
- <b><i> git checkout -b 'new branch name</i> :</b>to create new branch. <br>
- <b><i> git branch -d 'branch name'</i> :</b>to delete branch. <br>
- <b><i> git diff 'branch name'</i> :</b>to compare commits , files, branch. <br>
- <b><i> git merge 'branch name'</i> :</b>to merge 2 branches. <br>
- <b><i> git pull origin 'branch name'</i> :</b>used to integrate remote changes/content on local repo . <br>
- <b><i> pull request </i> :</b>It lets you tell others about changes you have pushed to a branch in repository on GitHUb and wish to merge them. <br>
<br>
<h3>Undoing changes</h3>
- <b><i> git reset</i> :</b>to undo the all added files for commit. <br>
- <b><i> git reset 'filename'</i> :</b>to undo the added files or changes for commit. <br>
- <b><i> git reset Head~1</i> :</b>to undo the latest commit only <br>
- <b><i> git reset 'commit hash'</i> :</b>to undo many commits. <br>
- <b><i> git reset --hard 'commit hash'</i> :</b>to undo many commits on both locally and remotely  <br>
- <b><i> git log</i> :</b>to undo check log file of all commits done on branch <br>

- <b><i> Resolving merge conflicts</i> :</b>An event  that take place when Git is unable to automatically resolves differences in code between two commits. There are two ways : 1. Pull request method 2. merge command <br>
