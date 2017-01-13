#o
vim 于上下文相关的替换
#i
Robbins-学习VI和VIM编辑器 7ed|78
#a
```
echo -e '1 a\n2 a\n1 a'  > v;vim v
:g/1/s/a/b/g
```
结果显示'1 b\n2 a\n1 b'
