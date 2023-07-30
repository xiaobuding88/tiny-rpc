# tiny-rpc
rocket 是基于 C++11 开发的一款多线程的异步 RPC 框架，它旨在高效、简洁的同时，又保持至极高的性能。
rocket 同样是基于主从 Reactor 架构，底层采用 epoll 实现 IO 多路复用。应用层则基于 protobuf 自定义 rpc 通信协议，同时也将支持简单的 HTTP 协议。

整个项目按以下大纲进行：

日志及配置类开发
Reactor 核心模块
Tcp 模块封装
序列化、编解码模块
Rpc 模块封装
脚手架搭建
简单性能测试
