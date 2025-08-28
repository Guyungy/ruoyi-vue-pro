<div align="center">

# 芋道管理系统 🚀

<p>
 <img src="https://img.shields.io/badge/Spring%20Boot-3.5.4-brightgreen.svg" alt="Spring Boot">
 <img src="https://img.shields.io/badge/Java-17/21-orange.svg" alt="Java">
 <img src="https://img.shields.io/badge/Vue-3.2-4fc08d.svg" alt="Vue">
 <img src="https://img.shields.io/badge/MySQL-8.0+-4479a1.svg" alt="MySQL">
 <img src="https://img.shields.io/badge/Redis-7.0+-dc382d.svg" alt="Redis">
 <img src="https://img.shields.io/github/license/YunaiV/ruoyi-vue-pro" alt="License" />
 <img src="https://img.shields.io/github/stars/YunaiV/ruoyi-vue-pro?style=social" alt="GitHub stars">
</p>

**🎯 打造中国第一流的快速开发平台，全部开源，个人与企业可 100% 免费使用**

**严肃声明：现在、未来都不会有商业版本，所有代码全部开源！**

</div>

---

## 📋 目录

- [🎯 项目简介](#-项目简介)
- [✨ 核心特性](#-核心特性)
- [🚀 快速开始](#-快速开始)
- [🏗️ 技术架构](#️-技术架构)
- [📦 功能模块](#-功能模块)
- [🔧 技术栈](#-技术栈)
- [📸 项目演示](#-项目演示)
- [🤝 参与贡献](#-参与贡献)
- [📄 开源协议](#-开源协议)

---

## 🎯 项目简介

**芋道管理系统**是一款基于 Spring Boot + Vue.js 构建的现代化企业级快速开发平台。项目采用前后端分离架构，内置完整的权限管理、工作流引擎、支付系统、商城系统、CRM、ERP等业务模块，帮助开发者快速构建企业级应用。

### 🌟 为什么选择芋道？

- **📦 开箱即用**：内置20+业务模块，覆盖企业应用90%场景
- **🏗️ 模块化设计**：采用Maven多模块架构，支持按需引入
- **🔒 安全可靠**：内置Spring Security + JWT认证，支持多租户
- **📱 多端适配**：支持PC端、移动端、小程序一套代码多端部署
- **🎨 界面精美**：提供Vue3/Vue2多套UI方案，开箱即用
- **📚 文档完善**：提供详细的开发文档和视频教程

### 🚀 快速体验

| 平台类型 | 演示地址 | 账号密码 |
|---------|---------|---------|
| **Vue3 + Element Plus** | [🌐 在线体验](http://dashboard-vue3.yudao.iocoder.cn) | admin/admin123 |
| **Vue3 + Ant Design Vue** | [🌐 在线体验](http://dashboard-vben.yudao.iocoder.cn) | admin/admin123 |
| **Vue2 + Element UI** | [🌐 在线体验](http://dashboard.yudao.iocoder.cn) | admin/admin123 |

### 📖 相关文档

- [📘 快速开始](https://doc.iocoder.cn/quick-start/) - 5分钟搭建开发环境
- [🎬 视频教程](https://doc.iocoder.cn/video/) - 手把手教学视频
- [📖 开发文档](https://doc.iocoder.cn/) - 详细的开发指南
- [🔧 部署指南](https://doc.iocoder.cn/deploy/) - 生产环境部署

## ✨ 核心特性

### 🏗️ 架构设计

- **前后端分离**：Spring Boot + Vue.js，支持多种前端UI框架
- **微服务就绪**：模块化设计，轻松拆分为微服务架构
- **多数据库支持**：MySQL、Oracle、PostgreSQL、SQL Server等
- **多环境部署**：支持Docker、K8s容器化部署

### 🔐 安全特性

- **权限管理**：基于RBAC模型，支持菜单、按钮级权限控制
- **多租户**：SaaS模式，支持租户数据隔离
- **单点登录**：集成OAuth2.0，支持第三方登录
- **数据安全**：SQL注入防护、XSS攻击防护

### 📦 版本说明

| 版本类型 | 项目地址 | JDK 8 + Spring Boot 2.7 | JDK 17/21 + Spring Boot 3.x |
|---------|---------|-------------------------|----------------------------|
| **🎁 完整版** | [ruoyi-vue-pro](https://gitee.com/zhijiantianya/ruoyi-vue-pro) | [`master`](https://gitee.com/zhijiantianya/ruoyi-vue-pro/tree/master/) | [`master-jdk17`](https://gitee.com/zhijiantianya/ruoyi-vue-pro/tree/master-jdk17/) |
| **⚡ 精简版** | [yudao-boot-mini](https://gitee.com/yudaocode/yudao-boot-mini) | [`master`](https://gitee.com/yudaocode/yudao-boot-mini/tree/master/) | [`master-jdk17`](https://gitee.com/yudaocode/yudao-boot-mini/tree/master-jdk17/) |

> **版本选择建议**
> - **🎁 完整版**：包含系统功能、基础设施、会员中心、工作流程、商城系统、CRM、ERP等20+业务模块
> - **⚡ 精简版**：仅包含系统功能、基础设施功能，适合快速开发基础管理系统
> - **📋 迁移指南**：参考[迁移文档](https://doc.iocoder.cn/migrate-module/)，5-10分钟完成版本间迁移

## 🚀 快速开始

### 📋 环境要求

| 环境 | 版本要求 | 备注 |
|-----|---------|------|
| **JDK** | 17+ | 推荐使用 OpenJDK 17/21 |
| **Node.js** | 16+ | 推荐使用 18.x |
| **MySQL** | 5.7+ / 8.0+ | 推荐 8.0+ |
| **Redis** | 6.0+ | 推荐 7.0+ |
| **Maven** | 3.6+ | 项目构建工具 |

### ⚡ 本地开发

```bash
# 1. 克隆项目
git clone https://gitee.com/zhijiantianya/ruoyi-vue-pro.git

# 2. 导入数据库
# 执行 sql/ 目录下的数据库脚本

# 3. 启动后端服务
cd ruoyi-vue-pro
mvn clean install
cd yudao-server
mvn spring-boot:run

# 4. 启动前端服务 (以Vue3版本为例)
git clone https://gitee.com/yudaocode/yudao-ui-admin-vue3.git
cd yudao-ui-admin-vue3
npm install
npm run dev
```

### 🐳 Docker部署

```bash
# 使用 Docker Compose 一键启动
docker-compose up -d
```

## 🏗️ 技术架构

<div align="center">

![架构图](/.image/common/ruoyi-vue-pro-architecture.png)

</div>

### 🎯 技术选型

**后端技术栈**
- **框架基础**: Spring Boot 3.x + Spring Security + Spring MVC
- **数据持久**: MyBatis Plus + Dynamic Datasource + Redis
- **工作流**: Flowable 工作流引擎
- **任务调度**: Quartz 定时任务
- **接口文档**: Springdoc (OpenAPI 3)
- **监控运维**: Spring Boot Admin + SkyWalking
- **消息队列**: Redis Stream / RabbitMQ / Kafka

**前端技术栈**
- **Vue 3**: Element Plus / Ant Design Vue
- **Vue 2**: Element UI
- **移动端**: uni-app (支持APP/小程序/H5)
- **构建工具**: Vite / Webpack
- **状态管理**: Pinia / Vuex

**基础设施**
- **数据库**: MySQL / Oracle / PostgreSQL / SQL Server
- **缓存**: Redis + Redisson
- **存储**: MinIO / 阿里云OSS / 腾讯云COS
- **部署**: Docker / Kubernetes

## 📦 功能模块

<div align="center">

![功能分层](/.image/common/ruoyi-vue-pro-biz.png)

</div>

### 🎯 模块架构

| 模块类型 | 模块说明 | 功能描述 |
|---------|---------|---------|
| **🔧 通用模块(必选)** | 系统功能 + 基础设施 | 用户管理、权限控制、代码生成、文件服务等 |
| **⚡ 通用模块(可选)** | 工作流 + 支付 + 报表 + 会员 | 流程引擎、支付对接、数据报表、会员体系 |
| **💼 业务系统(按需)** | ERP + CRM + 商城 + 公众号 + AI | 企业资源管理、客户关系、电商平台等 |

### 🏗️ 项目生态

<div align="center">

![架构演进](/.image/common/yudao-roadmap.png)

</div>

#### 🔥 后端项目

| 项目 | 架构类型 | 技术栈 | 适用场景 |
|-----|---------|-------|---------|
| [🎯 ruoyi-vue-pro](https://gitee.com/zhijiantianya/ruoyi-vue-pro) | 单体架构 | Spring Boot | 中小型企业快速开发 |
| [☁️ yudao-cloud](https://gitee.com/zhijiantianya/yudao-cloud) | 微服务 | Spring Cloud | 大型分布式系统 |
| [📚 SpringBoot-Labs](https://gitee.com/yudaocode/SpringBoot-Labs) | 学习专栏 | Spring 全家桶 | 技术学习和实践 |

#### 🎨 前端项目

| 项目 | UI框架 | 适用场景 | 特性 |
|-----|-------|---------|-----|
| [🎨 Vue3 + Element Plus](https://gitee.com/yudaocode/yudao-ui-admin-vue3) | Element Plus | 管理后台 | 组件丰富、稳定性好 |
| [🚀 Vue3 + Ant Design](https://gitee.com/yudaocode/yudao-ui-admin-vben) | Ant Design Vue | 管理后台 | 设计精美、功能强大 |
| [📱 uni-app商城](https://gitee.com/yudaocode/yudao-mall-uniapp) | uni-app | 移动端商城 | 跨端开发、一码多用 |
| [📊 数据大屏](https://gitee.com/yudaocode/yudao-ui-go-view) | Naive UI | 数据可视化 | 炫酷图表、实时展示 |

> 📋 **对比参考**: 查看社区整理的[国产开源项目对比表](https://www.yuque.com/xiatian-bsgny/lm0ec1/wqf8mn)

## 🔧 技术栈

### 📊 模块结构

| 模块 | 说明 | 技术栈 |
|-----|------|-------|
| `yudao-dependencies` | Maven 依赖版本管理 | Maven BOM |
| `yudao-framework` | Java 框架拓展 | Spring Boot Starter |
| `yudao-server` | 服务端启动模块 | Spring Boot Application |
| `yudao-module-system` | 系统功能模块 | Spring Security + JWT |
| `yudao-module-infra` | 基础设施模块 | Redis + MyBatis Plus |
| `yudao-module-bpm` | 工作流程模块 | Flowable |
| `yudao-module-pay` | 支付系统模块 | 支付宝/微信支付 |
| `yudao-module-mall` | 商城系统模块 | E-commerce |
| `yudao-module-erp` | ERP 系统模块 | Enterprise Resource Planning |
| `yudao-module-crm` | CRM 系统模块 | Customer Relationship Management |

### 🎯 核心框架

| 框架 | 版本 | 说明 | 学习文档 |
|-----|------|------|---------|
| [Spring Boot](https://spring.io/projects/spring-boot) | 3.5.4 | 应用开发框架 | [📚 学习指南](https://github.com/YunaiV/SpringBoot-Labs) |
| [Spring Security](https://spring.io/projects/spring-security) | 6.3.1 | 安全框架 | [📖 使用文档](http://www.iocoder.cn/Spring-Boot/Spring-Security/?yudao) |
| [MyBatis Plus](https://mp.baomidou.com/) | 3.5.7 | ORM 框架 | [📖 使用文档](http://www.iocoder.cn/Spring-Boot/MyBatis/?yudao) |
| [Redis](https://redis.io/) | 7.0+ | 缓存数据库 | [📖 使用文档](http://www.iocoder.cn/Spring-Boot/Redis/?yudao) |
| [Flowable](https://www.flowable.org/) | 7.0.0 | 工作流引擎 | [📖 使用文档](https://doc.iocoder.cn/bpm/) |
| [Quartz](http://www.quartz-scheduler.org/) | 2.3.2 | 任务调度 | [📖 使用文档](http://www.iocoder.cn/Spring-Boot/Job/?yudao) |
| [Springdoc](https://springdoc.org/) | 2.3.0 | 接口文档 | [📖 使用文档](http://www.iocoder.cn/Spring-Boot/Swagger/?yudao) |

## 📄 开源协议

### 💎 为什么选择我们？

<div align="center">

![开源项目对比](/.image/common/project-vs.png)

</div>

✅ **完全开源**: 采用 [MIT License](https://gitee.com/zhijiantianya/ruoyi-vue-pro/blob/master/LICENSE) 协议，比 Apache 2.0 更宽松  
✅ **商业友好**: 个人与企业可 100% 免费使用，无需保留版权信息  
✅ **代码质量**: 遵循阿里巴巴 Java 开发手册，113K+ 行代码，42K+ 行注释  
✅ **持续维护**: 活跃的社区，持续的功能更新和bug修复  

### 🤝 商业合作

如有项目外包需求，可联系微信：**Aix9975**

**服务范围**: 商城系统、OA办公、ERP管理、CRM客户、支付系统、IM聊天、微信开发等  
**团队配置**: 项目经理、架构师、前后端工程师、测试工程师、运维工程师

## 📸 项目演示

### 🖥️ 系统管理

| 功能模块 | 界面展示 | 功能模块 | 界面展示 |
|---------|---------|---------|---------|
| **登录页面** | ![登录](/.image/登录.jpg) | **系统首页** | ![首页](/.image/首页.jpg) |
| **用户管理** | ![用户管理](/.image/用户管理.jpg) | **角色管理** | ![角色管理](/.image/角色管理.jpg) |
| **菜单管理** | ![菜单管理](/.image/菜单管理.jpg) | **部门管理** | ![部门管理](/.image/部门管理.jpg) |

### 📋 工作流程

| 功能模块 | 界面展示 | 功能模块 | 界面展示 |
|---------|---------|---------|---------|
| **流程设计** | ![流程设计](/.image/流程模型-设计.jpg) | **我的流程** | ![我的流程](/.image/我的流程-列表.jpg) |
| **任务审批** | ![任务审批](/.image/任务列表-审批.jpg) | **OA请假** | ![OA请假](/.image/OA请假-发起.jpg) |

### 🛠️ 基础设施

| 功能模块 | 界面展示 | 功能模块 | 界面展示 |
|---------|---------|---------|---------|
| **代码生成** | ![代码生成](/.image/代码生成.jpg) | **系统监控** | ![Java监控](/.image/Java监控.jpg) |
| **文件管理** | ![文件管理](/.image/文件管理2.jpg) | **定时任务** | ![定时任务](/.image/定时任务.jpg) |

### 📊 数据报表

| 功能模块 | 界面展示 | 功能模块 | 界面展示 |
|---------|---------|---------|---------|
| **报表设计** | ![数据报表](/.image/报表设计器-数据报表.jpg) | **大屏设计** | ![大屏设计](/.image/大屏设计器-编辑.jpg) |

### 📱 移动端管理

| 界面展示 | 界面展示 | 界面展示 |
|---------|---------|---------|
| ![移动端1](/.image/admin-uniapp/01.png) | ![移动端2](/.image/admin-uniapp/02.png) | ![移动端3](/.image/admin-uniapp/03.png) |

## 🎯 核心功能

### 🔐 系统管理 (必选模块)

| 功能 | 描述 | 状态 |
|-----|------|------|
| **👤 用户管理** | 系统用户配置管理 | ✅ |
| **🔑 角色管理** | 角色权限分配，数据范围权限划分 | ✅ |
| **📋 菜单管理** | 配置系统菜单、操作权限、按钮权限 | ✅ |
| **🏢 部门管理** | 组织机构管理，树结构展现 | ✅ |
| **👥 岗位管理** | 配置用户担任职务 | ✅ |
| **🏪 租户管理** | SaaS 多租户功能 🚀 | ✅ |
| **📞 短信管理** | 短信渠道、模板、日志管理 🚀 | ✅ |
| **📧 邮件管理** | 邮箱账号、模版、发送日志 🚀 | ✅ |
| **🔍 操作日志** | 系统操作日志记录和查询 🚀 | ✅ |

### ⚡ 工作流程 (可选模块)

基于 **Flowable** 构建，支持信创数据库，满足中国特色流程操作：

| 功能 | 描述 | 状态 |
|-----|------|------|
| **🎨 SIMPLE 设计器** | 仿钉钉/飞书设计器，10分钟快速配置 | ✅ |
| **📐 BPMN 设计器** | 标准 BPMN，适配复杂业务场景 | ✅ |
| **👥 会签/或签** | 多人审批，支持全部同意或任意通过 | ✅ |
| **🔄 驳回/转办** | 灵活的审批流转控制 | ✅ |
| **⏰ 超时审批** | 自动触发超时处理 | ✅ |
| **🌳 条件分支** | 智能流程分支控制 | ✅ |

### 💰 支付系统 (可选模块)

| 功能 | 描述 | 状态 |
|-----|------|------|
| **💳 支付应用** | 对接支付宝、微信等支付渠道 🚀 | ✅ |
| **📋 支付订单** | 支付订单管理和查询 🚀 | ✅ |
| **💸 退款订单** | 退款订单管理和处理 🚀 | ✅ |
| **🔔 回调通知** | 支付回调通知处理 🚀 | ✅ |

### 🛒 商城系统 (业务模块)

完整的电商解决方案，[🌐 在线预览](https://doc.iocoder.cn/mall-preview/)

![商城功能](/.image/common/mall-feature.png)

### 📊 CRM系统 (业务模块) 

客户关系管理系统，[🌐 在线预览](https://doc.iocoder.cn/crm-preview/)

![CRM功能](/.image/common/crm-feature.png)

### 🏭 ERP系统 (业务模块)

企业资源规划系统，[🌐 在线预览](https://doc.iocoder.cn/erp-preview/)

![ERP功能](/.image/common/erp-feature.png)

### 🤖 AI大模型 (业务模块)

AI智能应用平台，[🌐 在线预览](https://doc.iocoder.cn/ai-preview/)

![AI功能](/.image/common/ai-feature.png)

---

> **💡 功能说明**  
> 🚀 表示新增功能 | ⭐ 表示重构功能 | ✅ 表示已完成  
> 本项目基于 RuoYi-Vue 深度优化，重构后端代码，美化前端界面  
> 所有功能均通过单元测试保证代码质量

## 🤝 参与贡献

我们欢迎所有形式的贡献，无论是新功能、bug修复、文档改进还是建议反馈。

### 💡 如何贡献

1. **🍴 Fork 项目** - 点击右上角的 Fork 按钮
2. **🌿 创建分支** - 从 master 创建你的特性分支
3. **✨ 提交更改** - 提交你的更改并编写清晰的提交信息
4. **📤 推送分支** - 推送到你的 Fork 仓库
5. **🔄 提交 PR** - 创建 Pull Request 到主仓库

### 📋 贡献类型

- **🐛 Bug 报告** - [提交 Issue](https://gitee.com/zhijiantianya/ruoyi-vue-pro/issues)
- **✨ 功能建议** - [讨论新功能](https://gitee.com/zhijiantianya/ruoyi-vue-pro/issues)
- **📖 文档完善** - 帮助改进文档质量
- **🧪 测试用例** - 编写和完善测试案例
- **🌐 国际化** - 帮助翻译多语言支持

### 🔗 联系我们

- **📧 邮箱**: yunai@iocoder.cn
- **💬 微信群**: 扫码加入技术交流群
- **🎯 问题反馈**: [Gitee Issues](https://gitee.com/zhijiantianya/ruoyi-vue-pro/issues)
- **📚 文档站点**: [doc.iocoder.cn](https://doc.iocoder.cn/)

---

<div align="center">

### 🌟 感谢所有贡献者

如果这个项目对您有帮助，请给我们一个 ⭐ Star 支持！

**「我喜欢写代码，乐此不疲」**  
**「我喜欢做开源，以此为乐」**

![Star History Chart](https://api.star-history.com/svg?repos=YunaiV/ruoyi-vue-pro&type=Timeline)

</div>
