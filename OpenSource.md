# 🌱 开源贡献

## Spring AI Alibaba

[Spring AI Alibaba](https://github.com/alibaba/spring-ai-alibaba) — 面向 Java 开发者的 Agentic AI 框架。

### PR #4902 — Agentic RAG 示例完善

- **改动**：
  - 新增分类、检索、回答、质量检查四节点，补全 Agentic RAG 示例的质量闭环
  - 补充最多两次检索重试机制
  - 完成 Studio 集成
  - 添加内存向量库支持
  - 完成 JDK 17 下 Maven 构建验证
- **链接**：https://github.com/alibaba/spring-ai-alibaba/pull/4902

### PR #4904 — graph 模块测试断言修复

- **改动**：
  - 定位 graph 模块字节数组往返测试断言与序列化器行为不一致的问题
  - 修正测试断言
  - 修复后模块测试 464 项通过
  - 形成缺陷定位 → 回归验证的完整闭环
- **链接**：https://github.com/alibaba/spring-ai-alibaba/pull/4904

---

## 自研项目

| 项目 | 链接 | 说明 |
|------|------|------|
| enterprise-rag-qa | https://github.com/zengbohan1/enterprise-rag-qa | 企业知识库 RAG 问答系统 |
| sentiment-analysis-agents | https://github.com/zengbohan1/sentiment-analysis-agents | 多智能体舆情分析系统 |
| agent-orchestration-framework | https://github.com/zengbohan1/agent-orchestration-framework | 轻量 Agent 编排框架 |