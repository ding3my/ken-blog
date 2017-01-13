#o
sed替换 ss aes-256-cfb 算法
#i
#a
sed "s/aes-256-cfb/rc4-md5/" /etc/shadowsocks.json -i
sed "s/aes-256-cfb/rc4-md5/" /etc/shadowsocks.json
/etc/init.d/shadowsocks restart
sed "s/rc4-md5/aes-256-cfb/" /etc/shadowsocks.json -i
sed "s/rc4-md5/aes-256-cfb/" /etc/shadowsocks.json
/etc/init.d/shadowsocks restart
