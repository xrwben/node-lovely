## node爬虫

#### node数据采集（世纪佳缘）

   >最初想学习一点关于mongoDB的知识，在熟悉一些简单的基本操作后感觉操作的数据有些少，于是乎就想多弄点数据顺便学习一下node爬虫，然后顺便找了个网站，一个不小心就选择了 **<a href="http://www.jiayuan.com">世纪佳缘</a>** (主要是想看美女),所以就有了这个结合node爬虫+mongDB数据库的小案例。
    
#### 使用技术和遇到的坑

- ###### requst+cheerio

- ###### 数据库mongoDB

- ###### 数据库对象模型工具mongoose

- ###### 定时任务node-schedulee

- ###### s6 语法 (async、promise)


    ##### question： 
    
    在爬取数据过程中，其实现实打算爬36kr的新闻列表，但是失败了，然后通过网上查阅资料发现，数据爬取分为两种，一种是服务端的渲染，一种是js异步接口渲染的数据，如果是服务端的渲染则需要cheerio来解析dom，cheerio操作基本操作和jQuery差不多。世纪佳缘则是第二种，所以我就直接通过调试工具查看请求的接口，然后模拟请求数据，这里mongDB数据就不提交啦，想要学习的小伙伴可以去网上自行查阅资料。

