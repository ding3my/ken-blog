#out
linux bash脚本 #!/bin/bash 不会加载 ~/.bashrc
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|375
#!/bin/bash ~/.bashrc
google bash 脚本 开头
https://linux.cn/thread-2882-1-1.html
#alg
vim ~/.bashrc
添加
```
vvv=1
```
新增无#!/bin/bash脚本
```
echo 'echo $vvv' >> t.sh
t.sh
```
输出 空
添加#!/bin/bash到脚本
```
echo '#!/bin/bash' > t.sh
echo 'echo $vvv' >> t.sh
t.sh
```
输出空
#sum
- 书上有误，#!/bin/bash表示指定shell程序，需要完整环境变量，最保险还是 "source /etc/profile ;
source ~/.bash_profile"
