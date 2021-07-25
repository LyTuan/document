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

4. Ubuntu, if a repository is not secure, we can remove it. 
```
sudo apt-add-repository -r ppa:armagetronad-dev/ppa
sudo apt update -q
```
5. Change timezone for server ubuntu 
```
timedatectl
timedatectl list-timezones
sudo timedatectl set-timezone your_time_zone
```

6. How to use github
```
git add .
git commit -m "message"
git push origin master
```

7. Fix the Ubuntu 20.04 cannot share screen in google meet or Team MS
```
run $ sudo vi /etc/gdm3/daemon.conf
Uncomment #WaylandEnable=false
Reboot.
```
