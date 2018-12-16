## Personal Information

TianZhen | 156-1172-1937 | i@youth2009.org | QuFuNormalUniversity Sofeware Engineering

[Blog](https://youth2009.org/) | [Blog before 2016](https://old.youth2009.org/blog/archives/) | [GitHub](https://github.com/dawncold) | [Linkedin](https://linkedin.com/in/dctz)

Earliest available entry time: 2019-01-01

## Experience
### Honovation (2013.09-Present，5+years)
Developer, SRE, Ops, DBA of Lijiababy.com.cn

* Lijiababy.com.cn

  Tech Keywords: React, Webpack, Python2, Tornado, Redis

  Business Keywords: Reporting, Member, Product, Trade, Promotion, Coupon, Finance, eInvoice, ERP(SAP), Warehouse, Logistics, Notification, After service, Refund, JD, Tmall, WeChat, OA, O2O

* Restful APIs

* PostgreSQL: SQL skills, backup and recovery (Barman)

* Linux Container: isolate subsystems on metal host

* Fix performance issues

  A majority of process time of asynchronous task is load time, after executed, the process exits. I changed async queue logic, after executed the process do not exit, it just keeps alive unless the count of execution exceeds a threshold as preventing memory leak.

* Elasticsearch, Logstash, Kibana

  Use Logstash collects application logs, stores to Elasticsearch and then query on Kibana, also analyze recently request status code or process time.

* automate deploy: Install dependencies, packages, enforce security levels from bare metal to runnable application

* automate test: python unittest and selenium+chrome for web test

* integrate with SAP

* use OCR service to parse images and find prohibited words

* multip channels tracking: track multip channels like GA, generate every channel report

* Others but very important

  Business domain naming, unify coding style, refactor frequently, add tests, make dependency between modules sence, decouple, etc.

### Training

Graduated from Udacity Deep Learning (first term): Basics of statistics, linear algebra, numpy, pandas, machine learning libraries

### Open Source Contribution
|Project Name|Role|Remark|Pull request/issue id|
|-------|---|---|---------------|
|[Veil](https://github.com/honovation/veil)|Member|Python web framework|-|
|[New ad law words](https://github.com/honovation/new-ad-law-words)|Member|Ad law in my country prohibited word list|-|
|[TaskTiger](https://github.com/closeio/tasktiger)|Contributor|Python task queue|71,72,81,82,88|
|[Tornado](https://github.com/tornadoweb/tornado)|Contributor|Python web framework and asynchronous networking library|2155|
|[pylxd](https://github.com/lxc/pylxd)|Contributor|Python module for LXD|307|
|[BaRMan](https://github.com/2ndquadrant-it/barman)|Issuer|Backup and Recovery Manager for PostgreSQL|174, 184|
|[Pyres](https://github.com/binarydud/pyres)|Issuer|a resque clone in python|137|
|[Resweb]()|Forker|Web interface to pyres jobs|[commits](https://github.com/dawncold/resweb/commits/master)|
|[redis documents]()|-|https://redis.io/topics/streams-intro|1017|
|[supervisor](https://github.com/Supervisor/supervisor)|-|Supervisor process control system for UNIX|444|
|[qiniu python sdk](https://github.com/dawncold/python-sdk)|-|Qiniu Resource (Cloud) Storage SDK for Python|319|
|[Nestable](https://github.com/dbushell/Nestable)|-|Drag & drop hierarchical list with mouse and touch compatibility (jQuery plugin)|113|
|[suds](https://bitbucket.org/jurko/suds/)|Issuer|python web service library|[issue](https://bitbucket.org/jurko/suds/issues/39/missing-last_sent-and-last_received)|

### Personal Projects

|Project Name|Tech|Remark|
|---|---|----|
|[raspberry_aqi](https://github.com/dawncold/raspberry_aqi)|Python, RaspberryPI, PMS7003, InfluxDB, Chronograf|Home Air Quality Index collect and show|
|[rasp_monitor_lcd](https://github.com/dawncold/rasp_monitor_lcd)|RaspberryPI, PMS7003, LCD|Home Air Quality Index collect and display on a LCD with Raspberry PI|
|[raspsound](https://github.com/dawncold/raspsound)|requests, tornado, rq, nginx, wechat |send voice on Wechat, play with Reaspberry PI|
|[expenditure-application](https://github.com/dawncold/expenditure-application)|Postgresql,tornado,tasktiger,mailgun|Homebrew expenditure application|
|[Scroll-Reverser](https://github.com/dawncold/Scroll-Reverser)|Objective-c|prevent horizontal scroll on MacOS|
|[Homebrew NAS hardware guide](https://youth2009.org/post/build-my-own-nas-hardware/)|Hardware, FreeNAS|-|
|[Fix M950 mouse with jumper](https://youth2009.org/post/fix-m950-with-wire-jumper/)|Hardware|-|
|[Neutralize Intel ME on X220](https://youth2009.org/post/neutralize-intel-me-on-thinkpad-x220/)|Raspberry pi, GPIO, BIOS|-|
|[unlock HG8347R](https://youth2009.org/post/unlock-hg8347r/)|-|-|
|[Flash OpenWRT](https://youth2009.org/post/flash-lede-or-openwrt-on-chinaunicom-youku-route/)|OpenWRT|-|
|3 nodes SBC cluster|Switch,SBC cluster,k8s|-|