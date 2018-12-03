## 个人信息

田震 | 186-0028-3016 | i@youth2009.org | 曲阜师范大学 软件工程（本科）

[博客](https://youth2009.org/) | [2016年之前博客](https://old.youth2009.org/blog/archives/) | [GitHub](https://github.com/dawncold) | [Linkedin](https://linkedin.com/in/dctz)

入职时间：2019-01-01

## 工作经验
### 北京诚创济世信息技术有限公司 (2012年9月至今，6年3个月)
Lijiababy.com.cn的开发者、网站可用性工程师、有时作为运维和DBA

* Lijiababy.com.cn商城前后台PC以及触屏版

  技术：React, React-router, Webpack, Python2, Tornado, PostgreSQL, Redis, jQuery, Gulp, ELK stack

  业务：分析报表、会员、商品、订单、促销、优惠券、财务、电子发票、ERP（SAP）、仓库、物流、通知、售后、退款、京东、天猫、微信、OA、门店线上线下打通

* PostgreSQL PITR (Barman)

  曾经遇到物理机RAID卡故障部分数据丢失，恢复后基于Barman搭建PostgreSQL PITR，将数据丢失控制在业务能接受范围内。

* Linux Container (LXC, LXD)

  系统不同组件（web、async queue、db）基于Linux容器技术部署在物理服务器上，以获取最大性能和良好的容器间隔离。由LXC迁移到LXD让部署过程更加健壮。

* 解决性能问题

  最初异步任务在每次执行前加载所有需要依赖的组件后执行完任务退出，大部分时间都消耗在加载依赖上，于是改造成加载依赖后不退出，直到处理足够多任务后再退出，防止有内存溢出。

* Elasticsearch, Logstash, Kibana

  应用程序日志归集、查找、分析，在运维时查看最近几小时错误日志，分析4xx，5xx请求比例、处理时间等

* 业务领域命名、统一代码风格

* 积极重构、完善测试，理顺模块间的依赖关系，解耦，复杂模块根据业务拆分重构降低复杂度

### 职业培训

Udacity深度学习（第一学期）毕业

统计、线性代数基础，numpy、pandas、机器学习框架基础

### 开源项目贡献
* [Veil](https://github.com/honovation/veil)：Python web框架，维护者之一，公司项目在使用，提交bug、fix、feature
* [Tornado](https://github.com/tornadoweb/tornado)：Python web框架，公司项目在使用，提交bug、fix
* [BaRMan](https://github.com/2ndquadrant-it/barman)：PostgreSQL数据库备份、恢复工具，公司项目在使用，提交bug、fix、feature
* [TaskTiger](https://github.com/closeio/tasktiger)：Python async queue，公司项目在使用，提交bug、fix、feature
* [Pyres](https://github.com/binarydud/pyres)：Python async queue，公司原async queue，提交bug、fix、feature，后来作者不再维护，转为使用TaskTiger
