#o
#i
Robbins-学习VI和VIM编辑器 7ed|108

:h map

google vim map key
http://yyq123.blogspot.jp/2010/12/vim-map.html
:h key-notation

google vim 映射 波浪符号
[1]http://www.seejoke.com/question/4709
imap ` <C-p>
google vim map ctrl backquote
[2]https://www.google.com/search?q=vim+map+ctrl+backquote&spell=1&sa=X&
ved=0ahUKEwiY2Jmh7-jQAhWLTrwKHcYFCawQBQgZKAA&biw=1472&bih=646
` (backtick, 0x60) and 1 (one, 0x31) fall in none of the above
categories, so Vim doesn't know about their Ctrl combinations.
#a
```
vim
:map ` ihi
`
```
结果显示hi
#sum
- <C-`>不可map，参考#i
1. http://www.seejoke.com/question/4709
2. https://www.google.com/search?q=vim+map+ctrl+backquote&spell=1&sa=X&ved=0ahUKEwiY2Jmh7-jQAhWLTrwKHcYFCawQBQgZKAA&biw=1472&bih=646
