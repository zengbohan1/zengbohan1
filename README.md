# Hi there 👋 我是曾波涵

**Java 后端开发工程师（AI 应用开发经验）** · 2027 届软件工程本科 · 英语 CET-4

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🧑‍💻 关于我

- 🎓 **南阳师范学院 · 软件工程**（2023.09 - 2027.06）
- 💼 **三段生产级 Java 后端实习**：第三方支付回调幂等治理 / 广告灰度实验流量分桶 / MQTT 摄像头设备接入
- 🤖 **自研并开源三个 AI 应用项目**：企业知识库 RAG 问答系统 · 多智能体舆情分析系统 · 轻量 Agent 编排框架
- 🎯 **关注方向**：Java 后端工程化（微服务 / 高并发 / 中间件）· 大模型应用开发（RAG / Agent / Function Calling / MCP）

## 🚀 开源项目

### 📚 企业知识库 RAG 问答系统
**Java 后端方向 · AI 应用** | [github.com/zengbohan1/enterprise-rag-qa](https://github.com/zengbohan1/enterprise-rag-qa)

> 完整 RAG 链路（解析 / 切片 / 向量化 / 混合检索 / 生成）+ Redis 三级语义缓存 + 异步并发改造 + Prometheus 监控

- 实测：**Recall@1 66.2% → 87.4%**，Recall@5 95.2% → 98.2%（334 条 QA 评测集）
- 实测：RAGAs 忠实度 **94.1%** / 答案相关性 88.7%
- 实测：压测 P95 延迟 **32s → 10s**（CPU 线程池 + ONNX 限线程调参）

### 📰 多智能体舆情分析系统
**AI 应用** | [github.com/zengbohan1/sentiment-analysis-agents](https://github.com/zengbohan1/sentiment-analysis-agents)

> Query / Media / Insight 三类 Agent 并行调度 + 自研 ForumEngine 协作调度器 + SSE 长任务管控 + 报告流水线（HTML / PDF / Markdown）

- 实测：工具调用成功率 **100%**（真实 LLM，265 次调用）
- 实测：**60 任务并发全部完成**，并行调度 P95 66.2s → 30.3s（-54%）
- 实测：故障注入下任务完成率 81.7% → 98.3%（重试防护），单任务平均成本 **0.054 元**

### 🧩 轻量 Agent 编排框架（agentflow）
**AI 应用 · 基础设施** | [github.com/zengbohan1/agent-orchestration-framework](https://github.com/zengbohan1/agent-orchestration-framework)

> 从多智能体项目沉淀的轻量编排框架：DAG 图编排 + StateGraph 状态机 + SQLite checkpoint（断点续传 / 幂等）+ MCP 工具注册中心（stdio / SSE）

- 实测：核心模块测试覆盖率 **89%**，43 个测试全过，MockLLM 调用成功率 100%

## 🛠️ 技术栈

| 领域 | 技术 |
|------|------|
| Java 后端 | Java、Spring Boot 3、Spring Cloud、MyBatis-Plus、MySQL（分库分表 / 调优）、Redis（分布式锁 / 缓存）、RabbitMQ、MQTT、Nacos、Docker、Nginx |
| AI 应用 | Python、FastAPI（asyncio / SSE）、LangChain、LangGraph、PGvector、RAGAs、Function Calling、MCP、vLLM / Ollama |
| 可观测与工程 | Prometheus + Grafana、阿里云 ARMS、JVM 诊断、pytest、GitHub Actions |

## 📊 GitHub

![followers](https://img.shields.io/github/followers/zengbohan1?style=flat-square&color=2F80ED)
![stars](https://img.shields.io/github/stars/zengbohan1?style=flat-square&color=2F80ED)
![repos](https://img.shields.io/github/repos/zengbohan1?style=flat-square&color=2F80ED)

| 项目 | 语言 | 状态 |
|------|------|------|
| [enterprise-rag-qa](https://github.com/zengbohan1/enterprise-rag-qa) | Python | v0.5 · Recall@1 87.4% |
| [sentiment-analysis-agents](https://github.com/zengbohan1/sentiment-analysis-agents) | Python | 工具成功率 100% · 60 并发 |
| [agent-orchestration-framework](https://github.com/zengbohan1/agent-orchestration-framework) | Python | 覆盖率 89% · 43 tests |

## 📫 联系我

- 📧 **bohan.zeng1@outlook.com**
- 📱 (+86) 19733143869
- 🌐 [github.com/zengbohan1](https://github.com/zengbohan1)
