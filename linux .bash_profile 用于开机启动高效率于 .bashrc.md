#out
linux .bash_profile 相对于.bashrc 更适用于第一次启动初始化
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|323
login shell 才会读取 .bash_profile
#alg
存在软件只需启动一次即可，例如fcitx
#sum
- .bash_profile 类似 windows 的启动文件夹
- .bash_profile 配置PATH变量高效率于 .bashrc，.bashrc可能会重复配置PATH，导致PATH过长
