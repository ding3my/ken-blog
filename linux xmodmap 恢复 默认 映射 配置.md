#out
xmodmap 恢复 默认 映射 配置
#in
google xmodmap 恢复
http://blog.csdn.net/a583886/article/details/46139223
xmodmap 不提供恢复初始化到功能，所以在使用如下指令备份map表，防止map出错
#algo
```
xmodmap -pke > .xmodbak
xmodmap .xmodbak
```
