# Check it out

## Restore first snapshot
identify the first commit
```
git log --reverse --oneline
```
```
git checkout e317d03
cat hello.sh
```

## Restore second snapshop
```
git log --oneline
```
```
git checkout e317d03
cat hello.sh
```

## Return to latest version

```
git checkout master
```
```
git pull master
```
```
cat hello.sh
```

