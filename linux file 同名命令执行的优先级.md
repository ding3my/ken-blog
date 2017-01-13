#out
当前目录file命令 > PATH路径file命令，靠前PATH路径file命令 > 靠后PATH路径file命令
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|298
file type -t
#alg
```
cd ~
mkdir d1 d2 d3
echo 'echo 1' > ~/d1/ttt
echo 'echo 2' > ~/d2/ttt
echo 'echo 3' > ~/d3/ttt
chmod +x d1/ttt d2/ttt d3/ttt
PATH=$PATH:~/d1:~/d2:~/d3
ttt
echo 'echo 4' > ~/ttt
chmod +x ttt
ttt
```
输出
1
4
#sum
- 当前目录file命令 > PATH路径file命令，靠前PATH路径file命令 > 靠后PATH路径file命令
