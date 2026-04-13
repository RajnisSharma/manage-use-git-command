# About me
This is my first repository.
<br>
Rajnish kumar Sharma
<br>
I have Completed my B.tech in Computer science.


<hr>

## How to upload a project to github using git?
### Create a new repositry on the command line.
1. git config --global user.name "Your Name"
2. git config --global user.email "Your Email @gmail.com"
3. If you don't want to Upload File then create file:- touch .gitignore
4. git init
5. git add .
6. git status
7. git add README.md
8. git commit -m "first commit"
9. git branch -M main
10. git remote add origin git@github.com:RajnisSharma/Python-API.git
11. git pull origin main
12. git pull --rebase origin main
13. git push origin main
14. 

```
GitHub project upload command:
______________________________________________________________________
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/username/repository-name.git
git branch -M main
git push -u origin main
_______________________________________________________________________
Project Update command:
-----------------------
git status
git pull
git add filename  or  git add .
git commit -m "project update message"
git push
_______________________________________________________________________
Folder Delete command:
----------------------
git rm -r foldername
git commit -m "Deleted folder"
git push
--------------------
File delete command:
--------------------
git rm src/test.js
git commit -m "Removed test file"
git push
_______________________________________________________________________
Git Clone(GitHub project download):
-----------------------------------
git clone repo_url
git clone https://github.com/username/repository-name.git

---------------------------
By downloading the zip file
---------------------------
If the song isn't installed:
1. Open the GitHub repo
2. Click the code button
3. Select Download Zip
4. Extract the zip file
_______________________________________________________________________
For update through vs code terminal:
_______________________________________________________________________
git init
git remote add origin https://github.com/RajnisSharma/BookFinder.git
git pull origin main
git add .
git commit -m "initial commit"
git push origin main
_______________________________________________________________________
👉 Old project → saved safely
👉 New project → becomes main
------------------------------
✅ Step 1: Save OLD project into a new branch
Right now your old code is in main.
...................................
git checkout -b old-project
git add .
git commit -m "Backup old project"
git push origin old-project
...................................
✅ Step 2: Go back to main branch
git checkout main
✅ Step 3: Remove old files from main
git rm -r *

Then commit:

git commit -m "Remove old project files"
✅ Step 4: Copy your NEW project into this folder
(Manually paste new project files into this directory)
✅ Step 5: Add and push new project to main
git add .
git commit -m "Add new project (latest version)"
git push origin main
------------------------------------------------------------------------
⚠️ This will overwrite ONLY main (safe because old project is in another branch)
git push -u origin main --force

```
