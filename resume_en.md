## Personal Information

TianZhen | 186-0028-3016 | i@youth2009.org | QuFuNormalUniversity Sofeware Engineering

[Blog](https://youth2009.org/) | [Blog before 2016](https://old.youth2009.org/blog/archives/) | [GitHub](https://github.com/dawncold) | [Linkedin](https://linkedin.com/in/dctz)

Earliest available entry time: 2019-01-01

## Experience
### Honovation (2012.09-Present，6+years)
Developer, SRE, Ops, DBA of Lijiababy.com.cn

* Lijiababy.com.cn Front-end, Back-end and mobile website

  Tech Keywords: React, React-router, Webpack, Python2, Tornado, PostgreSQL, Redis, jQuery, Gulp, ELK stack

  Business Keywords: Reporting, Member, Product, Trade, Promotion, Coupon, Finance, eInvoice, ERP(SAP), Warehouse, Logistics, Notification, After service, Refund, JD, Tmall, WeChat, OA, O2O

* PostgreSQL PITR (Barman)
  
  After a metal host RAID card fatal issue, I build PostgreSQL PITR solution by Barman, making database down-time under endurable time range.

* Linux Container (LXC, LXD)
  
  Every systems (web, async queue, db) are based Linux Container, deployed on metal host, to gain best performance and isolation between every containers. Changed from LXC to LXD lets deploy process more robost.

* Fix performance issues
  
  A majority of process time of asynchronous task is load time, after executed, the process exits. I changed async queue logic, after executed the process do not exit, it just keeps alive unless the count of execution exceeds a threshold as preventing memory leak.

* Elasticsearch, Logstash, Kibana
  
  Use Logstash collects application logs, stores to Elasticsearch and then query on Kibana, also analyze recently request status code or process time.
  
* Others but very important
  
  Business domain naming, unify coding style, refactor frequently, add tests, make dependency between modules sence, decouple, etc.

### Training

* Graduated from Udacity Machine Learning (first term)
  
  Basics of statistics, linear algebra, numpy, pandas, machine learning libraries

### Contribution
* [Veil](https://github.com/honovation/veil): Python web framework，contributor，used by project, report bug, commit fix and feature
* [Tornado](https://github.com/tornadoweb/tornado)：Python web framework, contributor，used by Veil project，report bug, commit fix
* [BaRMan](https://github.com/2ndquadrant-it/barman)：PostgreSQL backup and recovery tool, used by project, report bug, commit fix and feature
* [TaskTiger](https://github.com/closeio/tasktiger)：Python asynchronous queue, used by project, report bug, commit fix and feature
* [Pyres](https://github.com/binarydud/pyres)：Python asynchronous queue, used before, report bug, commit fix and feature
