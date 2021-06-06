## eureka-demo

通过spring-cloud实现简易的消费生产者模型

#### 基本功能

通过两个eureka-server构建的集群 实现consumer远程调用provider的方法的功能

#### 基本原理

通过http协议进行通信

生产者通过将自己的服务暴露给注册中心，生产者拉取注册中心的服务列表再通过负载均衡算法调取指定的ip进行访问

#### 基本使用

分别启动四个子模块 通过consumer访问http://localhost:9090/order/1 调取到生产者数据



