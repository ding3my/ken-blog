#o
#i
Robbins-学习VI和VIM编辑器 7ed|250
ref vim fdc 设置折叠栏
#a
```
echo -e '0\n\t1\n\t\t2\n\t\t\t3' > v;vim v
:set fdm=indent
:set fdl=1
```
第3、4行被折叠
#sum
- .vimrc注释掉“set ts=4”，用双引号注释，成功
