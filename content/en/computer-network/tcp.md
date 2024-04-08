---
title: TCP关闭连接
date: '2024-04-08'
type: book
weight: 20
---

问题：如果客户端先关闭套接字，那服务器还是可以单方面发送数据的对吧？但是我在编程的时候，如果clientsocket调用了close（），然后再用recv（）接收数据的话，会出现一个error。这样, clientsocket 关闭之后，client怎么接收数据呢？见下图：![Image alt](../images/tcp.png)

[查阅答疑文档](../files/qa-tcp.pdf)


