###   因为自己在跟一些朋友做了个APP，

###  自己负责后端数据的爬取，所以写了这个小东西

###  news_spider.py会爬取整个页面的相关的文章url

###  实际上并不需要这么多，所以就放在那了

### news_spider_two.py 只抓取置顶的，banner旋转的部分。

### 也就是当前热度比较高的文章。目前只抓取虎嗅网，雷锋网，钛媒体三家。

### 共抓取12篇左右，后面就每个三小时查询一次，

### 有新文章就会抓取下来，晚上九点会停止，直至早上八点开始。

### 因为是根据文章模板进行结构化抓取，所以会有不适用的现象。

### 自己根据需要进行修改即可。

### 有关注释，自己写的还行吧，如有不明白的地方，可以联系我。

@UpTime: 2017.11.12

### 此前抓取的只是静态的，所需信息就在网页源代码中。

### 但现在很多公司采用动态的方式，内容由JS来动态获取，动态填充。

### 所有就不能按照以前的思路来。

### 主流的做法是selenium + phantomjs的方式。

### 自己也是这样做的。

### Contact：520@skyne.cn

@UpTime: 2017.11.25

### 采用模块化的方法，结构清晰

### 优化了点东西。效率比以前高。

@UpTime: 2017.12.03

### 增加了将抓取信息自动同步到微博的功能。

### 增加了出现错误发送错误报告到自己邮箱。

### 其他地方也改动了一下，具体想不起来了。

### 总之，比以前又好点。

@UpTime: 2017.12.27

### 优化36kr抓取时获取不到图片的问题

### 增加了Socket来传输抓取的news,发送至指定的主机上。

### 增加了数据库部分，来存储抓取到的news,并将title取唯一。

### 当然了，也可以取url地址来去重。但这样我们也可以获取到抓取到的内容。



