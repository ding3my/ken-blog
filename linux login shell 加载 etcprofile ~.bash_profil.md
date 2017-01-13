#out
linux login shell 加载 /etc/profile ~/.bash_profile ~/.bashrc /etc/bashrc
#in
virtualbox fedora 24 runlevel 3
#alg
在各个文件第二句添加echo对应语句
reboot，登录后显示
```
Last login: Sun Dec 4 08:46:03 on tty1
/etc/profile
Sun Dec 4 08:46:21 CST 2016
.bash_profile
.bashrc
/etc/bashrc
```
#sum
- 此法成本过高，还要安装虚拟机
