#o
#i
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|282
#a
```
vim v
```
<c-z>
ls -a
这里会显示 .v.swp 在vim v后产生
```
kill -s 9 %1
vim v
```
输入e，查看内容是否正常
如果正常则:!rm .v.swp
如果不正常则:q退出，vim v，r，最后:!rm .v.swp
#sum
- :!rm .v.swp 亦可删除swp文件
