#out
linux bash 获取执行脚本路径
#in
google linux bash 执行 脚本 路径
[1]http://metman.info/blog/2014/11/05/bashjiao-ben-huo-qu-zi-shen-lu-ji
ng-fang-fa/
#alg
```
cd /
echo 'echo $(pwd)/${BASH_SOURCE[0]}' > ~/t.sh
. ~/t.sh
```
#sum
- $(pwd)/${BASH_SOURCE[0]}有问题，用户不会按照规范来输入路径
1. http://metman.info/blog/2014/11/05/bashjiao-ben-huo-qu-zi-shen-lu-jing-fang-fa/
