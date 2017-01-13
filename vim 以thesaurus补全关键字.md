#o
vim 以thesaurus补全关键字
#i
Robbins-学习VI和VIM编辑器 7ed|265
#a
```
echo -e 'aa bb\n11 22' > .thes
vim
```
:set thesaurus=~/.thes
i11^x^t
结果显示 11 22 列表
