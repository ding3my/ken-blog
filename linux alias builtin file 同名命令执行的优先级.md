#out
alias > builtin > file
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|298
file alias builtin
type -t
cd builtin
#alg
```
alias cd='echo ali'
cd
unalias cd
```
输出 ali
alias > builtin
```
echo 'echo file' > cd
chmod +x cd
cd
```
输出 空
builtin > file
综上，alias > builtin > file
