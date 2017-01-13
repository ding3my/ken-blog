#out
linux awk 代替 cut
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|335|365
ref linux cut 字符串 取 指定 列 数据
#alg
```
echo '1 2 3'|cut -d ' ' -f 2
echo '1 2 3'|awk 'BEGIN {FS=" "}{print $2}'
```
#sum
- awk配合管道命令需要简化为awk1
