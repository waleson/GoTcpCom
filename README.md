# GoTcpCom
一个网络与串口设备通信的小工具，使用golang编写

开发过程,初始思路：
1.使用一个开源的COM0COM虚拟串口对。
http://sourceforge.net/projects/com0com/ 
2.建立一对TCP C/S
3.在客户端做数据转发（一对多，或多对一）。

拟实现以下几种模式：
若采用tcp-client+COM模式：实现中
若采用tcp-server +COM模式：待实现
若采用http-server +COM模式：待实现
若采用http-client +COM模式：待实现
