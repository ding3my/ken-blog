#o
sed -E
#i
google sed number
Why does this sed command to match number not work?

#a
right
```
sed -En 's|[0-9]+|aaa|p'
```
wrong
```
sed -n 's|[0-9]+|aaa|p'
```
#sum

