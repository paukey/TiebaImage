## Python爬虫小项目

**Python 版本 ： 3.5 **

**功能描述:**

自动获取贴吧某个帖子中的所有**回复图片**（签名档以及其他网页中的图片不会获取到）

**参数说明:**

- url : 要爬取的帖子地址
- header: 浏览器头部信息，简单的反爬虫策略
- path: 本地保存路径
  ​

**使用:**

实例化一个对象，调用**down_load()**方法即可，添加了简单的异常处理，针对url无效、帖子中没有图片等情况。











