# Git commits to commit
## Establish a directory inside the work directory 
```bash
mkdir hello
```
## Create a file in the hello directory
```bash
touch hello.sh
```
## Input data in hello.sh file
```
echo "Hello World"
```
## Initialize git in hello directory
```bash
git init
```
## Check status and act to it
```bash
git status
git add hello.sh
git commit -m "Feat: Init file"
```
## Update hello.sh file
stage the changed file
```bash
git add hello.sh
git commit -m "Feat: update init file"
git status
```
## update file with comments
stage the changes
```bash
git add hello.sh
git commit -m "Docs(hello): Add comment"
```
## update file
stage the changes
```bash
git add hello.sh
git commit -m "Refactor: Add variable name"
```
