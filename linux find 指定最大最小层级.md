#out
linux find 指定最大最小层级
#in
google linux find level
[1]http://unix.stackexchange.com/questions/93323/list-subdirectories-on
ly-n-level-deep
#alg
```
cd /
```
sudo find -maxdepth 1 -mindepth 0 -name '.bashrc'
输出 空
sudo find -maxdepth 2 -mindepth 0 -name '.bashrc'
输出 ./root/.bashrc
sudo find -maxdepth 2 -mindepth 3 -name '.bashrc'
输出 空
1. http://unix.stackexchange.com/questions/93323/list-subdirectories-only-n-level-deep
