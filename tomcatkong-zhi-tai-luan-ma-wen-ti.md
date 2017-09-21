# tomcat控制台乱码问题

今天在调式程序的时个忽然发现的问题如下面所示

给接口发请求

```
$ curl -d "name=姜磊" -X POST  http://localhost:8089/data-support/test/get04
```

已经确定中文没有乱码，但是在tomcat的输出控制台确乱码了

![](/assets/1505980274036.png)

花了好久才找出角决的方法
![](/assets/1505980556047.png)

这样tomcat的控制台就不会乱码了

