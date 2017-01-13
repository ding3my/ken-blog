#o

#i
google ls find xargs
Fix "find xargs | ls -l" for files with spaces in name
	find /folder -type f -mmin -20 2>/dev/null | xargs ls -l
#a
```
find . -type f| xargs -d "\n" ls -l
```
#sum

