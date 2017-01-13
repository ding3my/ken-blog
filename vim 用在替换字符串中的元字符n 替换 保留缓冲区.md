#o
vim 用在替换字符串中的元字符\n
#i
Robbins-学习VI和VIM编辑器 7ed|83
#a
```
echo abc > v;vim v
:s/\(ab\)/\1c/g
```
结果显示abcc
