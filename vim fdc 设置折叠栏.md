#o
vim fdc 设置折叠栏
#i
Robbins-学习VI和VIM编辑器 7ed|248
#a
```
echo -e '0\n\t1\n\t\t2\n\t\t\t3' > v;vim v
:set fdc=12
:set fdm=indent
:set fdl=3
```
结果显示全部展开
