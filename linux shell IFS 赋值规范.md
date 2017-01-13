#o
$'string'
#i
google shell IFS dollar sign
http://stackoverflow.com/questions/4128235/what-is-the-exact-meaning-of-ifs-n
Normally bash doesn't interpret escape sequences in string literals. So if you write \n or "\n" or '\n', that's not a linebreak - it's the letter n (in the first case) or a backslash followed by the letter n (in the other two cases).
ANSI C-quoted strings.

bash manual
3.1.2.4 ANSI-C Quoting
Words of the form $'string' are treated specially. The word expands to string, with backslash-escaped characters replaced as specified by the ANSI C standard. 
3.5.7 Word Splitting
IFS
5.1 Bourne Shell Variables
IFS
8.8 A Programmable Completion Example
    local IFS=$' \t\n'    # normalize IFS
#a
```
echo -n $'\n' | od -c
echo -n '\n' | od -c
echo -n $"\n" | od -c
echo -n "\n" | od -c
```
output:
0000000  \n
0000001
0000000   \   n
0000002
0000000   \   n
0000002
0000000   \   n
0000002
#sum

