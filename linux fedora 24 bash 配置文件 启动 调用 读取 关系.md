#out
linux fedora 24 bash 配置文件 启动 调用 读取 关系
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|323
google xinitrc
[1]https://wiki.archlinux.org/index.php/Xinitrc_(%E7%AE%80%E4%BD%93%E4%
B8%AD%E6%96%87)
#alg
```
/etc/profile -> ~/.bash_profile
```
```
/etc/profile : /etc/inputrc /etc/profile.d/*.sh
~/.bash_profile : ~/.bashrc
~/.bashrc : /etc/bashrc
/etc/bashrc : /etc/profile.d/*.sh
```
#sum
- "->"表示主线流程
1. https://wiki.archlinux.org/index.php/Xinitrc_(简体中文)
