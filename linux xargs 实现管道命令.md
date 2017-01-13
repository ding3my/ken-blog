#out
linux xargs 实现管道命令|
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|342
#alg
案例，启动gedit
```
ps -A|grep 'gedit'|awk '{print $1}'|xargs kill -
```
#sum
- kill不支持管道
