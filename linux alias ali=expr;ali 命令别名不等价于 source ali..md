#out
linux alias ali=expr;ali 等价于 source ali.sh
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|317|379
alias source
ref linux alias 实质是字符串替换
#alg
```
alias ali='echo'
echo 'echo' > ali.sh
ali hi
source ali.sh hi
```
输出
hi
空
#sum
- 替换可以接收参数使用参数，但是脚本如果没有编写表达式参数，则不会使用参数
