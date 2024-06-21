# offline-dw (e-commerce)

- 前置：

  linux、shell、服务器

  hadoop、flume、kafka

  hive、sql

## 背景介绍

### 基本概念

- 项目课程和技术课程

  技术课程：繁多分散、浅层

  项目课程：少量集中、深层





- 大数据全流程

  用户行为日志采集、业务数据采集

  数仓建模、分层构造、全流程调度

  可视化大屏

- 项目规划

  采集项目：数据的采集、传输 (flume、kafka、datax、maxwell)

  数仓项目：数据的存储、计算 (mysql、hdfs、spark、flink、mr、hive)

- 数据库和数据仓库

  数据库 *Database*：存 - 核心数据的存储 (行式存储、索引、不能存储海量数据)

  数据仓库 *Data Warehouse*：卖 - 数据的存储和计算 (列式存储、能存储海量数据)

- 架构模式

  spark on hive：spark解析sql

  hive on spark：hive解释sql v

- 统计分析步骤：

  数据源、加工数据、统计数据、分析数据



- Q：数仓有自己的数据源？

  业务数据库行式存储、数仓列式存储、数据不能直接对接

  业务数据库不是海量数据、数仓要求海量数据、数据不能直接对接





- 数据的分类

  非结构化数据

  结构化数据：表、sql





### 架构设计















## 环境搭建

- 集群规划

  hadoop101

  hadoop102

  hadoop103

  



### 本地虚拟化 VMware

- 基于基础镜像文件

- hadoop

  ```bash
  
  ```

- ZooKeeper

  ```bash
  
  ```

- Flume

  ```bash
  
  ```

- Kafka

  ```bash
  
  ```

  









### 本地虚拟化 docker













### 云服务器

- 三种付费方式

  

















## 采集项目

- 数据格式

  页面浏览日志

  APP启动体制

- 技术选型

  

### Flume 方案









### Maxwell 方案





### DataX 方案



















## 数仓项目

### 数仓建模

- 分层

  ODS层

  DIM层

  DWD层

  ADS层

  DWS层









### ODS层











### DIM层







### DWD层







### ADS层







### DWS层















## 课程进度

- 第一阶段：总览
- 基本概念：
  - 项目课程技术课程、采集和数仓、数据库和数据仓库、数据流转过程、统计分析步骤、架构设计(数据源 采集 数仓)、 ✔
  - 数据分类、技术选型、数据同步方式 
- 环境搭建：
  - 本地虚拟化和云服务器、数据格式
  - 集群前置环境、Hadoop、Zookeeper、Flume、Kafka、MySQL (基本试用)
  - Maxwell、DataX





- 第二阶段：采集

- 数据建模、业务数据

- Maxwell

  



- 第三阶段：数仓

- 介绍：

- 

  



































































