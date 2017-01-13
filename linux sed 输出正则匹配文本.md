#o
() 未完成术语？
#i
google sed output match
[1]http://stackoverflow.com/questions/17511639/sed-print-only-matching-
group
#a
```
echo 12 | sed -n 's/\(1\|12\)/<\1>/p'
echo 12 | sed -n 's/\(1\|1\)/<\1>/p'
```
分别输出
<12>
<1>2
#sum
- 使用小括号()
1. http://stackoverflow.com/questions/17511639/sed-print-only-matching-group
