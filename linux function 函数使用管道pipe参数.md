#o
#i
google shell function pipeline
How to compose bash functions using pipes?
function X {
  while read data; do
    ...process...
  done
}
#a
```
f(){ read v; echo $v ;} ; echo hi | f
```
#sum
