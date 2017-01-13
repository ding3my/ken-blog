#o
dnf download rp-pppoe --destdir ~/Downloads
#i
google dnf downloadonly
[1]https://bugzilla.redhat.com/show_bug.cgi?id=1209638
#a
```
dnf download rp-pppoe --destdir ~/Downloads
```
#sum
- dnf没有直接指定目录的方法
- dnf download rp-pppoe --destdir=.
- dnf download 默认下载路径为 .
1. https://bugzilla.redhat.com/show_bug.cgi?id=1209638
