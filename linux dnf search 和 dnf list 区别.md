#o
参考#a
#i
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|705
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|678
rpm 软件名称 文件名称
#a
```
dnf search rp-pppo
dnf search rp-pppoe.
dnf list rp-pppo
dnf list rp-pppoe
dnf list rp-pppo*
dnf list *p-pppo*
```
结果显示分别是
rp-pppoe.x86_64
Error: No matches found.
Error: No matching Packages to list
rp-pppoe.x86_64
rp-pppoe.x86_64
rp-pppoe.x86_64
dnf search 可以查询部分软件名称，可以使用通配符，默认使用通配符，不区分大小写，但是不能查询软件版本
dnf list 只能查询完整软件名称，可以使用通配符*，不区分大小写
dnf search 不能列出版本号
dnf list 能列出版本号
#sum
- dnf install 类似 dnf list
