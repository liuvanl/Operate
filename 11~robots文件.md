## robots.txt
+ Robots协议（也称为爬虫协议、爬虫规则、机器人协议等）也就是robots.txt，网站通过robots协议告诉搜索引擎哪些页面可以抓取，哪些页面不希望被抓取。
+ Robots协议是网站国际互联网界通行的道德规范，其目的是保护网站数据和敏感信息、确保用户个人信息和隐私不被侵犯。
+ __因其不是命令，故需要搜索引擎自觉遵守。__
## robots.txt放置位置
+ __robots.txt文件应该放置在网站跟目录下。__
> 例如，当spider访问一个网站（比如<span>http://www.taobao.com</span>）时，首先会检查该网站中是否存在<span>http://www.taobao.com/robots.txt</span>这个文件，如果Spider找到这个文件，它就会根据这个文件的内容，来确定它访问权限的范围。
## robots.txt文件的写法
> __User-agent:__ * 这里的 *代表所有的搜索引擎种类，*是一个通配符。<br>
> __Disallow:__ / admin / 这里定义是禁止爬寻admin目录下面的目录。<br>
> __Disallow:__ / * ? *禁止访问网站中所有包含问号（？）的网址<br>
> __Disallow:__ /.jpg$ 禁止抓取网页所有的.jpg格式的图片<br>
> __Disallow:__ / ab / abc.html禁止爬取ab文件夹下面的abc.html文件<br>
> __Allow:__ / cgi-bin / 这里定义是允许爬寻cgi-bin目录下面的目录<br>
> __Allow:__ .html$ 仅允许访问以".html"为后缀的URL<br>
> __Allow:__ .gif$ 允许抓取网页和gif格式图片<br>
> __Sitemap:__ 网站地图告诉爬虫这个页面是网站地图。
