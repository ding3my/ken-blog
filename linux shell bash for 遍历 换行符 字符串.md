#out
linux bash for 遍历 换行符 字符串
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|395
#alg
```
vv=$(echo -e 'a\nb')
for v in $vv
do
    echo $v 0
done
```
#sum
- 'echo $v 0'，0用于验证变量行数
