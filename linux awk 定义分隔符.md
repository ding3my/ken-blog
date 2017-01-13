#out
linux awk 定义分隔符
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|365
#out
```
echo '1|2'|awk '{FS="|"}{print $1}'
echo '1|2'|awk 'BEGIN{FS="|"}{print $1}'
```
#sum
- {}与{}之间可以不用空格
