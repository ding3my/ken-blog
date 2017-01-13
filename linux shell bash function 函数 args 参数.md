#out
linux bash function 函数 args 参数
#in
Blum-Linux命令行与Shell脚本编程大全 2ed|342
#alg
```
function fun(){
    echo $# $1 $2
}
fun a b
```
输出 2 a b
```
function fun(){
    echo $# $1 $2
}
fun 'a b'
```
输出 1 a b
#sum
- echo不存在的参数，不报错
