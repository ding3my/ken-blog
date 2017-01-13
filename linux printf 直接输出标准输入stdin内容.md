#o
#i
google shell readarray new line
http://stackoverflow.com/questions/11393817/bash-read-lines-in-file-into-an-array
printf '%s\n' "${lines[@]}"
#a
v.sh
```
IFS=$'\n'
printf '%s\n' $(</dev/stdin)
```
echo -e "a a\nb b\nc c" | v.sh
#sum
- 必须修改IFS，IFS默认中有空格
