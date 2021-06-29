dubbo-remoting远程通信模块：提供通用的客户端和服务端的通讯功能


- dubbo-remoting-zookeeper，相当于Zookeeper Client和Zookeeper Server通信
- dubbo-remoting-api，定义了Dubbo Client和Dubbo Server的接口
- dubbo-remoting-grizzly，基于Grizzly实现
- dubbo-remoting-http，基于Jetty和Tomcat实现
- dubbo-remoting-mina，基于Mina实现
- dubbo-remoting-netty，基于Netty3实现
- dubbo-remoting-netty4，基于Netty4实现
- dubbo-remoting-p2p，P2P服务器，注册中心dubbo-registry-multicast使用该项目

我们这里只看了
- dubbo-remoting-api
- dubbo-remoting-netty4
- dubbo-remoting-zookeeper
