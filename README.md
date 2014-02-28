## 一个flask gevent实现的websocket监控

###  这是我做过的一个全网实时监控的核心部分代码，大家可以借鉴下 

* 抓取全网的交换机流量
* 调用公司的黑洞防护接口，针对攻击进行封杀或者分流攻击
* 抓到的数据，不仅入库，而且用jqplot实时绘图
* 对于超过阀值的监控类型，会进行高亮显示


```python
    yum -y install redis-server
    yum -y install python-dev
    pip install gevent
    pip install redis

    end
```


作者 [@小芮][1]

[1]: https://xiaorui.cc
