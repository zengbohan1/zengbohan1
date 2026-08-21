# 开发提效小 tips

## AI 辅助开发

- 用 AI 编程工具（Zcode / Claude Code / Cursor / Codex）做代码审查和单元测试生成，不要只用来聊天
- 复杂逻辑先让 AI 出方案，自己校验后再动手，不要直接用 AI 的第一版输出
- AI 生成的代码一定要跑通测试再提交，AI 生成的注释和文档通常需要二次修改

## 调试

- 先复现再修，不要凭猜测改代码
- 用 Prometheus / LangSmith 先定位延迟分位和瓶颈，再看具体日志
- 故障注入是检验鲁棒性的好方法，不要只测正常路径

## 项目管理

- 每个指标都要有实测数据支撑，不要用"大概""左右"
- 开源 PR 要写清楚改了什么、为什么改、怎么验证
- 简历上的每个数字都要能被追问到实现细节

## 工具

- Git commit message 用英文简短描述，不写"面试"字样
- Markdown 表格比列表更适合结构化信息
- GitHub Actions 做自动化验证，不要手动跑测试

---

## Workflow 配置

基于 [Matt Pocock 技能库](https://github.com/mattpocock/skills) 的开发流程配置，详见 [zengbohan-skill](https://github.com/zengbohan1/zengbohan-skill)。

### 通用极简配置（90% 开发者适用）

```
Grill-With-Docs → /to-spec → /to-tickets → /implement → /to-code-review
```

### 进阶增强配置（复杂项目 / 注重代码质量）

在通用流程基础上，额外保留：

- `/improve-codebase-architecture` — 系统性扫描代码库，生成可视化架构报告
- `/diagnose` — 标准化六步调试闭环：复现 → 最小化 → 假设 → 仪器化 → 修复 → 回归