# gohtran
使用golang 重复造了一个htran的轮子

因为go语言编译后的程序太大,只好把内网与公网执行段分开.

使用方式,首先在公网VPS上启动listener

listener  3389  33333     #第一个端口是客户端上线监听端口  第二个socks5服务监听端口

然后在肉鸡上执行
client ip:3389            #vps的ip和vps上监听的端口            
