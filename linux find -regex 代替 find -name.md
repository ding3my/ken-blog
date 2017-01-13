#out
linux find -regex 代替 find -name
#in
ref linux 统计输出行数
#alg
```
find . -regex '.*\.sh'|wc -l
find . -name '*.sh'|wc -l
```
#sum
- find必须完整匹配内容
