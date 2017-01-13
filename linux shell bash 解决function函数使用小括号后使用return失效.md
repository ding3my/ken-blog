#o
无法解决，语言特性
#i
findn功能发现问题
[1]https://segmentfault.com/q/1010000007783580
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|328
#a
```
function fff(){
(return)
echo 1
}
fff
```
结果输出1
```
function fff(){
{return}
echo 1
}
fff
```
结果 bash: {return}: command not found...
#sum
- 不要使用and or 且或代替if，在不允许子进程出现的时候，and or 且或 一般要用子进程，除非不使用小括号
1. https://segmentfault.com/q/1010000007783580
