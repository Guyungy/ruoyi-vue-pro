<div align="center">
  <img src="https://img.shields.io/badge/Spring%20Boot-2.7.18-brightgreen.svg" alt="Spring Boot Version">
  <img src="https://img.shields.io/badge/Vue-3.2-blue.svg" alt="Vue Version">
  <img src="https://img.shields.io/github/license/YunaiV/ruoyi-vue-pro" alt="License">
  <img src="https://img.shields.io/github/stars/YunaiV/ruoyi-vue-pro?style=social" alt="GitHub Stars">
  <img src="https://gitee.com/zhijiantianya/ruoyi-vue-pro/badge/star.svg?theme=dark" alt="Gitee Stars">
</div>

<h1 align="center">🌟 芋道 - 企业级快速开发平台</h1>

<p align="center">
  <b>以开发者为中心，打造中国第一流的快速开发平台</b><br/>
  <b>现在、未来都不会有商业版本，所有代码全部开源！</b>
</p>

<p align="center">
  <i>「我喜欢写代码，乐此不疲」</i><br/>
  <i>「我喜欢做开源，以此为乐」</i>
</p>

---

## 📋 目录

- [🚀 快速开始](#-快速开始)
- [🎯 在线演示](#-在线演示)
- [📦 版本说明](#-版本说明)
- [🏗️ 项目架构](#️-项目架构)
- [🌈 核心特性](#-核心特性)
- [🛠️ 技术栈](#️-技术栈)
- [📁 项目结构](#-项目结构)
- [🎨 功能预览](#-功能预览)
- [🤝 如何贡献](#-如何贡献)
- [📄 开源协议](#-开源协议)
- [🎁 项目外包](#-项目外包)

---

## 🚀 快速开始

### 📋 环境要求

- **JDK**: 8+ (推荐 JDK 8/11)
- **MySQL**: 5.7+ / 8.0+
- **Redis**: 5.0+
- **Maven**: 3.6+
- **Node.js**: 16.x+

### ⚡ 快速启动

1. **克隆项目**
   ```bash
   git clone https://gitee.com/zhijiantianya/ruoyi-vue-pro.git
   cd ruoyi-vue-pro
   ```

2. **配置数据库**
   ```bash
   # 创建数据库并导入初始化脚本
   mysql -u root -p < sql/mysql/ruoyi-vue-pro.sql
   ```

3. **启动后端**
   ```bash
   cd yudao-server
   mvn spring-boot:run
   ```

4. **启动前端**
   ```bash
   cd yudao-ui/yudao-ui-admin-vue3
   npm install
   npm run dev
   ```

🎉 访问 `http://localhost:1024` 即可体验系统！

📚 **详细文档**: [启动文档](https://doc.iocoder.cn/quick-start/) | [视频教程](https://doc.iocoder.cn/video/)

---

## 🎯 在线演示

| 前端技术栈 | 演示地址 | 账号密码 |
|---------|---------|---------|
| Vue3 + Element Plus | [🔗 点击访问](http://dashboard-vue3.yudao.iocoder.cn) | admin/admin123 |
| Vue3 + Ant Design Vue | [🔗 点击访问](http://dashboard-vben.yudao.iocoder.cn) | admin/admin123 |
| Vue2 + Element UI | [🔗 点击访问](http://dashboard.yudao.iocoder.cn) | admin/admin123 |

---

## 📦 版本说明

<table>
  <tr>
    <th>版本类型</th>
    <th>JDK 8 + Spring Boot 2.7</th>
    <th>JDK 17/21 + Spring Boot 3.2</th>
  </tr>
  <tr>
    <td><b>完整版</b><br/><small>包含所有功能模块</small></td>
    <td><a href="https://gitee.com/zhijiantianya/ruoyi-vue-pro/tree/master/">master 分支</a></td>
    <td><a href="https://gitee.com/zhijiantianya/ruoyi-vue-pro/tree/master-jdk17/">master-jdk17 分支</a></td>
  </tr>
  <tr>
    <td><b>精简版</b><br/><small>仅核心功能模块</small></td>
    <td><a href="https://gitee.com/yudaocode/yudao-boot-mini/tree/master/">yudao-boot-mini</a></td>
    <td><a href="https://gitee.com/yudaocode/yudao-boot-mini/tree/master-jdk17/">yudao-boot-mini</a></td>
  </tr>
</table>

💡 **迁移指南**: 可参考 [《迁移文档》](https://doc.iocoder.cn/migrate-module/)，5-10 分钟即可按需迁移

---

## 🏗️ 项目架构

![架构图](/.image/common/ruoyi-vue-pro-architecture.png)

### 🎨 技术架构特点

- 🏢 **多模块架构**: Spring Boot 多模块设计，便于扩展维护
- 🗄️ **多数据库支持**: MySQL、Oracle、PostgreSQL、SQL Server、国产达梦等
- 📨 **多消息队列**: Event、Redis、RabbitMQ、Kafka、RocketMQ
- 🔐 **权限认证**: Spring Security + Token + Redis，支持多终端认证
- 🏢 **SaaS多租户**: 透明化多租户底层封装，自定义权限
- 🔄 **工作流引擎**: Flowable，支持动态表单、在线设计
- ⚡ **代码生成**: 一键生成前后端代码、SQL脚本、接口文档
- 💬 **实时通信**: Spring WebSocket，支持集群部署
- 📊 **报表大屏**: 拖拽式报表设计器和大屏设计器

---

## 🌈 核心特性

### 💼 业务功能完整
- ✅ **系统管理**: 用户、角色、菜单、部门、岗位、字典等
- ✅ **基础设施**: 代码生成、系统接口、文件服务、定时任务等  
- ✅ **工作流程**: 流程设计、表单配置、任务处理、会签或签等
- ✅ **支付系统**: 支付宝、微信支付、退款、回调等
- ✅ **会员中心**: 会员管理、等级、积分、签到等
- ✅ **商城系统**: 商品、订单、购物车、营销活动等
- ✅ **CRM系统**: 客户、商机、合同、回款等  
- ✅ **ERP系统**: 采购、销售、库存、财务等
- ✅ **微信生态**: 公众号、小程序、企业微信等
- ✅ **AI大模型**: 对话、绘画、音乐、思维导图等

### 🔧 开发效率极高
- 🚀 **代码生成器**: 支持单表、树表、主子表
- 🚀 **低代码平台**: 拖拽式表单设计
- 🚀 **开发规范**: 阿里巴巴Java开发手册规范
- 🚀 **单元测试**: 113770行Java代码，42462行代码注释
- 🚀 **文档完善**: 详细的开发文档和视频教程

### 🛡️ 企业级特性
- 🔒 **安全可靠**: Spring Security权限控制，数据权限
- 🏢 **多租户**: SaaS模式，租户数据隔离
- 📈 **性能监控**: SkyWalking链路追踪，Spring Boot Admin监控
- 🔄 **分布式**: Redis分布式锁、幂等、限流
- 📱 **多端适配**: 管理后台、移动端、小程序等

---

## 🛠️ 技术栈

### 后端技术

| 技术 | 版本 | 说明 |
|------|------|------|
| Spring Boot | 2.7.18 | 应用开发框架 |
| MyBatis Plus | 3.5.7 | 持久层增强框架 |
| Spring Security | 5.7.11 | 认证授权框架 |
| Flowable | 6.8.0 | 工作流引擎 |
| Redis | 7.0 | 缓存数据库 |
| MySQL | 8.0+ | 关系型数据库 |

### 前端技术

| 技术 | 版本 | 说明 |
|------|------|------|
| Vue | 3.2 | 渐进式框架 |
| Element Plus | - | UI组件库 |
| Ant Design Vue | - | 企业级UI组件库 |
| TypeScript | - | 类型安全 |
| Vite | - | 构建工具 |

📋 [查看完整技术栈详情](#技术栈详情)

---

## 🐼 内置功能

系统内置多种业务功能，可以用于快速搭建你的业务系统：

![功能分层](/.image/common/ruoyi-vue-pro-biz.png)

* **通用模块（必选）**: 系统功能、基础设施
* **通用模块（可选）**: 工作流程、支付系统、数据报表、会员中心  
* **业务系统（按需）**: ERP 系统、CRM 系统、商城系统、微信公众号、AI 大模型

> 💡 **友情提示**: 本项目基于 RuoYi-Vue 修改，**重构优化**后端的代码，**美化**前端的界面
> 
> * 额外新增的功能，我们使用 🚀 标记
> * 重新实现的功能，我们使用 ⭐️ 标记

🎯 所有功能，都通过 **单元测试** 保证高质量

### 🔐 系统功能

| 功能 | 描述 |
|------|------|
| 用户管理 | 用户是系统操作者，该功能主要完成系统用户配置 |
| ⭐️ 在线用户 | 当前系统中活跃用户状态监控，支持手动踢下线 |
| 角色管理 | 角色菜单权限分配、设置角色按机构进行数据范围权限划分 |
| 菜单管理 | 配置系统菜单、操作权限、按钮权限标识等，本地缓存提供性能 |
| 部门管理 | 配置系统组织机构（公司、部门、小组），树结构展现支持数据权限 |
| 岗位管理 | 配置系统用户所属担任职务 |
| 🚀 租户管理 | 配置系统租户，支持 SaaS 场景下的多租户功能 |
| 🚀 租户套餐 | 配置租户套餐，自定每个租户的菜单、操作、按钮的权限 |
| 字典管理 | 对系统中经常使用的一些较为固定的数据进行维护 |
| 🚀 短信管理 | 短信渠道、短息模板、短信日志，对接阿里云、腾讯云等主流短信平台 |
| 🚀 邮件管理 | 邮箱账号、邮件模版、邮件发送日志，支持所有邮件平台 |
| 🚀 站内信 | 系统内的消息通知，提供站内信模版、站内信消息 |
| 🚀 操作日志 | 系统正常操作日志记录和查询，集成 Swagger 生成日志内容 |
| ⭐️ 登录日志 | 系统登录日志记录查询，包含登录异常 |
| 🚀 错误码管理 | 系统所有错误码的管理，可在线修改错误提示，无需重启服务 |
| 通知公告 | 系统通知公告信息发布维护 |
| 🚀 敏感词 | 配置系统敏感词，支持标签分组 |
| 🚀 应用管理 | 管理 SSO 单点登录的应用，支持多种 OAuth2 授权方式 |
| 🚀 地区管理 | 展示省份、城市、区镇等城市信息，支持 IP 对应城市 |

![功能图](/.image/common/system-feature.png)

### 🔄 工作流程

![功能图](/.image/common/bpm-feature.png)

基于 Flowable 构建，支持信创（国产）数据库，满足中国特色流程操作：

| BPMN 设计器 | 钉钉/飞书设计器 |
|-------------|----------------|
| ![](/.image/工作流设计器-bpmn.jpg) | ![](/.image/工作流设计器-simple.jpg) |

> 🏆 **历经头部企业生产验证，工作流引擎须标配仿钉钉/飞书 + BPMN 双设计器！**
>
> 前者支持轻量配置简单流程，后者实现复杂场景深度编排

<details>
<summary>📋 详细功能列表（点击展开）</summary>

| 功能列表 | 功能描述 | 完成状态 |
|----------|----------|----------|
| SIMPLE 设计器 | 仿钉钉/飞书设计器，支持拖拽搭建表单流程，10 分钟快速完成审批流程配置 | ✅ |
| BPMN 设计器 | 基于 BPMN 标准开发，适配复杂业务场景，满足多层级审批及流程自动化需求 | ✅ |
| 会签 | 同一个审批节点设置多个人，需全部同意之后，审批才可到下一审批节点 | ✅ |
| 或签 | 同一个审批节点设置多个人，任意一个人处理后，就能进入下一个节点 | ✅ |
| 依次审批 | 同一个审批节点设置多个人，三人按顺序依次收到待办，需全部同意之后才可到下一节点 | ✅ |
| 抄送 | 将审批结果通知给抄送人，同一个审批默认排重，不重复抄送给同一人 | ✅ |
| 驳回 | 将审批重置发送给某节点，重新审批。可驳回至发起人、上一节点、任意节点 | ✅ |
| 转办 | A 转给其 B 审批，B 审批后，进入下一节点 | ✅ |
| 委派 | A 转给其 B 审批，B 审批后，转给 A，A 继续审批后进入下一节点 | ✅ |
| 加签 | 允许当前审批人根据需要，自行增加当前节点的审批人，支持向前、向后加签 | ✅ |
| 减签 | 在当前审批人操作之前，减少审批人 | ✅ |
| 撤销 | 流程发起人，可以对流程进行撤销处理 | ✅ |
| 终止 | 系统管理员，在任意节点终止流程实例 | ✅ |
| 表单权限 | 支持拖拉拽配置表单，每个审批节点可配置只读、编辑、隐藏权限 | ✅ |
| 超时审批 | 配置超时审批时间，超时后自动触发审批通过、不通过、驳回等操作 | ✅ |
| 自动提醒 | 配置提醒时间，到达时间后自动触发短信、邮箱、站内信等通知提醒 | ✅ |
| 父子流程 | 主流程设置子流程节点，子流程节点会自动触发子流程 | ✅ |
| 条件分支 | 用于在流程中实现决策，即根据条件选择一个分支执行 | ✅ |
| 并行分支 | 允许将流程分成多条分支，不进行条件判断，所有分支都会执行 | ✅ |
| 包容分支 | 允许基于条件选择多条分支执行，但如果没有任何一个分支满足条件，则可以选择默认分支 | ✅ |
| 路由分支 | 根据条件选择一个分支执行，也可以选择默认分支执行 | ✅ |
| 触发节点 | 执行到该节点，触发 HTTP 请求、HTTP 回调、更新数据、删除数据等 | ✅ |
| 延迟节点 | 执行到该节点，审批等待一段时间再执行，支持固定时长、固定日期等 | ✅ |
| 拓展设置 | 流程前置/后置通知，节点（任务）前置、后置通知，流程报表等 | ✅ |

</details>

### 💳 支付系统

| 功能 | 描述 |
|------|------|
| 🚀 应用信息 | 配置商户的应用信息，对接支付宝、微信等多个支付渠道 |
| 🚀 支付订单 | 查看用户发起的支付宝、微信等的【支付】订单 |
| 🚀 退款订单 | 查看用户发起的支付宝、微信等的【退款】订单 |
| 🚀 回调通知 | 查看支付回调业务的【支付】【退款】的通知结果 |
| 🚀 接入示例 | 提供接入支付系统的【支付】【退款】的功能实战 |

### 🏗️ 基础设施

| 功能 | 描述 |
|------|------|
| 🚀 代码生成 | 前后端代码的生成（Java、Vue、SQL、单元测试），支持 CRUD 下载 |
| 🚀 系统接口 | 基于 Swagger 自动生成相关的 RESTful API 接口文档 |
| 🚀 数据库文档 | 基于 Screw 自动生成数据库文档，支持导出 Word、HTML、MD 格式 |
| 表单构建 | 拖动表单元素生成相应的 HTML 代码，支持导出 JSON、Vue 文件 |
| 🚀 配置管理 | 对系统动态配置常用参数，支持 SpringBoot 加载 |
| ⭐️ 定时任务 | 在线（添加、修改、删除)任务调度包含执行结果日志 |
| 🚀 文件服务 | 支持将文件存储到 S3（MinIO、阿里云、腾讯云、七牛云）、本地、FTP、数据库等 |
| 🚀 WebSocket | 提供 WebSocket 接入示例，支持一对一、一对多发送方式 |
| 🚀 API 日志 | 包括 RESTful API 访问日志、异常日志两部分，方便排查 API 相关的问题 |
| MySQL 监控 | 监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈 |
| Redis 监控 | 监控 Redis 数据库的使用情况，使用的 Redis Key 管理 |
| 🚀 消息队列 | 基于 Redis 实现消息队列，Stream 提供集群消费，Pub/Sub 提供广播消费 |
| 🚀 Java 监控 | 基于 Spring Boot Admin 实现 Java 应用的监控 |
| 🚀 链路追踪 | 接入 SkyWalking 组件，实现链路追踪 |
| 🚀 日志中心 | 接入 SkyWalking 组件，实现日志中心 |
| 🚀 服务保障 | 基于 Redis 实现分布式锁、幂等、限流功能，满足高并发场景 |
| 🚀 日志服务 | 轻量级日志中心，查看远程服务器的日志 |
| 🚀 单元测试 | 基于 JUnit + Mockito 实现单元测试，保证功能的正确性、代码的质量等 |

![功能图](/.image/common/infra-feature.png)

### 📊 数据报表

| 功能 | 描述 |
|------|------|
| 🚀 报表设计器 | 支持数据报表、图形报表、打印设计等 |
| 🚀 大屏设计器 | 拖拽生成数据大屏，内置几十种图表组件 |

### 🛒 商城系统

演示地址：[🔗 点击访问](https://doc.iocoder.cn/mall-preview/)

![功能图](/.image/common/mall-feature.png)
![功能图](/.image/common/mall-preview.png)

### 👥 会员中心

| 功能 | 描述 |
|------|------|
| 🚀 会员管理 | 会员是 C 端的消费者，该功能用于会员的搜索与管理 |
| 🚀 会员标签 | 对会员的标签进行创建、查询、修改、删除等操作 |
| 🚀 会员等级 | 对会员的等级、成长值进行管理，可用于订单折扣等会员权益 |
| 🚀 会员分组 | 对会员进行分组，用于用户画像、内容推送等运营手段 |
| 🚀 积分签到 | 回馈给签到、消费等行为的积分，会员可订单抵现、积分兑换等途径消耗 |

### 📦 ERP 系统

演示地址：[🔗 点击访问](https://doc.iocoder.cn/erp-preview/)

![功能图](/.image/common/erp-feature.png)

### 👨‍💼 CRM 系统

演示地址：[🔗 点击访问](https://doc.iocoder.cn/crm-preview/)

![功能图](/.image/common/crm-feature.png)

### 🤖 AI 大模型

演示地址：[🔗 点击访问](https://doc.iocoder.cn/ai-preview/)

![功能图](/.image/common/ai-feature.png)
![功能图](/.image/common/ai-preview.gif)

### 💬 微信公众号

| 功能 | 描述 |
|------|------|
| 🚀 账号管理 | 配置接入的微信公众号，可支持多个公众号 |
| 🚀 数据统计 | 统计公众号的用户增减、累计用户、消息概况、接口分析等数据 |
| 🚀 粉丝管理 | 查看已关注、取关的粉丝列表，可对粉丝进行同步、打标签等操作 |
| 🚀 消息管理 | 查看粉丝发送的消息列表，可主动回复粉丝消息 |
| 🚀 自动回复 | 自动回复粉丝发送的消息，支持关注回复、消息回复、关键字回复 |
| 🚀 标签管理 | 对公众号的标签进行创建、查询、修改、删除等操作 |
| 🚀 菜单管理 | 自定义公众号的菜单，也可以从公众号同步菜单 |
| 🚀 素材管理 | 管理公众号的图片、语音、视频等素材，支持在线播放语音、视频 |
| 🚀 图文草稿箱 | 新增常用的图文素材到草稿箱，可发布到公众号 |
| 🚀 图文发表记录 | 查看已发布成功的图文素材，支持删除操作 |

## 🔗 项目关系

![架构演进](/.image/common/yudao-roadmap.png)

三个项目的功能对比，可见社区共同整理的 [国产开源项目对比](https://www.yuque.com/xiatian-bsgny/lm0ec1/wqf8mn) 表格。

### 📦 后端项目

| 项目 | Star | 简介 |
|------|------|------|
| [ruoyi-vue-pro](https://gitee.com/zhijiantianya/ruoyi-vue-pro) | [![Gitee star](https://gitee.com/zhijiantianya/ruoyi-vue-pro/badge/star.svg?theme=white)](https://gitee.com/zhijiantianya/ruoyi-vue-pro) [![GitHub stars](https://img.shields.io/github/stars/YunaiV/ruoyi-vue-pro.svg?style=social&label=Stars)](https://github.com/YunaiV/ruoyi-vue-pro) | 基于 Spring Boot 多模块架构 |
| [yudao-cloud](https://gitee.com/zhijiantianya/yudao-cloud) | [![Gitee star](https://gitee.com/zhijiantianya/yudao-cloud/badge/star.svg?theme=white)](https://gitee.com/zhijiantianya/yudao-cloud) [![GitHub stars](https://img.shields.io/github/stars/YunaiV/yudao-cloud.svg?style=social&label=Stars)](https://github.com/YunaiV/yudao-cloud) | 基于 Spring Cloud 微服务架构 |
| [Spring-Boot-Labs](https://gitee.com/yudaocode/SpringBoot-Labs) | [![Gitee star](https://gitee.com/yudaocode/SpringBoot-Labs/badge/star.svg?theme=white)](https://gitee.com/zhijiantianya/yudao-cloud) [![GitHub stars](https://img.shields.io/github/stars/yudaocode/SpringBoot-Labs.svg?style=social&label=Stars)](https://github.com/yudaocode/SpringBoot-Labs) | 系统学习 Spring Boot & Cloud 专栏 |

### 🌐 前端项目

| 项目 | Star | 简介 |
|------|------|------|
| [yudao-ui-admin-vue3](https://gitee.com/yudaocode/yudao-ui-admin-vue3) | [![Gitee star](https://gitee.com/yudaocode/yudao-ui-admin-vue3/badge/star.svg?theme=white)](https://gitee.com/yudaocode/yudao-ui-admin-vue3) [![GitHub stars](https://img.shields.io/github/stars/yudaocode/yudao-ui-admin-vue3.svg?style=social&label=Stars)](https://github.com/yudaocode/yudao-ui-admin-vue3) | 基于 Vue3 + element-plus 实现的管理后台 |
| [yudao-ui-admin-vben](https://gitee.com/yudaocode/yudao-ui-admin-vben) | [![Gitee star](https://gitee.com/yudaocode/yudao-ui-admin-vben/badge/star.svg?theme=white)](https://gitee.com/yudaocode/yudao-ui-admin-vben) [![GitHub stars](https://img.shields.io/github/stars/yudaocode/yudao-ui-admin-vben.svg?style=social&label=Stars)](https://github.com/yudaocode/yudao-ui-admin-vben) | 基于 Vue3 + vben(ant-design-vue) 实现的管理后台 |
| [yudao-mall-uniapp](https://gitee.com/yudaocode/yudao-mall-uniapp) | [![Gitee star](https://gitee.com/yudaocode/yudao-mall-uniapp/badge/star.svg?theme=white)](https://gitee.com/yudaocode/yudao-mall-uniapp) [![GitHub stars](https://img.shields.io/github/stars/yudaocode/yudao-mall-uniapp.svg?style=social&label=Stars)](https://github.com/yudaocode/yudao-mall-uniapp) | 基于 uni-app 实现的商城小程序 |
| [yudao-ui-admin-vue2](https://gitee.com/yudaocode/yudao-ui-admin-vue2) | [![Gitee star](https://gitee.com/yudaocode/yudao-ui-admin-vue2/badge/star.svg?theme=white)](https://gitee.com/yudaocode/yudao-ui-admin-vue2) [![GitHub stars](https://img.shields.io/github/stars/yudaocode/yudao-ui-admin-vue2.svg?style=social&label=Stars)](https://github.com/yudaocode/yudao-ui-admin-vue2) | 基于 Vue2 + element-ui 实现的管理后台 |
| [yudao-ui-admin-uniapp](https://gitee.com/yudaocode/yudao-ui-admin-uniapp) | [![Gitee star](https://gitee.com/yudaocode/yudao-ui-admin-uniapp/badge/star.svg?theme=white)](https://gitee.com/yudaocode/yudao-ui-admin-uniapp) [![GitHub stars](https://img.shields.io/github/stars/yudaocode/yudao-ui-admin-uniapp.svg?style=social&label=Stars)](https://github.com/yudaocode/yudao-ui-admin-uniapp) | 基于 Vue2 + element-ui 实现的管理后台 |
| [yudao-ui-go-view](https://gitee.com/yudaocode/yudao-ui-go-view) | [![Gitee star](https://gitee.com/yudaocode/yudao-ui-go-view/badge/star.svg?theme=white)](https://gitee.com/yudaocode/yudao-ui-go-view) [![GitHub stars](https://img.shields.io/github/stars/yudaocode/yudao-ui-go-view.svg?style=social&label=Stars)](https://github.com/yudaocode/yudao-ui-go-view) | 基于 Vue3 + naive-ui 实现的大屏报表 |

### 📋 技术栈详情

#### 📦 模块说明

| 项目 | 说明 |
|------|------|
| `yudao-dependencies` | Maven 依赖版本管理 |
| `yudao-framework` | Java 框架拓展 |
| `yudao-server` | 管理后台 + 用户 APP 的服务端 |
| `yudao-module-system` | 系统功能的 Module 模块 |
| `yudao-module-member` | 会员中心的 Module 模块 |
| `yudao-module-infra` | 基础设施的 Module 模块 |
| `yudao-module-bpm` | 工作流程的 Module 模块 |
| `yudao-module-pay` | 支付系统的 Module 模块 |
| `yudao-module-mall` | 商城系统的 Module 模块 |
| `yudao-module-erp` | ERP 系统的 Module 模块 |
| `yudao-module-crm` | CRM 系统的 Module 模块 |
| `yudao-module-ai` | AI 大模型的 Module 模块 |
| `yudao-module-mp` | 微信公众号的 Module 模块 |
| `yudao-module-report` | 大屏报表 Module 模块 |

#### 🛠️ 核心框架

| 框架 | 说明 | 版本 | 学习指南 |
|------|------|------|----------|
| [Spring Boot](https://spring.io/projects/spring-boot) | 应用开发框架 | 2.7.18 | [文档](https://github.com/YunaiV/SpringBoot-Labs) |
| [MySQL](https://www.mysql.com/cn/) | 数据库服务器 | 5.7 / 8.0+ | - |
| [Druid](https://github.com/alibaba/druid) | JDBC 连接池、监控组件 | 1.2.23 | [文档](http://www.iocoder.cn/Spring-Boot/datasource-pool/?yudao) |
| [MyBatis Plus](https://mp.baomidou.com/) | MyBatis 增强工具包 | 3.5.7 | [文档](http://www.iocoder.cn/Spring-Boot/MyBatis/?yudao) |
| [Dynamic Datasource](https://dynamic-datasource.com/) | 动态数据源 | 3.6.1 | [文档](http://www.iocoder.cn/Spring-Boot/datasource-pool/?yudao) |
| [Redis](https://redis.io/) | key-value 数据库 | 5.0 / 6.0 /7.0 | - |
| [Redisson](https://github.com/redisson/redisson) | Redis 客户端 | 3.32.0 | [文档](http://www.iocoder.cn/Spring-Boot/Redis/?yudao) |
| [Spring MVC](https://github.com/spring-projects/spring-framework/tree/master/spring-webmvc) | MVC 框架 | 5.3.24 | [文档](http://www.iocoder.cn/SpringMVC/MVC/?yudao) |
| [Spring Security](https://github.com/spring-projects/spring-security) | Spring 安全框架 | 5.7.11 | [文档](http://www.iocoder.cn/Spring-Boot/Spring-Security/?yudao) |
| [Hibernate Validator](https://github.com/hibernate/hibernate-validator) | 参数校验组件 | 6.2.5 | [文档](http://www.iocoder.cn/Spring-Boot/Validation/?yudao) |
| [Flowable](https://github.com/flowable/flowable-engine) | 工作流引擎 | 6.8.0 | [文档](https://doc.iocoder.cn/bpm/) |
| [Quartz](https://github.com/quartz-scheduler) | 任务调度组件 | 2.3.2 | [文档](http://www.iocoder.cn/Spring-Boot/Job/?yudao) |
| [Springdoc](https://springdoc.org/) | Swagger 文档 | 1.7.0 | [文档](http://www.iocoder.cn/Spring-Boot/Swagger/?yudao) |
| [SkyWalking](https://skywalking.apache.org/) | 分布式应用追踪系统 | 8.12.0 | [文档](http://www.iocoder.cn/Spring-Boot/SkyWalking/?yudao) |
| [Spring Boot Admin](https://github.com/codecentric/spring-boot-admin) | Spring Boot 监控平台 | 2.7.10 | [文档](http://www.iocoder.cn/Spring-Boot/Admin/?yudao) |
| [Jackson](https://github.com/FasterXML/jackson) | JSON 工具库 | 2.13.5 | - |
| [MapStruct](https://mapstruct.org/) | Java Bean 转换 | 1.6.3 | [文档](http://www.iocoder.cn/Spring-Boot/MapStruct/?yudao) |
| [Lombok](https://projectlombok.org/) | 消除冗长的 Java 代码 | 1.18.34 | [文档](http://www.iocoder.cn/Spring-Boot/Lombok/?yudao) |
| [JUnit](https://junit.org/junit5/) | Java 单元测试框架 | 5.8.2 | - |
| [Mockito](https://github.com/mockito/mockito) | Java Mock 框架 | 4.8.0 | - |

---

## 📷 演示图

### 🖥️ 系统功能

| 模块 | 演示1 | 演示2 | 演示3 |
|------|-------|-------|-------|
| 登录 & 首页 | ![登录](/.image/登录.jpg) | ![首页](/.image/首页.jpg) | ![个人中心](/.image/个人中心.jpg) |
| 用户 & 应用 | ![用户管理](/.image/用户管理.jpg) | ![令牌管理](/.image/令牌管理.jpg) | ![应用管理](/.image/应用管理.jpg) |
| 租户 & 套餐 | ![租户管理](/.image/租户管理.jpg) | ![租户套餐](/.image/租户套餐.png) | - |
| 部门 & 岗位 | ![部门管理](/.image/部门管理.jpg) | ![岗位管理](/.image/岗位管理.jpg) | - |
| 菜单 & 角色 | ![菜单管理](/.image/菜单管理.jpg) | ![角色管理](/.image/角色管理.jpg) | - |
| 审计日志 | ![操作日志](/.image/操作日志.jpg) | ![登录日志](/.image/登录日志.jpg) | - |
| 短信 | ![短信渠道](/.image/短信渠道.jpg) | ![短信模板](/.image/短信模板.jpg) | ![短信日志](/.image/短信日志.jpg) |
| 字典 & 敏感词 | ![字典类型](/.image/字典类型.jpg) | ![字典数据](/.image/字典数据.jpg) | ![敏感词](/.image/敏感词.jpg) |
| 错误码 & 通知 | ![错误码管理](/.image/错误码管理.jpg) | ![通知公告](/.image/通知公告.jpg) | - |

### 🔄 工作流程

| 模块 | 演示1 | 演示2 | 演示3 |
|------|-------|-------|-------|
| 流程模型 | ![流程模型-列表](/.image/流程模型-列表.jpg) | ![流程模型-设计](/.image/流程模型-设计.jpg) | ![流程模型-定义](/.image/流程模型-定义.jpg) |
| 表单 & 分组 | ![流程表单](/.image/流程表单.jpg) | ![用户分组](/.image/用户分组.jpg) | - |
| 我的流程 | ![我的流程-列表](/.image/我的流程-列表.jpg) | ![我的流程-发起](/.image/我的流程-发起.jpg) | ![我的流程-详情](/.image/我的流程-详情.jpg) |
| 待办 & 已办 | ![任务列表-审批](/.image/任务列表-审批.jpg) | ![任务列表-待办](/.image/任务列表-待办.jpg) | ![任务列表-已办](/.image/任务列表-已办.jpg) |
| OA 请假 | ![OA请假-列表](/.image/OA请假-列表.jpg) | ![OA请假-发起](/.image/OA请假-发起.jpg) | ![OA请假-详情](/.image/OA请假-详情.jpg) |

### 🏗️ 基础设施

| 模块 | 演示1 | 演示2 | 演示3 |
|------|-------|-------|-------|
| 代码生成 | ![代码生成](/.image/代码生成.jpg) | ![生成效果](/.image/生成效果.jpg) | - |
| 文档 | ![系统接口](/.image/系统接口.jpg) | ![数据库文档](/.image/数据库文档.jpg) | - |
| 文件 & 配置 | ![文件配置](/.image/文件配置.jpg) | ![文件管理](/.image/文件管理2.jpg) | ![配置管理](/.image/配置管理.jpg) |
| 定时任务 | ![定时任务](/.image/定时任务.jpg) | ![任务日志](/.image/任务日志.jpg) | - |
| API 日志 | ![访问日志](/.image/访问日志.jpg) | ![错误日志](/.image/错误日志.jpg) | - |
| MySQL & Redis | ![MySQL](/.image/MySQL.jpg) | ![Redis](/.image/Redis.jpg) | - |
| 监控平台 | ![Java监控](/.image/Java监控.jpg) | ![链路追踪](/.image/链路追踪.jpg) | ![日志中心](/.image/日志中心.jpg) |

### 💳 支付系统

| 模块 | 演示1 | 演示2 | 演示3 |
|------|-------|-------|-------|
| 商家 & 应用 | ![商户信息](/.image/商户信息.jpg) | ![应用信息-列表](/.image/应用信息-列表.jpg) | ![应用信息-编辑](/.image/应用信息-编辑.jpg) |
| 支付 & 退款 | ![支付订单](/.image/支付订单.jpg) | ![退款订单](/.image/退款订单.jpg) | - |

### 📊 数据报表

| 模块 | 演示1 | 演示2 | 演示3 |
|------|-------|-------|-------|
| 报表设计器 | ![数据报表](/.image/报表设计器-数据报表.jpg) | ![图形报表](/.image/报表设计器-图形报表.jpg) | ![报表设计器-打印设计](/.image/报表设计器-打印设计.jpg) |
| 大屏设计器 | ![大屏列表](/.image/大屏设计器-列表.jpg) | ![大屏预览](/.image/大屏设计器-预览.jpg) | ![大屏编辑](/.image/大屏设计器-编辑.jpg) |

### 📱 移动端（管理后台）

| | | |
|---|---|---|
| ![](/.image/admin-uniapp/01.png) | ![](/.image/admin-uniapp/02.png) | ![](/.image/admin-uniapp/03.png) |
| ![](/.image/admin-uniapp/04.png) | ![](/.image/admin-uniapp/05.png) | ![](/.image/admin-uniapp/06.png) |
| ![](/.image/admin-uniapp/07.png) | ![](/.image/admin-uniapp/08.png) | ![](/.image/admin-uniapp/09.png) |

目前已经实现登录、我的、工作台、编辑资料、头像修改、密码修改、常见问题、关于我们等基础功能。

---

## 📁 项目结构

```
yudao/
├── 📁 yudao-dependencies/          # Maven依赖版本管理
├── 📁 yudao-framework/             # Java框架拓展
├── 📁 yudao-server/                # 管理后台+用户APP服务端
├── 📁 yudao-module-system/         # 系统功能模块
├── 📁 yudao-module-infra/          # 基础设施模块
├── 📁 yudao-module-bpm/            # 工作流程模块
├── 📁 yudao-module-pay/            # 支付系统模块
├── 📁 yudao-module-mall/           # 商城系统模块
├── 📁 yudao-module-erp/            # ERP系统模块
├── 📁 yudao-module-crm/            # CRM系统模块
├── 📁 yudao-module-ai/             # AI大模型模块
├── 📁 yudao-module-mp/             # 微信公众号模块
├── 📁 yudao-module-report/         # 大屏报表模块
├── 📁 yudao-ui/                    # 前端项目
│   ├── 📁 yudao-ui-admin-vue3/     # Vue3管理后台
│   ├── 📁 yudao-ui-admin-vben/     # Vben管理后台
│   ├── 📁 yudao-ui-admin-vue2/     # Vue2管理后台
│   └── 📁 yudao-mall-uniapp/       # 商城小程序
└── 📁 sql/                         # 数据库脚本
```

---

## 🎨 功能预览

### 🖥️ 管理后台
| 功能模块 | 效果展示 |
|---------|---------|
| 登录首页 | ![登录](/.image/登录.jpg) |
| 用户管理 | ![用户管理](/.image/用户管理.jpg) |
| 工作流程 | ![流程模型-设计](/.image/流程模型-设计.jpg) |

### 📱 移动端
| | | |
|---|---|---|
| ![](/.image/admin-uniapp/01.png) | ![](/.image/admin-uniapp/02.png) | ![](/.image/admin-uniapp/03.png) |

[查看更多演示图片](#演示图)

---

## 🤝 如何贡献

我们欢迎各种形式的贡献！

### 🔧 开发贡献
1. Fork 本仓库
2. 新建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

### 🐛 问题反馈
- [Gitee Issues](https://gitee.com/zhijiantianya/ruoyi-vue-pro/issues)
- [GitHub Issues](https://github.com/YunaiV/ruoyi-vue-pro/issues)

### 💡 功能建议
- 在 Issues 中提出您的想法
- 参与社区讨论

---

## 📄 开源协议

**为什么推荐使用本项目？**

✅ **完全免费**: 采用 [MIT License](https://gitee.com/zhijiantianya/ruoyi-vue-pro/blob/master/LICENSE) 开源协议，个人与企业可 100% 免费使用

✅ **代码全开源**: 不像其他项目只开源部分代码，让你无法了解整个项目架构

✅ **代码质量高**: 遵循《阿里巴巴 Java 开发手册》规范，113770 行 Java 代码，42462 行代码注释

![开源项目对比](/.image/common/project-vs.png)

---

## 🎁 项目外包

💼 **专业外包团队**

我们也接外包项目，如有需要可微信联系 **Aix9975**

🏢 **团队实力**
- 专业的项目经理、架构师
- 资深前端工程师、后端工程师  
- 经验丰富的测试工程师、运维工程师
- 提供全流程外包服务

💻 **业务范围**
商城系统、SCRM、OA、物流、ERP、CMS、HIS、支付、IM聊天、微信公众号、小程序等

---

<div align="center">

### 🌟 给项目点个 Star 吧！

**如果这个项目对您有帮助，请不要忘记点击 ⭐️ Star**

**这对我们来说是最大的鼓励和支持！**

<br>

![项目关系](/.image/common/yudao-roadmap.png)

---

<sub>Made with ❤️ by 芋道源码</sub>

</div>
