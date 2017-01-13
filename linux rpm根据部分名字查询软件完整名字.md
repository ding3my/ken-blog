#o
rpm -qa|grep
#i
google rpm 不支持 通配符
[1]http://www.linuxdiyf.com/linux/24709.html
需要注意的是这里rpm命令查询的时候不支持通配符，如果使用*去通配的话会导致识别为软件包名称的一个字符。
#a
```
rpm -qa|grep -i pam
```
#sum
1. http://www.linuxdiyf.com/linux/24709.html
