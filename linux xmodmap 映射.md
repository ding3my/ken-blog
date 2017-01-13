#out
linux xmodmap 映射
#in
ref linux xmodmap 查看 原始 按键 keycode keysym
google xmodmap tutorial
http://cs.gmu.edu/~sean/stuff/n800/keyboard/old.html
keysym equal = equal plus notequal plusminus
keycode codenum = equal plus notequal plusminus
#alg
```
echo 'keycode 66 = 1 2' > .xmodmap
xmodmap .xmodmap
```
caps输出1
shift caps输出2
#sum
- 运行，xmodmap conf
- ~~感觉keycode比keysym更稳定~~，实质一样的，ref linux xmodmap keycode keysym 区别
