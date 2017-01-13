#out
gnome 3 alt tab 切换 一个 程序 而不是 一组 程序
#in
google gnome alt tab switch one not group
[1]http://superuser.com/questions/394376/how-to-prevent-gnome-shells-al
ttab-from-grouping-windows-from-similar-apps
google dconf all option
[2]http://askubuntu.com/questions/169704/how-to-search-dconf-for-keys-o
r-values
dconf dump /
dconf help
reset
#alg
```
```
还原
```
```
dconf dump / | less
/bind
#sum
- 推荐使用<Win>Tab
- switch-windows 某程序窗口
- switch-group 一组程序
- switch-applications 一组程序某窗口
- reset删除键值对，空即默认键值对
1. http://superuser.com/questions/394376/how-to-prevent-gnome-shells-alttab-from-grouping-windows-from-similar-apps
2. http://askubuntu.com/questions/169704/how-to-search-dconf-for-keys-or-values
