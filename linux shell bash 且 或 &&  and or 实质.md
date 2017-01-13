#o
e1 op e2 op e3 == ( e1 op e2 ) op e3
#i
google bash and or operator
[1]http://unix.stackexchange.com/questions/24684/confusing-use-of-and-o
perators
#a
案例
```
false || false && echo 1
true || false && echo 1
false || true && echo 1
true || true && echo 1
```
分别输出 空 1 1 1
e1 op e2 op e3 == ( e1 op e2 ) op e3
PS:
e==expression
op=&& or ||
#sum
- bash可以使用小括号构成原子操作
- bash可以直接使用false、true关键字
- ! false == true，exam
```
! false && echo 1
```
1. http://unix.stackexchange.com/questions/24684/confusing-use-of-and-operators
2. https://bash.cyberciti.biz/guide/Logical_Not_!
