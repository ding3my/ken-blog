#o
regex 判断nfa正则引擎
#i
Friedl-精通正则表达式 3ed|146
使用'nfa|nfa not'去匹配'nfa not'
google python regex
[1]https://docs.python.org/2/library/re.html
google perl regex output match
http://stackoverflow.com/questions/5617314/perl-regex-print-the-matched
-value
ref linux sed 输出正则匹配文本
#a
```
echo 'nfa not'|grep 'nfa\|nfa not'
echo 'nfa not'|grep -e 'nfa\|nfa not'
echo 'nfa not'|grep -E 'nfa|nfa not'
```
结果显示 nfa not
```
echo 'nfa not'|sed -n 's/\(nfa\|nfa not\)/<\1>/p'
```
结果显示 <nfa not>
```
echo -e 'nfa not'|awk '/nfa|nfa not/'
```
结果显示 nfa not
未完成 不够说服力
```
echo 'nfa not' > v;vim v
```
/nfa\|nfa not
结果匹配 nfa
```
import re;
m = re.search('nfa|nfa not','nfa not');
print(m.group(0))
```
python v.py
结果输出 nfa
```
```
perl p.pl
结果输出 nfa
#sum
- grep不是传统nfa
- vim的/是传统nfa
1. https://docs.python.org/2/library/re.html
