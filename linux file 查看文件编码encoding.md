#o
#i
google linux file encoding
http://stackoverflow.com/questions/805418/how-to-find-encoding-of-a-file-in-unix-via-scripts
file -i
#a
```
echo 1 > t ; file -i t
echo 啊 > t ; file -i t
```
output:
t: text/plain; charset=us-ascii
t: text/plain; charset=utf-8
#sum
