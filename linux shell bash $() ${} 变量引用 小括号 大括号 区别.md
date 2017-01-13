#out
$()内执行表达式expr，${}内执行变量
$()返回命令输出值，${}返回变量值
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|301
google BASH_SOURCE
[1]http://stackoverflow.com/questions/39340169/dir-cd-dirname-bash-sour
ce0-pwd-how-does-that-work
${} acts as a kind of quoting for variables.
$() acts as a kind of quoting for commands but they're run in their own
context.
#alg
```
$(uname -r)
${PATH}
```
#sum
- $()返回命令输出值，${}返回变量值
1. http://stackoverflow.com/questions/39340169/dir-cd-dirname-bash-source0-pwd-how-does-that-work
