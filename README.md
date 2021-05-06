# document
1. Git rebase and resolve conflig
```
Step 1: Checkout về nhánh dev 
Step 2: Pull code mới nhất về nhánh dev
    $ git pull origin dev
Step 3: Checkout quay về nhánh đang bị conflicts
Step 4: Rebase với nhánh dev
    $ git rebase dev
Step 5: Resolve các conflicts
Step 6: Sau khi resolve conflicts xong chạy
    $ git add .
    $ git rebase --continue

```
2. Git update code 
```
git fetch -a 
git checkout origin/name_branch
```

3. Git rollback change all file
```
git checkout .
```
