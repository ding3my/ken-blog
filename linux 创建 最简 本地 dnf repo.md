#o
参考#a
#i
google local repo
[1]https://wiki.centos.org/HowTos/CreateLocalRepos
google fedora 本地 repo
[2]http://www.tsingpost.com/articles/201403/499.html
createrepo
google dnf createrepo
[3]https://ask.fedoraproject.org/en/question/74027/how-to-create-useful
-local-repository/
google 重定向 Permission denied
[4]https://fukun.org/archives/05232211.html
echo “xxxx” | sudo tee -a test.txt
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed
yum 设置文件 709
yum repolist all
yum clean all
google repo format
https://docs.fedoraproject.org/en-US/Fedora/24/html/System_Administrato
rs_Guide/index.html
[5]6.3. Configuring DNF and DNF Repositories
repo format
#a
```
#clean
sudo rm /var/local_repo -rf
sudo rm /etc/yum.repos.d/local.repo
#init
sudo mkdir /var/local_repo
sudo createrepo_c -v /var/local_repo
echo '[local]
baseurl=file:///var/local_repo
enabled=1' | sudo tee -a /etc/yum.repos.d/local.repo
dnf repolist all|grep local
```
结果显示
local                           local
enabled:      0
#sum
- 书里没有说明createrepo，需要google
- fedora24 没有 createrepo，只有craeterepo_c用法一样
- repo 格式参考官方文档
- 直接把rpm包放入baseurl目录即可检索
1. https://wiki.centos.org/HowTos/CreateLocalRepos
2. http://www.tsingpost.com/articles/201403/499.html
3. https://ask.fedoraproject.org/en/question/74027/how-to-create-useful-local-repository/
4. https://fukun.org/archives/05232211.html
5. https://docs.fedoraproject.org/en-US/Fedora/24/html/System_Administrators_Guide/sec-Configuring_DNF_and_DNF_Repositories.html
