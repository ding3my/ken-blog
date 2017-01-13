#o
参考#a
#i
Robbins-学习VI和VIM编辑器 7ed|76
google E486: Pattern not found
[1]http://stackoverflow.com/questions/5289262/vim-does-not-find-and-rep
lace-simple-phrase-that-is-clearly-present
Without the % symbol Vim only matches and replaces on the current line.
#a
```
echo -e '1\n1\n1' > v ; vim v
```
:s/1/2/
结果显示
2
1
1
```
echo -e '1\n1\n1' > v ; vim v
```
:s/1/2/g
结果显示
2
1
1
```
echo -e '1\n1\n1' > v ; vim v
```
:%s/1/2/
结果显示
2
2
2
```
echo -e '11\n11\n11' > v ; vim v
```
:%s/1/2/
结果显示
21
21
21
```
echo -e '11\n11\n11' > v ; vim v
```
:%s/1/2/g
结果显示
22
22
22
#sum
- :s/old/new/ == :1s/old/new/
- g表示替换当前行所有匹配，否则最多替换一次
1. http://stackoverflow.com/questions/5289262/vim-does-not-find-and-replace-simple-phrase-that-is-clearly-present
