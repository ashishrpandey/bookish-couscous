### Understand the Git Repo workflow using CLI
    
Make a directory
```
mkdir test-project
```
login to the directory
```
cd test-project/
```
Create readme.md file
```
"# super-duper-giggle" >> README.md
```
Intiliaze the repo
```
git init
```
create test.md file
```
vim test.md
```
Check the status
```
git status
```
Stage the files
```
git add README.md
```
Check the status
```
git status
```
Stage all the files
```
git add -A
```
check the status
```
git status
```
commit the changes
```
git commit -am "add readme.md files"
```
commit readme.md files
```
git commit -am "add readme.md files"
```
Add remote repo ref
```
git remote add origin <your remote repo url>
```
Check what are the remote ref urls
```
git remote -v
```
Set upstream branch
```
git push --set-upstream origin master
```
 
