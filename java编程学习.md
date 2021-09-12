# java编程学习

## 高性能编程

### 多线程并发编程

- Java基础
- 线程安全问题
- J.U.C并发包

### 高并发网络编程

- NIO网络编程
- Netty框架源码
- 网络编程项目

### Java系统性能调优

- Java性能
- 性能调优实战

## 中间件

### 消息中间件

- Activemq
- Rabbitmq

	- 消息分发机制
	- 集群和高可用方案：普通集群只同步元数据，能看到消息存放在哪个节点上然后到对应节点取数据，镜像队列可以同步队列上的消息
	- 持久化机制

		- 内存警告：当内存使用超过配置阈值或磁盘剩余空间低于阈值，阻塞客户端连接，并停止接受新消息
		- 持久化：交换机第三个参数，队列第二个参数，消息messageProperties.PRESISTENT_TEXT_PLAIN都可设置持久化

- kafka
- Rocketmq
- 应用场景

### 负载均衡中间件

- Ngnix
- LVS
- 基于云计算平台架构
- 网易实战

### 缓存中间件

- Java内存缓存
- redis缓存
- memcached
- 缓存实战

### 数据库中间件

- 数据库中间件设计
- mycat数据库
- sharding-JDBC数据库

## 容器化技术

### Docker

- docker入门
- docker进阶
- 网易docker实战

### Kubernetes

- K8S前言
- K8S入门
- K8S进阶
- K8S实战
- 安装

### ES

## 分布式技术

### 分布式应用协调

- ZK
- 分布式系统设计理论

### RPC服务治理框架

- RPC技术
- Dubbo框架

### springcloud微服务解决方案

- springboot
- spring netflix
- springcloud生态
- 网易分布式系统
- 就业指导

## 云课堂项目

### 源码结构管理

- maven

### 版本控制

- git

### 研发流程管理

- devops

### springcloud项目开发

- 功能开发

### 线上运维部署

## 网易商业化项目

### 网易商业化项目

