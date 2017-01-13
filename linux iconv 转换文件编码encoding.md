#o
#i
google linux convert file encoding
http://stackoverflow.com/questions/64860/best-way-to-convert-text-files-between-character-sets
iconv -f UTF-8 -t ISO-8859-1 in.txt > out.txt

http://stackoverflow.com/questions/11316986/how-to-convert-iso8859-15-to-utf8
iconv -f ISO-8859-14 Agreement.txt -t UTF-8 -o agreement.txt
iconv -t UTF-8 YourFile.txt

google linux 转换 编码
linux下查看文件编码及修改编码
iconv -f UTF-8 -t GBK file1 -o file2
#a
```
echo 啊 > t ; file -i t ; iconv -t gbk t -o t ; file -i t ; 
```
output:
t: text/plain; charset=utf-8
t: text/plain; charset=iso-8859-1
#sum
