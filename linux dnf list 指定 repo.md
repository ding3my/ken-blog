#o
dnf --disablerepo="*" --enablerepo="fedora" list
#i
google yum refresh repo
[1]http://superuser.com/questions/333542/how-do-i-get-yum-to-see-update
s-to-a-local-repo-without-cleaning-cache
-disablerepo=* --enablerepo=myrepo
#a
```
dnf --disablerepo="*" --enablerepo="fedora" list available|wc
dnf --disablerepo="*" --enablerepo="updates" list available|wc
dnf --disablerepo="*" list available|wc
```
  49283  143786 3965143
  13423   39545 1081276
      0       0       0
#sum
1. http://superuser.com/questions/333542/how-do-i-get-yum-to-see-updates-to-a-local-repo-without-cleaning-cache
