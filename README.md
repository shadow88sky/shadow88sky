<p align="center">
  <a href="http://39.102.50.88/">
    <img src="./assets/profile-banner.svg" alt="徐晨 / Chen Xu — AI、Web3 与 Web2 全栈工程师" width="100%" />
  </a>
</p>

<p align="center">
  <strong>15 年生产系统研发经验，把业务需求交付成能上线、可维护的产品</strong><br />
  AI products · Web3 infrastructure · Web2 systems
</p>

<p align="center">
  <a href="#01--ai-应用与-agent"><strong>AI</strong></a>
  &nbsp;·&nbsp;
  <a href="#02--web3-与区块链系统"><strong>Web3</strong></a>
  &nbsp;·&nbsp;
  <a href="#03--web2-全栈与企业系统"><strong>Web2</strong></a>
  &nbsp;│&nbsp;
  <a href="http://39.102.50.88/"><strong>个人网站</strong></a>
  &nbsp;·&nbsp;
  <a href="http://39.102.50.88/resume.html"><strong>完整简历</strong></a>
  &nbsp;·&nbsp;
  <a href="mailto:119136016@qq.com?subject=Project%20Inquiry"><strong>联系合作</strong></a>
</p>

---

### 你好，我是徐晨 👋

我是一名拥有 **15 年软件研发经验**的全栈与后端工程师，职业经历覆盖 **Web2 企业系统、Web3 基础设施和 AI 产品**。主力技术栈为 **Node.js、TypeScript、NestJS、React 和 PostgreSQL**，也使用 Go、Python、Solidity 以及云原生工具完成特定场景的交付。

我做过全国门店业务系统、企业 BFF 与公共服务、万人活动平台、钱包和跨链服务、Web3 数据产品，也独立完成了 RAG、业务 Agent、GEO 和文档 OCR 产品。既能从模糊需求开始完成产品与架构设计，也能进入现有代码库解决核心开发、数据库、API 集成、性能、部署和生产问题。

> **目前可承接远程项目与长期开发合作。** 支持中文和英文文字沟通，可从 MVP、核心模块或现有系统改造开始合作。

### 三个主要方向

| AI 应用工程 | Web3 系统工程 | Web2 全栈工程 |
| --- | --- | --- |
| RAG、Agent、OCR、多模型编排、知识库与业务自动化 | 钱包、跨链、多链适配、链上数据、智能合约与 Web3 API | Node.js 后端、SaaS、运营后台、微服务、数据库与基础设施 |

## 01 · AI 应用与 Agent

自 2023 年起持续开发真实 AI 产品，覆盖 RAG、向量检索、Web Search / Crawler、Tool Calling、Structured Output、状态机、Human-in-the-loop、多模型调度和生产异常治理。

### EntryFlow · 发票 OCR、复核与财务报表

OCR-first 的发票处理应用。本地 OCR 与金额校验优先，仅在字段缺失、计算不一致或图像不清楚时调用视觉模型复核，从而兼顾成本、速度与准确性。

<p align="center">
  <a href="http://39.102.50.88/entryflow/"><img src="./assets/entryflow.png" alt="EntryFlow 发票识别、复核与报表界面" width="100%" /></a>
</p>

- PDF / 图片 OCR、字段与金额校验、重复检测和人工修改记录
- 审批、付款状态、月度与供应商报表，以及 CSV / Excel 导出

