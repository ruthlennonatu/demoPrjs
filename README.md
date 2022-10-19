# demoPrjs 

* create a new folder to work in
* create a clone of the repo
* Create a copy in a new branch to work in
* Make your edits such as creating a file
* Add your file
* Commit using a good commit message. 

** Normally reference the issue number 

** also reference keyword(s) such as fixes, resolves, closes

* push your branch to the remote repo (github) creating a new branch there


Sample commands to test for the lab. What do they do?
If this is a new project with no existing content in the repo.

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ruthlennonatu/demorepos.git
git push -u origin main
******************

if the project already exists then create a folder to work in. initialise as a repo.

git clone https://github.com/ruthlennonatu/demoPrjs

git checkout -b gh1-wip

notepad newcodefile.txt

git add .

git commit -m "Resolves #gh-1 via newcodefile.txt"

git push -u origin gh1-wip


*****************

If the repo exists then checkout the repo to a new branch and work from there.

git checkout -b gh1-wip

notepad newcodefile.txt
notepad file1.txt

git add .

git commit -m "Resolves #gh-1 via newcodefile.txt"

git push -u origin gh1-wip

git log --committer="Ruth Lennon"
git log --before="yesterday"
git log --after="2022-09-10"
git log -- "README.md"
git log --grep="fixes"
git log --oneline --decorate
git rm file1.txt
git branch
git show
