#o
有效
#i
#a
```
function fff(){
true && echo 1 && return
true && echo 2
echo end
}
fff
```
输出空
```
function fff(){
true && exit
echo 1
}
fff
```
退出terminal
#sum
