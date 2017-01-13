#o
vim 多开复制文本到另一个文件
#i
Robbins-学习VI和VIM编辑器 7ed|74
#a
```
echo 1 > v1;echo 2 > v2
vim v1 v2
yy
:e v2
p
```
结果显示
2
1
