#out
linux xmodmap 映射 caps 为 esc caps
#in
ref linux xmodmap 映射
ref linux xmodmap 查看 原始 按键 keycode keysym
#alg
vim .xmodmap
```
keysym Caps_Lock = Escape Caps_Lock
```
xmodmap .xmodmap
