
This is just a practice repository to learn githu

Hi I am jagadeesh, Editing this readme file to merge with master

git clone <.git path>

git pull 

git add .

git commit -m 'message'

git push

------------------------------
git branch <branch name>

git checkout <branch>

git push --set-upstream origin <branch name>

--------------------
To create a branch locally
You can create a branch locally as long as you have a cloned version of the repo.

From your terminal window, list the branches on your repository.

$ git branch 
 * master
This output indicates there is a single branch, the master and the asterisk indicates it is currently active.

Create a new feature branch in the repository

$ git branch <feature_branch>
Switch to the feature branch to work on it.

$ git checkout <feature_branch>
You can list the branches again with the git branch command.

Commit the change to the feature branch:

$ git add . 
$ git commit -m "adding a change from the feature branch"
Switch back to the master branch.

$ git checkout master
Push the feature branch to Bitbucket:

$ git push origin <feature_branch>
View the Source page of your repository in Bitbucket. You should see both the master and the feature branch. When you select the feature branch, you see the Source page from that perspective. Select the feature branch to view its Recent commits.


-------------------------------------------------------------------------------------------------------------------
Create .gitignore file using gitbash => touch .gitignore
----------------------------
new master
cd existing_folder
git init
git remote add origin https://gitlab.com/jagadeeshchirumamilla999/pervasive_assignment.git
git add .
git commit -m "Initial commit"
git push -u origin master

