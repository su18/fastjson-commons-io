# fastjson commons-io AutoCloseable

为了方便测试把代码放上来了

分析文章：[https://su18.org/post/fastjson-1.2.68/](https://su18.org/post/fastjson-1.2.68/)

注意：由于 fastjson 获取 WriterOutputStream 的构造方法时并不唯一，所以这个 payload 并不是每次都能触发，需要等随机到带有指定参数的构造方法才能触发，测试的小伙伴多测几次就可以写入了。如果你有解决这个问题的办法请联系我。