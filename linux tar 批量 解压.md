#out
linux tar 批量 解压
#in
google not found in archive tar
[1]http://stackoverflow.com/questions/16933221/shell-tar-not-found-in-a
rchive-error-when-using-regular-expression
it is caused by the fact that argument syntax of tar accept just one
single tar in the command line and the rest is interpreted as something
else.
google tar 批量
[2]http://blog.sina.com.cn/s/blog_4af3f0d20100ijxx.html
#alg
ls *.tar.gz | xargs -n1 tar -xzvf
#sum
- for tar in *.tar.gz;
do tar xvf $tar; done
- find -maxdepth 1 -name "*.bz2"|xargs -i tar xvjf {}
1. http://stackoverflow.com/questions/16933221/shell-tar-not-found-in-archive-error-when-using-regular-expression
2. http://blog.sina.com.cn/s/blog_4af3f0d20100ijxx.html
