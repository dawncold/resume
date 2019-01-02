## 个人信息

田震 | 156-1172-1937 | dawncold (微信) | i@youth2009.org | 曲阜师范大学 软件工程（本科）

[博客](https://youth2009.org/) | [2016年之前博客](https://old.youth2009.org/blog/archives/) | [GitHub](https://github.com/dawncold) | [Linkedin](https://linkedin.com/in/dctz)

入职时间：2019-01-01


## 项目经验

### Lijiababy新零售平台建设
Lijiababy作为母婴产品零售企业，在线下具有丰富的门店资源，定位中高端会员，致力于提供更高品质的母婴产品和服务。新零售平台主要在以下方面为原业务模式进行优化：
* 减少会员结账等待时间，减少配送时间。开发快结账功能，会员可自助结账，缓解周末门店结账压力；由统一仓库+第三方物流配送转变为根据收货地址就近门店出库+闪送等方式尽量减少配送时间（未上线）。
* 减少中间环节，为会员提供品质更高、价格更低的商品。开发供应商直送功能，选择业内优秀产品供应商，通过供应商直接配送给消费者，减少中间环节降低成本。
* 与天猫、京东、微盟、Amazon等电商平台对接，年中、节日大促一直保持较高增长。
* 给会员统一的体验，打通线上线下功能，使会员没有隔离感。通过与门店POS系统集成，优惠券线上线下都可使用；线下购买的预付卡可在线上购物（未上线）；为促进店员推广注册，开发店员线上业绩功能；售后可退至门店等。
* 突破线下门店面积限制，为大体积商品找到去处。通过在门店中放置可触摸式一体机，将占地面积较大的车床椅等品类商品展示给消费者，消费者可在线浏览、下单。

### PostgreSQL数据库备份恢复
存储设备故障导致文件损坏，原先备份策略为每天备份，对于生产环境无法使用，服务恢复后开始着手其他备份方案。目前使用社区最为推荐的Barman完成数据库备份任务，PITR特性使得可以恢复数据到过去一周任意一个时间点；Streaming replication特性使得跨数据中心只读节点与主节点达到秒级同步。

### 任务队列升级
Pyres在执行完每个任务后进程退出，某些任务量非常多，执行完退出使得每次执行任务都要重复加载依赖，浪费时间，任务吞吐量上不去。修改执行策略为加载完任务依赖后子进程执行任务然后退出，后续任务都启动子进程执行，使得之前加载的依赖可以与子进程共享，任务处理速度显著提升。因Pyres项目作者不再维护，该feature无法合并，放弃Pyres改用TaskTiger。

### 运维平台建设
运维人员需要知道应用程序是否异常、服务响应时间是否有波动等。开发人员根据需要在业务关键节点输出结构化的日志和领域数据，推送至Logstash加工处理，存储在Elasticsearch。运维人员从Kibana中查询、设置运维监控指标。

## 工作经验
### 北京诚创济世信息技术有限公司 (2013年7月至今，5年5个月)

DevOps at Lijiababy.com.cn

* Lijiababy.com.cn网站前后台PC版：Python、Tornado、PostgreSQL、Redis等

* 触屏版网站：主要使用React、Webpack、ES6等

* 自动化测试：python unittest，selenium+chrome进行web主业务流程测试

* 集成测试：静态依赖检查、循环依赖检查、封装性检查、代码长度、日志格式、html内容、单元测试、文档测试

* 自动化部署：从裸机开始自动加固主机安全配置、安装应用依赖和软件，启动服务。涉及Fabric, LXD

* 触屏版嵌入微信公众号：触屏版网站使用微信js sdk集成各种能力，微信版上线后基本吞没了八成以上流量

* 触屏版嵌入app：触屏版网站集成进一个类似浏览器外壳的app，用类似微信jssdk的方式使用其封装的硬件能力。app上线后销售上升快速，基本和微信版持平

* Linux Container：在物理机上隔离不同子系统，从2013年开始使用LXC，去年迁移到了LXD

* PostgreSQL: 未使用ORM，对数据库操作有一定封装，查询全是完整SQL，对数据库操作熟悉

* Restful接口：app、小程序、线下门店使用的接口

* 图片中敏感词寻找：使用OCR服务解析商品图片，找到可能违反广告法的词语，规避法律风险

* 多渠道推广追踪：类似统计网站的utm追踪方式，可统计不同渠道转化效果

* 优惠券系统：多渠道投放、多种类型优惠券，促销类型更加丰富

* 会员抽奖：消会员积分利器

* 本月特权：根据会员以往消费多少决定本月优惠商品，提高会员购物频次、客单价

* 对接支付宝、微信退款，极大缩短售后退款时间

* 对接SAP系统集成订单、商品、库存、价格等

* 电子发票：线上线下购物自助开票，退换货自动冲红并重开

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
|[家用NAS选购指南](https://youth2009.org/post/build-my-own-nas-hardware/)|Hardware, FreeNAS|全服务器级硬件搭建|
|[飞线修复M950鼠标](https://youth2009.org/post/fix-m950-with-wire-jumper/)|Hardware|稳定运行一年以上|
|[修改BIOS关闭Intel ME](https://youth2009.org/post/neutralize-intel-me-on-thinkpad-x220/)|Raspberry pi, GPIO, BIOS|胆战心惊编译BIOS|
|[优酷路由宝刷OpenWRT](https://youth2009.org/post/flash-lede-or-openwrt-on-chinaunicom-youku-route/)|OpenWRT|无线驱动不稳定需编译内核|

## 职业充电

Udacity深度学习（第一学期）毕业：统计、线性代数基础、numpy、pandas、机器学习框架基础