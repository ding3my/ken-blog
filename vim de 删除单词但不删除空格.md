#o
vim de 删除单词但不删除空格
#i
Robbins-学习VI和VIM编辑器 7ed|30
#o
```
echo 12 34 > v;vim v
```
若光标在1，de
```
 34
```
若光标在2，de
```
1
```
#sum
- de识别"\S{}"、"\S\s*\S+"为单词
