#o
${!i}
#i
google shell positional parameters for loop
How to iterate over positional parameters in a Bash script?
for ((i=1; i<=$#; i++))
do
    grep "$str" ${filename}${!i}.txt
done

https://www.gnu.org/software/bash/manual/bash.html#Positional-Parameters
3.4.1 Positional Parameters

#a
```
f(){ v=2 ; echo ${!v} ;} ; f a b c
```
#sum

