#o
sed 's///gp' -n
#i
google sed 输出 修改 的行
[1]https://my.oschina.net/jccpp/blog/118278
-n p
#a
```
echo -e '1\n2\n3\n4' | sed -n '2,3s/[0-9]/n/p'
```
结果显示
n
n
```
echo -e '1\n2\n3\n4' | sed -n '2,3s/[0-9]/n/'
```
结果显示空
```
echo -e '1\n2\n3\n4' | sed '2,3s/[0-9]/n/p'
```
结果显示
1
n
n
n
n
4
#sum
1. https://my.oschina.net/jccpp/blog/118278
