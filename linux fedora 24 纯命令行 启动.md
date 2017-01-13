#out
linux fedora 24 纯命令行 启动
#in
Google inittab is no longer used
http://www.cnblogs.com/lanston/p/3880577.html
#alg
```
ln -sf /lib/systemd/system/runlevel3.target
/etc/systemd/system/default.target
```
