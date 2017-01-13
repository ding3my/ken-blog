#o
vim zA递归切换折叠状态
#i
Robbins-学习VI和VIM编辑器 7ed|244
:help zA
When on a closed fold: open it
When on an open fold: close it recursively and set 'foldenable'.
#a
```
echo -e '1\n2\n3' > v;vim v
```
Gzf{up}zf{up}
zazazA
结果显示展开一个折叠（12）、展开所有折叠（123）
#sum
- a是当前折叠取反，若是-则变为+
- A只是递归打开，但是不会递归关闭，例如Gzf{up}zf{up}后，zAzAza，展开所有折叠（123）
