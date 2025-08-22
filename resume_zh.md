## 个人信息

田震 | +86 18600283016 | loooseleaves@gmail.com

工作经验: 12年以上

最快入职时间：2025 年 8 月 25 日

## 核心能力概要
1. 架构治理
* 作为tech lead与国内、印度团队历时2年将客户所有线上服务迁移至业界领先技术栈，现代化的技术栈降低了客户运维（VM license）、研发（工程师）成本，现代的技术栈同时提升了安全性、稳定性，降低了资源使用，紧跟技术趋势，未来继续升级变得更容易，可作为客户公司内其部门参考案例。
* 为客户内部应用团队搭建自研工程平台，应用团队可自助获取各种云上的基础设施，平台提供所有开发、部署、监控的支持，统一了应用团队的开发流程、运维、安全性基线。
* 在某项目中作为tech lead带领团队处理客户报告的线上问题，从问题具体问题出发反馈开发团队或作为技术债管理起来，定期与客户沟通安排固定时间解决技术债中的问题。
* 基于现有API产品管理工具指导应用团队发布API、订阅其他团队API、维护API产品，提升API可复用性，因为采用统一的API产品，减少了沟通、集成成本，提升了业务响应速度。

2. 可观测性构建和落地
* 在迁移线上服务时集成OpenTelemetry，完善了线上服务的全链路追踪，通过集成Grafana Cloud实现监控可视化、metrics收集、告警等功能。
* 搭建自研工程平台时将OpenTelemetry内置，应用团队默认部署的应用就已经接入到了监控平台（HoneyComb）。

3. AI4SE
* 在迁移线上服务时最大的困难之一是不能保证安全迁移，主要原因来自于服务本身无法提供足够多的测试保证迁移前后行为一致，另外对于核心服务，QA团队无法确保完整的回归测试保证，这使得迁移过程充满风险。通过AI技术可以在迁移前完善自动化测试，回归测试甚至可以做到100%覆盖，在这种保证下进行迁移将会更加安全。
* 在对一个超大规模项目进行迁移的过程中，因为无法短期完成，采用了渐进式迁移方法，分析功能迁移顺序显得格外重要，特别是在测试覆盖有限的情况下。AI技术可结合我们目前已有的服务迁移经验快速评估一个项目的迁移成本以及给出迁移路线图。

## 项目经验

### **Thoughtworks** | 资深顾问 | 2019.01- 2025.08（6 年 7 个月）

1. **全球最大工业资产及车辆拍卖平台** | 7 个月
   * **基础设施工程师 (5 个月):** 为客户内部应用团队提供可自助管理的工程平台，团队可在几分钟内自助申请基础设施，部署应用。
     * *技术栈:* 云平台: Azure; 基础设施即代码: Terraform, Crossplane; 调度: Karmada; 安全: HashiCorp Vault, OPA(K8s & Istio), Connaisseur; CI/CD流水线: CircleCI; 服务网络: Istio; 语言: Java (self service API), Go (Crossplane function); 数据库: PostgreSQL
   * **后端工程师 (2 个月):** 开发产品团队依赖的分类（Taxonomy） API。
     * *技术栈:* 语言: Python; 框架: FastAPI; 数据库: DynamoDB; CI/CD流水线: CircleCI; 测试: Pactflow (契约测试); 监控: Honeycomb
2. **某能源企业 (Fortune 50)** | 1 个月
   * **云解决方案顾问:** 为遗留的企业打印机推荐基于云的打印机管理方案
     * *技术栈:* Microsoft Universal Print
3. **某四大会计师事务所** | 5.5 年
   * **领域专家(海外团队合作) (6 个月):** 与印度团队合作完成约 40 个服务从.NET Framework 或.NET Core 6 迁移到.NET Core 8 并容器化部署到AKS上。
     * *技术栈:* 语言: C# (.NET Framework, .NET Core); 云平台: Azure SQL Managed Instance, AKS; CI/CD: Azure DevOps
   * **技术领导 (应用现代化) (1.5 年):** 带领团队成员完成约 40 个服务从.NET Framework迁移到.NET Core 6。
     * *技术栈:*  语言: C# (.NET Framework, .NET Core); 云平台: Azure SQL Managed Instance; CI/CD: Azure DevOps
   * **技术领导 (解决生产环境问题) (1 年):** 管理技术债并解决客户报告的线上问题，通过解决线上问题和技术债提升产品整体质量，确保系统稳定性和客户满意。
   * **全栈工程师 (2.5 年):** 在客户的全球出行管理产品上进行功能开发。涉及Tax, Immigration领域。
     * *技术栈:* 前端框架: AngularJS, React, Aurelia; 后端: C# (.NET Framework), Autofac, NHibernate; 数据库: SQL Server, EventStore, ElasticSearch; 云平台: Azure SQL Managed Instance, VM, KeyVault, ServiceBus

4. **全球某领先车企** | 4 个月   
   * **API平台顾问:** 指导应用团队发布API到平台，从API平台订阅其他团队维护的API。
     * *技术栈:* API管理工具: Apigee; 脚本工具: Python

5.  **短期咨询项目**
    *   **技术培训 (4 天):** 参与某电信设备提供商Python培训项目，准备Python最佳实践，问题答疑，修改作业。
    *   **敏捷咨询 (18 天):** 参与某商业银行敏捷转型咨询项目，讲解 Rest API 含义，成熟度。

### Honovation | 全栈工程师 | 2012.10 - 2018.12（6 年）

**全栈工程师:** 为国内领先的婴童用品公司构建线上商城系统，打通线上所有销售渠道和线下渠道，并与客户的SAP系统、POS系统集成，商城系统覆盖PC、移动端、微信。   

*技术栈:* Python 2.7, PostgreSQL, React, JavaScript, HTML/CSS, LXC Container, SAP API, 微信支付, 微信SDK

## 认证和教育信息

Microsoft认证：Azure开发者助理 | [在线验证](https://learn.microsoft.com/zh-cn/users/zhentian-6703/credentials/b15f12aa38a7c8d0) | 获得时间 2024 年 12 月

曲阜师范大学 | 软件工程学士 | 2009 年 – 2013 年