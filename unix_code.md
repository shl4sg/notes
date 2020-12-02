#### TCP网络通信API

##### socket

创建socket套接字文件，可选ip协议版本和tcp/udp。

##### connect

客户端向指定服务器地址发起连接。

##### bind

绑定套接字到指定端口。

##### listen

创建监听队列，监听指定socket上的连接请求。

##### accept

接受一个指定地址的连接

##### close

关闭socket文件，当发的引用计数为0，即中断连接

#### UDP网络通信API

##### socket

##### sendto

##### recvfrom

#### epoll原理及实现

#### 边缘触发和水平触发