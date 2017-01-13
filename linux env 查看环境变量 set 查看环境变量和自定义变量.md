#out
linux env 查看环境变量 set 查看环境变量和自定义变量
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|304|305|309
全局变量 局部变量
#alg
```
unset vvv
vvv=1
set|grep vvv
env|grep vvv
export vvv
set|grep vvv
env|grep vvv
```
输出
vvv=1
空
vvv=1
vvv=1
