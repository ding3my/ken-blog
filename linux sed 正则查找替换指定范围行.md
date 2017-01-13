#o
s
#i
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|359
Blum-Linux命令行与Shell脚本编程大全 2ed|386
-n 禁止sed输出 p 输出修改过的行
#a
```
echo -e '1\n2\n3\n4' | sed '2,4s/\d/n/g'
```
结果输出
1
2
3
4
```
echo -e '1\n2\n3\n4' | sed '2,4s/[0-9]/n/g'
```
结果输出
1
n
n
4
```
echo -e '1\n2\n3\n4' | sed -n '2,4s/[0-9]/n/g'
```
结果输出空
#sum
- sed不匹配\d 为什么 未完成
- -n 禁止sed输出 p 输出修改过的行
