<div align="center">

# AI Platform & Backend Engineer

### LLM Gateway · Agent Runtime · Distributed Systems

近 10 年后端与平台工程经验，最近 3 年专注 AI Infra、LLM Platform 与 Agent Runtime，具备从需求拆解、架构设计、核心实现到云上交付和稳定性治理的端到端经验。

</div>

---

## 核心能力

- **LLM Platform**：多模型网关与协议适配，覆盖 OpenAI / Anthropic API、Tool Calling、多模态消息、Prompt Cache、流式 SSE，以及 Token / Cost 计量。
- **Agent Runtime**：Agent 编排、MCP / Custom Widget、隔离 Sandbox、Session / Snapshot / Volume、异步任务执行与多渠道 Bot Gateway。
- **Backend & Infrastructure**：使用 Go、Python、PHP 构建后端服务和平台基础设施，熟悉 Kratos、FastAPI、Gin、Flask 与 NestJS。
- **Distributed Systems**：围绕 MySQL、Redis、MongoDB、Elasticsearch、Kafka、AWS SNS / SQS 处理并发控制、幂等、重试、消息顺序与最终一致性。
- **Observability & Cloud**：使用 OpenTelemetry 建设跨 HTTP、WebSocket、消息队列、Sandbox 和数据库的端到端可观测性；具备 AWS 与 Cloudflare 的生产部署经验。

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Kratos-00ADD8?style=flat-square" alt="Kratos" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
</p>

---

## 工作经历

### MyShell · AI Platform Backend

`2023.08 - 2026.06`

负责 AI Bot / Agent 平台后端与基础设施研发，并推动核心后端从 NestJS 向 Go / Kratos 渐进式迁移。

**LLM Gateway 与多模型协议治理**

- 主导从 0 建设 FastAPI LLM Proxy，统一 OpenAI-compatible Chat Completions 与 Anthropic Messages API，适配 OpenRouter、AWS Bedrock、Azure OpenAI 等模型后端。
- 支持 SSE 流式输出、Tool Calling、多模态消息及 reasoning / thinking 参数，统一不同 Provider 的模型、参数、错误与响应协议。
- 建设鉴权、余额检查、Token / Cached Token / Cost 计量、Prompt Cache、错误映射与 LLM Trace，维护流式请求的完整 Trace 生命周期。

**Agent Runtime 与异步任务基础设施**

- 建设 MCP / Custom Widget 工具发现与版本管理，以及按 Bot / 用户隔离的 Sandbox、Session、Snapshot 和持久 Volume。
- 支持健康检查、断线重连、状态恢复、定时 Agent Task，以及文本、语音、图片、视频和文件等多模态输入输出。
- 设计消息队列基础库与 Consumer Runner，统一事件封装、并发控制、超时、幂等、重试、Trace 传播和容量保护。

**平台工程、稳定性与云上交付**

- 使用 OpenTelemetry 贯通 HTTP、WebSocket、线程 / 异步任务、Agent Session、消息队列、Sandbox 和 MySQL，并关联日志、消费耗时与排队延迟。
- 治理流式请求断线重连、Provider fallback / retry、慢 SQL、连接池、锁竞争和幂等补偿等生产问题。
- 推动服务从 EC2 向 ECS 容器化迁移，落地 Cloudflare Workers / Pages，并接入 AWS Bedrock、S3、SES、SNS 与 SQS。
- 优化 Go 项目 CI / Lint 流程，将执行时间从 15 分钟以上缩短至约 3.5 分钟。

### Shopee · Senior Software Engineer

`2022.03 - 2023.07`

- 负责视频审核回查系统的架构设计与实现，使用 Go、Elasticsearch、MySQL 与 Kafka 串联事件接入、数据存储、多维检索和运营查询，支持多国家业务。
- 参与人审系统重构，负责网关与 Portal 服务，支持消息队列和 RPC 两种进审方式，并通过权限校验、流量控制与配置化物料接入提升系统扩展性。

### Momo · Senior Crawler Engineer

`2020.07 - 2022.02`

- 使用 PHP 与 Go 建设内容平台、搜索、Feed、账户和运营后台，推进内容数据分库分表，并接入 OpenSearch、Redis、MySQL、MongoDB 与 Elasticsearch。
- 建设内容数据引入链路，完成 500 万+视频和图片资源导入，并串联下载、上传、转码、去重和打标流程。

### Earlier Data Infrastructure Experience

`2017.01 - 2020.06`

- 建设分布式爬虫任务调度系统，管理 80+ 爬虫、200+ 队列，日调度任务超过 5 亿次。
- 参与 7000 万+商品的每日更新链路，使用 Kafka 解耦数据生产与消费；通过 scrapy-redis 批量取任务将爬虫性能提升约 30%。
- 完成 100+ 数据源与 5000 万+企业基础信息采集，并建设基于 InfluxDB、Grafana、Fluentd 的监控与数据平台。

---

## 技术栈

**AI & Agent**

`LLM Gateway` · `OpenAI / Anthropic API` · `Tool Calling` · `Multimodal` · `Prompt Cache` · `SSE` · `Agent Runtime` · `MCP` · `Sandbox`

**Backend**

`Go` · `Python` · `PHP` · `Kratos` · `FastAPI` · `Gin` · `Flask` · `NestJS`

**Data & Messaging**

`MySQL` · `Redis` · `MongoDB` · `Elasticsearch` · `Kafka` · `AWS SNS / SQS` · `DynamoDB`

**Cloud & Engineering**

`OpenTelemetry` · `AWS ECS / Bedrock / S3` · `Cloudflare Workers / Pages` · `Docker` · `CI / CD`

---

## Vibe Coding

| 项目 | 简介 |
| --- | --- |
| [Codex-QuotaGlass](https://github.com/qshine/Codex-QuotaGlass) | 原生 macOS 桌面沙漏，实时展示 Codex 剩余额度与重置时间。 |
| [Lapp](https://github.com/qshine/Lapp) | 键盘优先的原生 macOS 快速启动器，支持应用搜索、内联计算、Web 搜索和本地剪贴板历史。 |
