# Socket_spider


这个版本会将页面都下载下来放到/downloaded文件夹里面。

**warning:**

  * 这个版本只支持macos
  * 这只是一个学习的爬虫系统
  * 这个项目爬取的网站已经被换了，所以不能用了，但是只要去改改逻辑就能用到别的网站样式去（bupt的计算机应用编程实验课作业）
  

**Pre-work**

  * 安装 libevent 先
  

使用方法：
 
  * cmake .
  * make
  * ./spider
  
Q&A:

1. 我的程序结束是利用主线程的睡眠时间，现在设置了1000秒，并不是靠判断队列为空发送信号量的方式，懒了，不想去实现了。
2. 一篇很详细的文档会在doc/里面
3. 我的libevent使用的很碰巧（这么说是不是显得很不专业，但确实如此），有心人可以帮我看看改改。
