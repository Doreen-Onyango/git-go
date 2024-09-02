t ca# Blobs, trees and commits
Exploring .git/ directory
```
cd .git/
ls
```
latest object hash
```
find .git/objects -type f
git rev-parse HEAD
git cat-file -p 59a9ae1f6387b42eadc223aaf05156ab9fe0f37b
```
dumping directory
```
git log --oneline
git li-tree -r 59a9ae1
git ls-tree 043e9fc
git cat-file -p cd0cf6169b870bbafb68f10ea353953ae3fabc8d 
```
