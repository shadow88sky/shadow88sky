<p align="center">
  <a href="http://39.102.50.88/">
    <img src="./assets/profile-banner.svg" alt="徐晨 / Chen Xu — AI 产品与全栈工程师" width="100%" />
  </a>
</p>

<p align="center">
  <strong>把业务需求交付成能上线、可维护的产品</strong><br />
  AI product engineering · Node.js / TypeScript · Full-stack delivery
</p>

<p align="center">
  <a href="http://39.102.50.88/"><strong>个人网站</strong></a>
  &nbsp;·&nbsp;
  <a href="http://39.102.50.88/#work"><strong>项目与 Demo</strong></a>
  &nbsp;·&nbsp;
  <a href="http://39.102.50.88/resume.html"><strong>完整简历</strong></a>
  &nbsp;·&nbsp;
  <a href="mailto:119136016@qq.com?subject=Project%20Inquiry"><strong>联系合作</strong></a>
</p>

---

### 你好，我是徐晨 👋

我是一名全栈 AI / Agent 开发工程师，有 **15 年软件研发经验**，长期使用 **Node.js、TypeScript、NestJS、React 和 PostgreSQL** 构建生产系统。自 2023 年起，我持续开发 AI 搜索、RAG、业务 Agent、文档识别与自动化产品。

我既能从模糊需求开始完成产品与架构设计，也能进入现有代码库解决后端、数据库、API 集成、性能和部署问题。开发中重视可控性：确定性流程交给普通程序，模型负责语义理解与生成，并通过校验、超时、重试、来源追踪和人工复核控制风险。

> **目前可承接远程项目与长期开发合作。** 支持中文和英文文字沟通，可从 MVP、单个核心模块开始合作。

### 我可以帮你完成

| 方向 | 可交付内容 |
| --- | --- |
| **AI 应用落地** | RAG、知识库问答、Agent 工作流、Tool Calling、多模型接入、流式输出与评测 |
| **文档与 OCR 自动化** | PDF / 图片识别、结构化字段提取、业务规则校验、人工复核、报表与导出 |
| **Node.js / TypeScript 后端** | NestJS API、PostgreSQL / MySQL、Redis、队列、定时任务、WebSocket 与第三方 API |
| **全栈产品与后台** | Next.js / React、SaaS 控制台、运营后台、权限、支付与数据分析 |
| **系统交付与治理** | 架构设计、数据库设计、Docker / Kubernetes、Nginx、CI/CD、日志和生产问题排查 |

### 精选项目

#### EntryFlow · 发票 OCR、复核与财务报表

OCR-first 的发票处理应用。本地 OCR 与金额校验优先，仅在字段缺失、计算不一致或图像不清楚时调用视觉模型复核，从而兼顾成本、速度与准确性。

- PDF / 图片 OCR、中英文识别与原始文本追踪
- 必填字段、行项目汇总、税额和总额校验
- 重复票据检测、人工修改记录、审批与付款状态
- 月度、供应商、多币种、逾期和处理质量报表

**FastAPI · SQLite · Tesseract · Poppler · DeepSeek**<br />
[在线 Demo](http://39.102.50.88/entryflow/) · [技术详解](http://39.102.50.88/projects/entryflow.html) · [源代码](https://github.com/shadow88sky/entryflow)

#### RankWeave · AI 品牌可见度与 GEO 平台

面向国际市场的 GEO 产品，监测品牌在多个 AI 搜索引擎中的提及率、引用来源和竞品位置，并提供站点诊断、内容生成与持续监测。

- 多模型并发调度、引擎级超时、失败隔离与实时进度
- 品牌提及、竞品 SOV、情感、内容差距和引用域名分析
- AI Crawler、robots.txt、Schema.org、SEO 与知识图谱审计
- 开源 GEO 审计 CLI / API，覆盖 9 类 AI 爬虫

**Next.js · React · NestJS · PostgreSQL · TypeORM**<br />
[产品 Demo](http://39.102.50.88:8081) · [技术详解](http://39.102.50.88/projects/rankweave.html) · [开源审计工具](https://github.com/shadow88sky/rankweave-geo-audit)

#### AnswerDesk AI · 可配置业务客服 Agent

将知识检索、字段收集、外部工具和人工接管连接为可配置流程的业务执行平台，支持网页 Widget、Telegram Bot 和 REST API。

- Hybrid RAG、向量与关键词检索、RRF 融合和来源追踪
- FAQ-first、Playbook、Workflow、Structured Output 与 Tool Calling
- Webhook 超时和重试、低置信度转人工、完整执行轨迹
- 知识库、Inbox、测试台、评测和运营控制台

**Next.js · TypeScript · PostgreSQL · Qdrant · LangChain**<br />
[产品 Demo](http://39.102.50.88:8082) · [技术详解](http://39.102.50.88/projects/answerdesk.html)

#### TypoGraphy AI · Web3 搜索与 RAG

在 KNN3 Network 主导开发的 Web3 垂直搜索产品。我负责核心后端、知识检索和协议集成，搭建从网页与文档采集、分块、向量入库到流式回答和来源引用的完整链路。

**NestJS · OpenAI / Llama2 · LangChain · Milvus · Elasticsearch**<br />
[项目经历](http://39.102.50.88/projects/typoai.html) · [官方产品介绍](https://medium.com/knn3-network/typography-ai-v2-0-product-upgrade-7a9d9601722c)

### 技术能力

```text
AI / Agent     RAG · Tool Calling · Structured Output · LangChain · DeepSeek · OpenAI · Gemini
Backend        Node.js · TypeScript · NestJS · Go · Python · REST · GraphQL · WebSocket
Frontend       Next.js · React · TypeScript · Tailwind CSS
Data           PostgreSQL · MySQL · Redis · Qdrant · Milvus · Elasticsearch / OpenSearch
Infrastructure Docker · Kubernetes · Helm · Nginx · PM2 · ELK · GitHub Actions
```

### 相关经历

- 曾带领 **10+ 人技术团队**完成产品从 0 到 1，负责架构、研发计划、核心开发与交付。
- 主导 Web3 AI 搜索与数据标注产品，其中第三方 API 获客户采购接入，标注产品累计服务 7 万用户。
- 负责过企业 BFF 通用框架、公共服务、Kubernetes 容器化、ELK 日志体系和大型活动平台。
- 完成 Ethereum、Solana、Base、BSC、Tron、TON 多链服务适配与跨链交易后端。

### 联系我

如果你正在做 AI 产品、业务自动化、Node.js 后端或现有系统改造，可以在邮件中简单说明**目标、当前技术栈、期望时间和预算范围**，我会尽快回复并给出可执行方案。

**Email:** [119136016@qq.com](mailto:119136016@qq.com?subject=Project%20Inquiry)<br />
**Portfolio:** [39.102.50.88](http://39.102.50.88/)<br />
**Résumé:** [在线简历](http://39.102.50.88/resume.html)

<p align="center">
  <sub>Available for freelance projects and long-term remote collaboration.</sub>
</p>
