## 个人信息

田震 | 156-1172-1937 | i@youth2009.org | 曲阜师范大学 软件工程（本科）

[博客](https://youth2009.org/) | [2016年之前博客](https://old.youth2009.org/blog/archives/) | [GitHub](https://github.com/dawncold) | [Linkedin](https://linkedin.com/in/dctz)

入职时间：2019-01-01

## 职业培训

Udacity深度学习（第一学期）毕业：统计、线性代数基础，numpy、pandas、机器学习框架基础

## 工作经验
### 北京诚创济世信息技术有限公司 (2013年7月至今，5年5个月)
Lijiababy.com.cn的开发者、网站可用性工程师、有时作为运维和DBA

* Lijiababy.com.cn网站前后台PC版：Python、Tornado、PostgreSQL、Redis等

* 触屏版网站：主要使用React、Webpack、ES6等

* 触屏版集成微信公众号：触屏版网站使用微信js sdk集成各种能力，微信版上线后基本吞没了八成以上流量

* 触屏版集成app：触屏版网站集成进一个类似浏览器外壳的app，用类似微信jssdk的方式使用其封装的硬件能力。app上线后销售上升快速，基本和微信版持平

* Restful接口：app、小程序、线下门店使用的接口

* Linux Container：在物理机上隔离不同子系统，由2013年开始使用LXC，去年迁移到了LXD

* 自动化测试：python unittest，selenium+chrome进行web主业务流程测试

* 自动化部署：从裸机开始自动加固主机安全配置、安装应用依赖和软件，启动服务。涉及Fabric, LXD

* PostgreSQL: 未使用ORM，对数据库操作有一定封装，查询全是完整SQL，对数据库操作熟悉

* PostgreSQL HA: 据库服务器RAID卡坏掉，导致部分数据丢失，是业务中断最长的一次。数据库上次备份时间距离损坏时间间隔较大，无法使用，只能尽量恢复数据。这次惨痛经历过后立刻开始了数据库实时备份的建设，基于Barman、PostgreSQL的PITR技术，现基本可以实现极小的数据丢失概率，而且测试跨数据中心备份效果非常好

* 日志、问题追踪平台（ELK）：应用程序日志归集、查找、分析，在运维时查看最近几小时错误日志，分析4xx，5xx请求比例、处理时间等

* 业务领域命名、统一代码风格，积极重构

* 异步任务队列升级、迁移：异步任务在每次执行前加载所有需要依赖的组件后执行完之后退出，大部分时间都消耗在加载依赖上，于是改造成加载依赖后不退出，直到处理足够多任务后再退出，防止有内存溢出。后因原项目不再继续维护，转而使用TaskTiger作为目前的任务队列，目前是该项目的代码贡献者

* 与SAP系统集成订单、商品、库存、价格等数据

* 使用OCR服务解析商品图片，找到可能违反广告法的词语，规避风险

* 多渠道推广追踪：类似统计网站的utm追踪方式，可统计不同渠道转化效果

* 礼金卡支付建设：线上可使用线下门店售出的预付卡，与线下门店系统集成

* 供应商直送建设：由供应商发货并提供售后，线上平台进入多商户模式，对订单、商品模型修改以适应发展

* 重构商品模型，与ERP商品隔离，使得销售前端可以根据需要定制商品，增加灵活性

* 优惠券系统建设：多渠道投放、多种类型优惠券，促销类型更加丰富

* 推介系统建设：全部员工可推广会员注册，根据后续会员消费可拿提成

* 会员抽奖建设：消会员积分利器

* 本月特权建设：根据会员以往消费多少决定本月优惠商品，提高会员购物频次、客单价

* 与线下门店系统打通优惠券，使得线上线下导流更便捷

* 对接支付宝、微信退款，极大缩短售后退款时间

* 打通天猫、京东店铺商品、订单、库存、价格与线上平台

* 打通微盟微商城订单与线上平台

* 电子发票建设：线上线下购物自助开票，退换货自动冲红并重开

### 开源项目贡献

|项目名称|角色|备注|Pull request/issue id|
|-------|---|---|---------------|
|[Veil](https://github.com/honovation/veil)|Member|Python web框架|-|
|[新广告法敏感词](https://github.com/honovation/new-ad-law-words)|Member|新广告法敏感词库，由其他部门员工整理后发布|-|
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

### 个人项目

|名称|技术|备注|
|---|---|----|
|[raspberry_aqi](https://github.com/dawncold/raspberry_aqi)|Python, RaspberryPI, PMS7003, InfluxDB, Chronograf|家庭空气质量检测、展示（web）|
|[rasp_monitor_lcd](https://github.com/dawncold/rasp_monitor_lcd)|RaspberryPI, PMS7003, LCD|家庭空气质量展示（LCD）|
|[raspsound](https://github.com/dawncold/raspsound)|requests, tornado, rq, nginx, wechat |微信公众号发送语音，通过树莓派连接音箱播放|
|[expenditure-application](https://github.com/dawncold/expenditure-application)|Postgresql,tornado,tasktiger,mailgun|家用资金申请、审批|
|[Scroll-Reverser](https://github.com/dawncold/Scroll-Reverser)|Objective-c|禁止MacOS横向滚动|
|[家用NAS选购指南](https://youth2009.org/post/build-my-own-nas-hardware/)|Hardware, FreeNAS|-|
|[飞线修复M950鼠标](https://youth2009.org/post/fix-m950-with-wire-jumper/)|Hardware|-|
|[修改BIOS关闭Intel ME](https://youth2009.org/post/neutralize-intel-me-on-thinkpad-x220/)|Raspberry pi, GPIO, BIOS|-|
|[HG8347R光猫改桥接](https://youth2009.org/post/unlock-hg8347r/)|-|-|
|[优酷路由宝刷OpenWRT](https://youth2009.org/post/flash-lede-or-openwrt-on-chinaunicom-youku-route/)|OpenWRT|-|
|光纤冷接|Hardware|-|
|3节点SBC集群|Switch,SBC cluster,k8s|-|