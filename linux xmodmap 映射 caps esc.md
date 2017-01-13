#out
linux xmodmap 映射 caps esc
#in
ref linux xmodmap 查看 原始 按键 keycode
ref linux xmodmap 映射
#alg
```
echo 'keycode  66 = Escape' > .xmodmap
echo 'keycode  9 = Caps_Lock' >> .xmodmap
xmodmap .xmodmap
```
#sum
- 推荐'keycode  66 = Escape Caps_Lock'代替，少修改一个Esc按键
baidu xmodmap 组合键
https://www.zhihu.com/question/28643416
