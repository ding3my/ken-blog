#o
参考#a
#i
google scrapy
[1]https://scrapy.org/
pip install scrapy
pip install scrapy 报错
google Permission denied scrapy
[2]http://stackoverflow.com/questions/14265231/error-when-installing-sc
rapy-with-pip-on-mac
sudo pip install scrapy
sudo pip install scrapy 报错 scrapy Command "/usr/bin/python -u -c
"import setuptools
google scrapy Command "/usr/bin/python -u -c "import setuptools
[3]https://github.com/scrapy/scrapy/issues/2204
sudo yum install gcc libffi-devel python-devel openssl-devel
失败
google fedora 24 install scrapy
[4]https://my.oschina.net/webcreazy/blog/713515
#a
```
sudo dnf install libxslt-devel redhat-rpm-config python-devel
openssl-devel
sudo pip install scrapy
```
```
 name = 'blogspider'
 start_urls = ['https://blog.scrapinghub.com']
 def parse(self, response):
     for title in response.css('h2.entry-title'):
         yield {'title': title.css('a ::text').extract_first()}
     next_page = response.css('div.prev-post > a ::attr(href)').extract_first
     if next_page:
         yield scrapy.Request(response.urljoin(next_page), callback=self.pars
```
结果显示
#sum
- 使用ss代理，proxychains4 sudo pip install scrapy，
1. https://scrapy.org/
2. http://stackoverflow.com/questions/14265231/error-when-installing-scrapy-with-pip-on-mac
3. https://github.com/scrapy/scrapy/issues/2204
4. https://my.oschina.net/webcreazy/blog/713515
5. https://blog.scrapinghub.com/
