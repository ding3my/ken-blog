#o
vim zf 创建折叠
#i
Robbins-学习VI和VIM编辑器 7ed|244
默认:set fdc=12
#a
```
echo -e '1\n2\n3' > v;vim v
```
Gzf{up}
结果
折叠栏显示
```
-           1$
|           2$
            3$
```
#sum
- 减号表示一个折叠
- 竖线表示对应内容2从属这个折叠
- 折叠可以重复创建，zf{left or right}