**FastAPI · SQLite · Tesseract · Poppler · DeepSeek**<br />
[在线 Demo](http://39.102.50.88/entryflow/) · [技术详解](http://39.102.50.88/projects/entryflow.html) · [源代码](https://github.com/shadow88sky/entryflow)

### RankWeave · AI 品牌可见度与 GEO 平台

监测品牌在多个 AI 搜索引擎中的提及率、引用来源和竞品位置，并提供站点诊断、内容生成与持续监测。

<p align="center">
  <a href="http://39.102.50.88:8081"><img src="./assets/rankweave.jpg" alt="RankWeave AI 品牌可见度产品界面" width="100%" /></a>
</p>

- 多模型并发调度、失败隔离、SSE 实时进度和部分成功策略
- 品牌与竞品分析、引用聚合、AI Crawler、Schema.org 和 SEO 审计

**Next.js · React · NestJS · PostgreSQL · TypeORM**<br />
[产品 Demo](http://39.102.50.88:8081) · [技术详解](http://39.102.50.88/projects/rankweave.html) · [开源审计工具](https://github.com/shadow88sky/rankweave-geo-audit)

### AnswerDesk AI · 可配置业务客服 Agent

将知识检索、字段收集、外部工具和人工接管连接为可配置流程的业务执行平台，支持网页 Widget、Telegram Bot 和 REST API。

<p align="center">
  <a href="http://39.102.50.88:8082"><img src="./assets/answerdesk.jpg" alt="AnswerDesk AI 知识库与业务工作流界面" width="100%" /></a>
</p>

- Hybrid RAG、RRF 融合、来源追踪、Playbook 和 Structured Output
- Webhook 工具、超时与重试、低置信度转人工和完整执行轨迹

**Next.js · TypeScript · PostgreSQL · Qdrant · LangChain**<br />
[产品 Demo](http://39.102.50.88:8082) · [技术详解](http://39.102.50.88/projects/answerdesk.html)

## 02 · Web3 与区块链系统

具备从钱包认证、多链节点接入和跨链状态管理，到链上数据采集、关系图谱、Web3 搜索与智能合约的完整经验。

### 钱包与跨链 · Tomo / World Liberty Financial

- 从 0 到 1 搭建注册、登录、认证与钱包生成核心模块，并与 Cubist 安全基础设施集成
- 完成 Ethereum、Solana、Base、BSC、Tron、TON 六条主流公链适配
- 通过幂等、状态机、缓存、日志和失败恢复处理链上确认时间差异与节点波动

**Node.js · TypeScript · Cubist · Multi-chain · State Machine**

### TypoGraphy AI / TypoCurator · KNN3 Network

- 主导基于 RAG 的 Web3 AI 搜索引擎，接入 OpenAI / Llama2、LangChain、Milvus 和多个 Web3 协议；对外 API 被第三方项目采购接入
- 主导 Telegram / TON 数据标注平台，上线首周 3 万用户、累计 7 万用户，并获得 TON Grants

[TypoGraphy AI 项目经历](http://39.102.50.88/projects/typoai.html) · [官方产品介绍](https://medium.com/knn3-network/typography-ai-v2-0-product-upgrade-7a9d9601722c)

### MeshGraph · 钱包关系与链上数据

搭建 Geth 节点并聚合 ETH 全量区块、TheGraph、Snapshot、.bit 等数据，以 ClickHouse、GraphQL API 和 SDK 支持钱包关系、NFT / Token 资产查询和可视化分析。

[KNN3 SDK](https://github.com/KNN3-Network/KNN3-SDK) · [OAuth 回调服务](https://github.com/KNN3-Network/oauth-server) · [Snapshot 数据同步](https://github.com/KNN3-Network/snapshot)

### SecureDeal · 智能合约支付信任

使用 Solidity 实现的合约项目，用链上规则解决互联网交易中的付费信任问题。

[查看 Solidity 源代码](https://github.com/shadow88sky/SecureDeal)

## 03 · Web2 全栈与企业系统

从 2011 年开始参与和负责生产系统研发，积累了企业后端、微服务、SaaS 控制台、数据服务、高并发活动和团队管理经验。

### 企业平台与基础设施 · GaiaWorks

- 基于 NestJS 设计 BFF 通用框架，模块化集成 Redis、MySQL、加解密、签名与请求转发
- 建设短链、验证码、Excel 转 PDF 等公共服务，并带队完成低代码平台、可视化编辑器和在线 IDE
- 推动 Docker / Kubernetes 容器化上线，建设前端埋点、日志上报与 ELK 分析链路

### 产品从 0 到 1 与高并发活动

- 从零组建并管理 10+ 人技术团队，负责架构、招聘、研发流程、Code Review 和交付
- 以 Kong、ELK、Elasticsearch 和 Go 建设微服务体系
- 支撑百威万人电音节活动，峰值 QPS 400，全程稳定运行

### 长期生产系统经验

- 参与启信宝 App 企业信息查询后端升级与性能优化
- 参与全国麦当劳门店考勤、工时统计和月末薪资结算系统研发与维护
- 交付广州铁路 Wi-Fi 接入、人员位置、流量监控和运营 Dashboard

### Node.js 开源积累

| 项目 | 方向 |
| --- | --- |
| [Nest-WebSocket](https://github.com/shadow88sky/Nest-WebSocket) | NestJS WebSocket 示例与服务通信 |
| [nest-grpc](https://github.com/shadow88sky/nest-grpc) | NestJS gRPC 服务示例 |
| [mongoose-api](https://github.com/shadow88sky/mongoose-api) | Node.js / MongoDB API 封装 |
| [shadow-mysql](https://github.com/shadow88sky/shadow-mysql) | MySQL 接口封装 |
| [excelToPdf](https://github.com/shadow88sky/excelToPdf) | Excel 到 PDF 转换服务 |

## 技术栈

```text
AI / Search     RAG · Agent Workflow · Tool Calling · LangChain · DeepSeek · OpenAI · Gemini
Backend         Node.js · TypeScript · NestJS · Go · Python · REST · GraphQL · WebSocket
Web3            Ethereum · Solana · Base · BSC · Tron · TON · Solidity · TheGraph
Frontend        Next.js · React · TypeScript · Tailwind CSS · SaaS / Admin Console
Data            PostgreSQL · MySQL · Redis · ClickHouse · Qdrant · Milvus · Elasticsearch
Infrastructure  Docker · Kubernetes · Helm · Nginx · PM2 · ELK · GitHub Actions
```

## 联系合作

如果你正在开发 **AI 产品、Web3 服务、Node.js 后端、SaaS 平台或企业系统**，可以在邮件中简单说明目标、当前技术栈、期望时间和预算范围，我会尽快回复并给出可执行方案。

**Email:** [119136016@qq.com](mailto:119136016@qq.com?subject=Project%20Inquiry)<br />
**Portfolio:** [39.102.50.88](http://39.102.50.88/)<br />
**Résumé:** [在线简历](http://39.102.50.88/resume.html)

<p align="center">
  <sub>Available for freelance projects and long-term remote collaboration.</sub>
</p>
