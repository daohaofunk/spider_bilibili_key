# b站关键字爬取
## 一个新人的练手项目，仅供参考！！
### 所用到的库
    1.re 用于正则表达规范网址
    2.random 用于随机选择UA和IP代理
    3.pymongo MONGODB数据库
    4.requests模块 用于主要的请求发送
    5.lxml 利用etree进行xpath分析
### 为什么用request
    这是本人自学爬虫过程的一个练手项目，只是用到很简单request，不涉及ajax和json包，之前也用过selenium和scrapy。目前觉得scrapy需要配置的过多，对于中间件也没学明白。selenium爬取速度感觉有点慢，对于这种小项目觉得request是最适合的
### 未来的改进方向
    1.分布式爬取，
    2.优化代码结构
