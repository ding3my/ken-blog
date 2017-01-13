#o
#i
google rpm size
[1]http://forgetmenotes.blogspot.jp/2009/08/sort-installed-rpms-by-size
.html
#a
rpm -qa --qf '%{size} %{name}\n'|sort -n
#sum
- size tag需要放在name前面，sort需要使用size
- sort使用方法，未完成
1. http://forgetmenotes.blogspot.jp/2009/08/sort-installed-rpms-by-size.html
2. http://archive.download.redhat.com/pub/redhat/linux/9/en/doc/RH-DOCS/maximum-rpm-1.0/html/ch-queryformat-tags.html
