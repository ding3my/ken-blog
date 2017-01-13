#o
vim 打开多个文件
#i
Robbins-学习VI和VIM编辑器 7ed|72
:n 72
:args 73
:rewind 73
:w 73
:e 74
#a
```
echo 1 > v1;echo 2 > v2;echo 3 > v3
vim v1 v2 v3
:ar
```
结果显示[v1] v2 v3
:n | :ar
结果显示 2 和 v1 [v2] v3
:rew|:w! v11|:!grep '' v11
结果显示1
:rew|:n|:n|:rew|:ar
结果显示[v1] v2 v3
:e 3 | :ar
结果显示 3 和 [v1] v2 v3，不一致
