#out
linux bash 跟踪 脚本 输出
#in
鸟哥-鸟哥的Linux私房菜 基础学习篇 3ed|397
#alg
vim tmp.sh
```
echo 1
echo 2
```
sh -vx tmp.sh
```
module () {  eval `/usr/bin/modulecmd bash $*`
}
scl () {  local CMD=$1;
 if [ "$CMD" = "load" -o "$CMD" = "unload" ]; then
 eval "module $@";
 else
 /usr/bin/scl "$@";
 fi
}
echo 1
+ echo 1
1
echo 2
+ echo 2
2
```
