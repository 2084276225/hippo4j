---
sidebar_position: 1
---

# 简介


Hippo-4J 通过对 JDK 线程池增强，以及扩展三方框架底层线程池等功能，为业务系统提高线上运行保障能力。

- 全局管控：管理应用线程池实例；
- 动态变更：应用运行时动态变更线程池参数，包括不限于：核心、最大线程数、阻塞队列容量、拒绝策略等；
- 通知报警：内置四种报警通知策略，线程池活跃度、容量水位、拒绝策略以及任务执行时间超长；
- 运行监控：实时查看线程池运行时数据，最近半小时线程池运行数据图表展示；
- 功能扩展：支持线程池任务传递上下文；项目关闭时，支持等待线程池在指定时间内完成任务；
- 容器管理：Tomcat、Jetty、Undertow 容器线程池运行时查看和线程数变更；
- 中间件适配：Apache RocketMQ、Dubbo、RabbitMQ 消费线程池运行时数据查看和线程数变更；
- 多种模式：内置两种使用模式：[依赖配置中心](https://hippo4j.cn/docs/getting-started/hippo4j-core-start) 和 [无中间件依赖](https://hippo4j.cn/docs/getting-started/hippo4j-server-start)。

## 快速开始

对于本地演示目的，请参阅 [Quick start](https://hippo4j.cn/docs/getting-started/hippo4j-server-start)

演示环境：
- [http://console.hippo4j.cn/index.html](http://console.hippo4j.cn/index.html)
- 用户/密码：hippo4j/hippo4j

## 联系我

图片加载不出来，访问 [国内站点](https://hippo4j.cn/docs/other/group)

![](https://user-images.githubusercontent.com/77398366/169202380-6c068acd-700a-41fa-8823-e01c92bb5e88.png)

## 开发者

感谢所有为 Hippo-4J 做出贡献的开发者！

<a href="https://github.com/longtai-cn/hippo4j/graphs/contributors"><img src="https://opencollective.com/hippo4j/contributors.svg?width=890" /></a>

## 我们的荣誉

Hippo-4J 获得了一些宝贵的荣誉，这属于每一位对 Hippo-4J 做出过贡献的成员，谢谢各位的付出。

![](https://user-images.githubusercontent.com/77398366/170607238-7308c9be-1d63-46a6-852c-eef2e4cf7405.JPG)

## Stars 趋势

![](https://starchart.cc/longtai-cn/hippo4j.svg)


## 友情链接

- [JavaGuide](https://github.com/Snailclimb/JavaGuide)：「Java学习+面试指南」一份涵盖大部分 Java 程序员所需要掌握的核心知识。准备 Java 面试，首选 JavaGuide！
- [Guide-Rpc-Framework](https://github.com/Snailclimb/guide-rpc-framework)：A custom RPC framework implemented by Netty+Kyro+Zookeeper.（一款基于 Netty+Kyro+Zookeeper 实现的自定义 RPC 框架-附详细实现过程和相关教程。）
- [toBeBetterJavaer](https://github.com/itwanger/toBeBetterJavaer)：Java 程序员进阶之路，据说每一个优秀的 Java 程序员都喜欢她，风趣幽默、通俗易懂。内容包括 Java 基础、Java 并发编程、Java 虚拟机、Java 企业级开发、Java 面试等核心知识点
- [Austin](https://github.com/ZhongFuCheng3y/austin)：消息推送平台📝 推送下发【邮件】【短信】【微信服务号】【微信小程序】等消息类型。所使用的技术栈包括：SpringBoot、SpringDataJPA、MySQL、Docker、docker-compose、Kafka、Redis、Apollo、prometheus、Grafana、GrayLog、Flink、Xxl-job、Echarts等等

## 鸣谢

Hippo4J 项目基于或参考以下项目：[Nacos](https://github.com/alibaba/nacos)、[Eureka](https://github.com/Netflix/Eureka)、[Mzt-Biz-Log](https://github.com/mouzt/mzt-biz-log)、[Equator](https://github.com/dadiyang/equator)。

感谢 JetBrains 提供的免费开源 License
