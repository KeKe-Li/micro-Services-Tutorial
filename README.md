### micro-Services-Tutorial
微服务最早由Martin Fowler与James Lewis于2014年共同提出，微服务架构风格是一种使用一套小服务来开发单个应用的方式途径，每个服务运行在自己的进程中，并使用轻量级机制通信，通常是HTTP API，这些服务基于业务能力构建，并能够通过自动化部署机制来独立部署，这些服务使用不同的编程语言实现，以及不同数据存储技术，并保持最低限度的集中式管理。然而微服务又需要限流器(Rate Limiter)，数据传输(Trasport 序列化和反序列化),日志(Logging),指标(Metrics)
,断路器(Circuit breaker),请求追踪(Request tracing ),服务发现(Service Discovery),因此就想写一篇关于微服务和微服务组件的总结来记录下自己使用优化的过程．

这是学习的天地，也是技术的聚集地，记录了我一路前行的心得，仅以此文分享给所有在微服务架构之路上学习和使用的人。

* [microServices](https://github.com/KeKe-Li/microServices)
* [promethues和grafana监控](https://github.com/KeKe-Li/micro-Services-Tutorial/blob/master/src/chapter01/01.0.md)
* [promethues命令解析]()
* [redis命令解析]()
* [harbor搭建docker私有仓库]()

#### golang编程

觉得此文章不错，支持我的话可以给我star ，:star:！如果有问题可以加我的微信**Sen0676**,加入我们的交流群一起一起交流goalng技术！

#### License
This is free software distributed under the terms of the MIT license
