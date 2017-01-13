#o
vim map 将特殊按键作为命令序列一部分
#i
Robbins-学习VI和VIM编辑器 7ed|109
:h key-notation
#a
```
vim
```
:map ` ihi^Mhi
`
结果显示
hi
hi
#sum
- ^M==<C-V><CR>，而不是直接输入^和M
