# python-project
1. Install Visual Studio Code from here: https://code.visualstudio.com/download.
2. Create a project called python-project in github with README file and gitignore file.
3. Install git bash and clone the project using git clone command.
4. Add a new file called app.py and write your code.
5. Run using the command python app.py.
6. Add the file to local repo using the command git add app.py.
7. Commit the file using the command git commit -m "Initial commit".
8. Push using the command git push and you can view status using git status and git diff commands.
9. Other commands:
GIT
====
git log 
show the commit logs

git checkout <branch>
Updates files in the working tree to match the version in the index or the specified tree.

git reset <paths>
Reset current HEAD to the specified state

git pull
incorporates the changes from a remote repository to the current branch

git status 
show the working tree status

git stash 
stash the changes in a dirty working directory away

git stash pop
remove a single stashed state from the stash list and apply it on top of the current working tree state

git cherry-pick <commit>
apply the changes introduced by some existing commits

git reset HEAD TheLearningBar/src/main/java/global.properties

To fetch a new branch:
git fetch
git branch -a => displays the branches
git checkout -b TTFM-2453 remotes/origin/TTFM-2453_Make_School_Level_MCQ_Drilldowns_Visible

git pull --rebase => to remove the Your branch is ahead by 'x' commits in local branch and sync with remote

git reset --hard => to undo local changes

git show-branch -aJRe	Kala

git checkout -bweb	

git push -u origin <branch>

To merge develop with master
----------------------------
git checkout master
git merge develop

delete a branch
---------------
git branch -d branch_name

create a new branch
--------------------
git checkout -b branch_name

1) if he's trying to merge his branch into master, abort that. 2) merge master into his branch. 3) Resolve merge conflicts in his branch (he'll probably need Bin's assistance to make sure he doesn't affect Bin's work in any negative way). 4) Once conflicts are resolved in his branch, he should pull request his branch into master, adding Bin as a reviewer, so Bin can give the final okay that his code wasn't altered in any negative way
It's good practice to regularly pull/merge the origin branch (the branch you branched from) into your current temporary branch. It helps you stay abreast of any changes in the origin branch and you can resolve conflicts along the way, so you don't have to deal with them all at once when the time comes to merge back into the origin branch. For example, if I branched off of master and called my branch TEMP-BRANCH, As I did my work, I would regularly merge master into TEMP-BRANCH to ensure that other developers' changes don't affect my work, and resolve it if need be. Then, my when my work is complete, it will be easier to merge back into master, as there will be less conflicts to deal with.

sudo su -

git checkout --theirs pom.xml
https://stackoverflow.com/questions/10697463/resolve-git-merge-conflicts-in-favor-of-their-changes-during-a-pull

