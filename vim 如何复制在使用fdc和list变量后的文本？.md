#o
未完成
#i
复制时会把序号和符号给复制进去
google vim 复制 list 问题
http://lvii.github.io/soft/2011/04/10/gvim-copy-paste/
#a
添加到.vimrc
nnoremap <C-a> :setlocal nu! list! paste! foldcolumn=0<CR>
#sum
