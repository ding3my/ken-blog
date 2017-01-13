#out
linux alias 换行需要添加反斜杠\
#in
google alias 转义
https://zh.wikipedia.org/wiki/Alias_(%E5%91%BD%E4%BB%A4)
#alg
正确
```
alias ali='echo 1;\
echo 2'
ali
```
错误
```
alias ali='echo 1;
echo 2'
ali
```
