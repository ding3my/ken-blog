#o
sudo dnf install xxx --downloadonly
#i
google yum download only
[1]https://access.redhat.com/discussions/1571653
#a
```
sudo dnf install rp-pppoe --downloadonly
```
The downloaded packages were saved in cache until the next successful
transaction.
```
sudo find /var/cache -name '*pppoe*.rpm'
```
结果显示软件路径
sudo dnf install xxx --downloadonly
#sum
- 可以使用dnf download代替
1. https://access.redhat.com/discussions/1571653
