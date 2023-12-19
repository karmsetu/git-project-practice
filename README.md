# git-project-practice
this is a testing/practice repository for working in project with git

## Branching
```bash
git checkout -b <branchName>
```

### how to know current branch
```bash
git branch
```
### delete branch
```bash
git branch -D <fileName>
```


## Adding
```bash
git add <fileName> or .
```

## commit
```bash
git commit -m "<message>"
```
- saves snapshot locally

## push
```bash
git push -u origin <branchName>
```

## pull
```bash
git pull origin main
```
- pull from the main/ merged directory
`git pull`

## GitHub UI merge
- from sender
![specifyung pull req](./img/git-pull-req.png)
- From inspector
![accepting merge](./img/git-accept-merge.png)