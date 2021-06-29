dubbo-registry注册中心模块：基于注册中心下发地址的集群方式，以及对各注册中心的抽象。

- dubbo-registry-api，抽象注册中心的注册与发现接口。
- 其他模块，实现dubbo-registry-api，提供对应的注册中心实现。
- 另外，dubbo-registry-default对应Simple注册中心。
