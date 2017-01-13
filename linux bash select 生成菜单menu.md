#o
#i
google bash  select
How can I create a select menu in a shell script?
select opt in "${options[@]}"
#a
```
ar=(1 2)
select f in "${ar[@]}" ; do
	echo $f
done 
```
#sum
