#out
linux xmodmap 查看 原始 按键 keycode keysym
#in
google xmodmap
[1]https://wiki.archlinux.org/index.php/xmodmap
#alg
案例，未修改过xmodmap
```
xmodmap -pke | grep -i esc
xmodmap -pke | grep -i caps
```
#sum
- grep 默认区分大小写
1. https://wiki.archlinux.org/index.php/xmodmap
