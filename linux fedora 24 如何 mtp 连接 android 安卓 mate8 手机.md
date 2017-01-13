#o
参考#a
#i
google fedora 24 mtp
http://nknu.net/mount-nexus5-on-fedora23-using-simple-mtpfs/
#a
```
echo 'SUBSYSTEM=="usb", ATTR{idVendor}=="", ATTR{idProduct}="",
SYMLINK="hwm8"' > /etc/udev/rules.d/10-phone.rules
mkdir /tmp/hwm8
simple-mtpfs /dev/hwm8 /tmp/hwm8
cd /tmp/hwm8
```
RT>6，echo那步需要查看dmesg
#sum
