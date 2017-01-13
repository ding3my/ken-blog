#out
linux export var 等价于 declare -x var
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|308|310
google env export 区别
[1]http://blog.csdn.net/longxibendi/article/details/6125075
export readonly
#alg
```
unset vvv
vvv=1
export vvv
env|grep vvv
unset vvv
declare -x vvv=1
env|grep vvv
unset vvv
export vvv=1
env|grep vvv
```
输出
vvv=1
vvv=1
vvv=1
1. http://blog.csdn.net/longxibendi/article/details/6125075
