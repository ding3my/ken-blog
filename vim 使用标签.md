#o
vim 使用标签
#i
Robbins-学习VI和VIM编辑器 7ed|126
#a
```
sudo dnf install ctags -y
echo 'void f1(){}' > a.c
```
vim
:!ctags ./*.c
:tag f1
结果 f1函数补全
