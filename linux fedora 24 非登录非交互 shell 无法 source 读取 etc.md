#out
linux fedora 24 非登录非交互 shell 无法 source 读取 /etc/profile.d/*.sh
#in
vim /etc/profile.d/colorls.sh
#alg
```
# Skip all for noninteractive shells.
```
grep '# Skip all for noninteractive shells.' /etc/profile.d/*.sh -l
输出 /etc/profile.d/colorls.sh
#sum
- /etc/profile.d/colorls.sh，只有colorls.sh不让非登录非交互shell读取
