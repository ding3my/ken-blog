#o
/etc/proxychains.conf
#i
google proxychains
[1]https://github.com/rofl0r/proxychains-ng
/etc/proxychains.conf
#a
```
sudo sed 's/^socks4.*/socks5 127.0.0.1 1080/' /etc/proxychains.conf -i
cat /etc/proxychains.conf
```
#sum
1. https://github.com/rofl0r/proxychains-ng
