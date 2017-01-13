#out
linux fedora 24 goldendict 添加本地词典
#in
google goldendict 词典 推荐
[1]http://www.cnblogs.com/vimmer/articles/2645734.html
推荐 朗道 英汉 汉英 bz2
[2]http://abloz.com/huzheng/stardict-dic/zh_CN/
#alg
stardict-langdao-ce-gb-2.4.2.tar.bz2
stardict-langdao-ec-gb-2.4.2.tar.bz2
解压
```
ls|grep stardict-langdao-|xargs -n1 tar -jxvf
```
goldendict-edit-dictionary-sources-files 添加词典文件夹
1. http://www.cnblogs.com/vimmer/articles/2645734.html
2. http://abloz.com/huzheng/stardict-dic/zh_CN/
