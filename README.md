Python所写，豆瓣读书的爬虫，方便大家搜罗各种美美书 

实现功能：

1 可以爬下豆瓣读书标签下的所有图书 

2 按评分排名依次存储

3 存储到Excel中，可方便大家筛选搜罗，比如筛选评价人数>1000的高分书籍；可依据不同的主题存储到Excel不同的Sheet 

4 采用User Agent伪装为浏览器进行爬取，并加入随机延时来更好的模仿浏览器行为，避免爬虫被封（更新于 2015-5-20）

试着小小运行了下，爬了七八万本书，结果在book_list.xlsx中，截图如下：

![Aaron Swartz](https://github.com/lanbing510/DouBanSpider/raw/master/screenshots/douban.jpg)


代码刚写一小时，更多功能有待增加


声明：受@plough同学启发，再其代码基础上进行的创作，感谢@plough




