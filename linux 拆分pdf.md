#o
参考#a
#i
google linux pdf split command line
#a
```
pdfseparate -l 2 test.pdf %d.pdf
ls *.pdf
```
结果显示
1.pdf  2.pdf
```
pdfunite 1.pdf 2.pdf end.pdf
ls end.pdf
```
结果显示
end.pdf
#sum
1. https://www.pdflabs.com/docs/install-pdftk-on-redhat-or-centos/
2. https://jorge.fbarr.net/2015/02/20/split-and-merge-pdfs-part-2/
