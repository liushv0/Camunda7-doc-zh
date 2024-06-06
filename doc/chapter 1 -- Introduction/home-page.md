[原文链接](https://docs.camunda.org/manual/7.17/introduction/)


## Camunda简介
欢迎查看Camunda Platform手册! Camunda是一个基于java语言的开发框架, 支持包括面向工作流的BPMN规范, 面向案例管理的CMMN规范, 以及面向商业决策管理的DMN规范. 详见[实现标准](./Implemented-Standards.md)

本文档主要描述了Camunda Platform支持的功能.

下面的图片展示了Camunda中最主要的组件, 以及一些典型的用户角色.

![Camunda架构总览](./image/architecture-overview.png)

## 流程引擎 & 基础设施

* 流程引擎(Process Engine)是一个Java库, 用于执行基于BPMN 2.0定义的流程, 或基于CMMN 1.1定义的案例, 或基于DMN 1.3定义的决策. 它是一个轻量的内核, 同时依赖关系型数据库做数据持久化, ORM框架使用的是MyBatis.
* Spring框架集成
* CDI/Java EE集成
* 运行时容器集成(与应用服务器基础设施的集成)

