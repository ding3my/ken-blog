#o
sudo rpm -ivh
[1]http://rpms.famillecollet.com/fedora/remi-release-24.rpm
#i
google top linux repo
[2]http://tecadmin.net/top-5-yum-repositories-for-centos-rhel-systems/
http://rpms.famillecollet.com/
#a
案例
```
sudo rpm -ivh
[3]http://rpms.famillecollet.com/fedora/remi-release-24.rpm
cat /etc/yum.repos.d/remi.repo
dnf list | wc
sudo sed 's/enabled=0/enabled=1/g' /etc/yum.repos.d/remi.repo -i
dnf list | wc
```
结果显示[remi]信息
  53920  157198 4346692
  55073  160594 4439753
```
dnf repolist all|grep remi
```
结果显示
remi                            Remi's RPM repository - Fedora 2
enabled:  2,675
#sum
- 默认enabled=0
1. http://rpms.famillecollet.com/fedora/remi-release-24.rpm
2. http://tecadmin.net/top-5-yum-repositories-for-centos-rhel-systems/
3. http://rpms.famillecollet.com/fedora/remi-release-24.rpm
