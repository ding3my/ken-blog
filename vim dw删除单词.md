#o
vim dw删除单词
#i
Robbins-学习VI和VIM编辑器 7ed|30
#a
```
echo 12 34 56 > v;vim v
```
若光标在3，dw
```
12 56
```
若光标在3前的空格，dw
```
1234 56
```
#sum
- dw识别"\s+"、"\S+\s*"为一个单词
