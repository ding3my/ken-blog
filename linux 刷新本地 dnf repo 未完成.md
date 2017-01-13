#o
#i
refresh repo
[1]http://superuser.com/questions/333542/how-do-i-get-yum-to-see-update
s-to-a-local-repo-without-cleaning-cache
yum clean metadata
#a
```
echo '[local]
dnf list|grep shell-script
```
结果显示
local                           local_repo
disabled
shell-script.noarch
0.1-1                           @System
#sum
1. http://superuser.com/questions/333542/how-do-i-get-yum-to-see-updates-to-a-local-repo-without-cleaning-cache
