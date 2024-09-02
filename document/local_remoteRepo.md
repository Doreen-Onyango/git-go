# Local and remote repositories

```
cd work
git clone /home/doonyango/Desktop/work/hello cloned_hello
cd cloned_hello
git log
git remote
git remote show
git branch
git branch -a
cd  hello
 edit README.md
git add README.md
git commit -m "Docs: Update documentation"
cd cloned_hello
git fetch origin
git log --oneline --graph --decorate --all
git checkout master
git merge origin
git fetch origin
git checkout -b greet origin/greet
git branch -vv
git remote add main https://learn.zone01kisumu.ke/git/doonyango/git.git
git remote -v
git push main master
git push main greet

```

## bare repositories
```
cd work
git clone --bare hello hello.git
cd hello.git
ls
cd hello
git remote add origin /home/doonyango/work/hello/hello.git/   

 edit README.md file
git add README.md
git commit -m "Docs: Update document"
 git remote add master https://learn.zone01kisumu.ke/git/doonyango/git.git
git push master

cd cloned_hello
git remote -v
git pull main master
git log --oneline -n 5
```
