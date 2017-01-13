#o
od -c or od -d[SIZE]
#i
google shell ifs
http://blog.csdn.net/whuslei/article/details/7187639
 Shell中的IFS解惑 
echo "$IFS" | od -b

google shell od
http://man.linuxde.net/od
od -c tmp

鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed 177
od

man od
#a
```
echo -n 1 | od
echo -n 1 | od -o
echo -n 1 | od -c
echo -n 1 | od -d
echo -n 1 | od -d1

```
output:
0000000 000061
0000001
0000000 000061
0000001
0000000   1
0000001
0000000    49
0000001
0000000    49
0000001
#sum
