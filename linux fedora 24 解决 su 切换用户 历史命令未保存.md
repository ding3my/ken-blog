#out
linux fedora 24 解决 su 切换用户 历史命令未保存
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|318|325
history -w
"注销时才会更新记录文件"
.bash_history
#alg
未保存
```
cat ~/.bash_history
echo 1
cat ~/.bash_history
```
保存
```
cat ~/.bash_history
echo 1
history -w
cat ~/.bash_history
```
解决方案
```
alias su='history -w;su'
```
