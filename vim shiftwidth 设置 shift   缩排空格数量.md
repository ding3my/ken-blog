#o
vim shiftwidth 设置 shift << >> 缩排空格数量
#i
Robbins-学习VI和VIM编辑器 7ed|125
#a
```
vim
:set sw=4
:set list
i1{esc}
>>>>>>
结果显示
```
^I    1$
```
#sum
- 如果sw长度等于ts，则使用shift移位则插入tab制表符，可以保存后使用gedit测试
- 默认sw=8 ts=8
