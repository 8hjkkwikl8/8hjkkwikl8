# AI Application / RAG Engineering

你好，我关注可追溯、可复现、边界明确的 AI 应用工程，主要使用 Python、FastAPI 与 SQLite。

I build traceable and reproducible AI applications with explicit safety boundaries, focusing on RAG, LLM evaluation, guarded NL2SQL, and multi-agent systems.

## 原创项目 / Selected Projects

### [AI Engineering Portfolio](https://github.com/8hjkkwikl8/ai-portfolio)

一个包含三个可运行项目的 monorepo，默认离线演示，无需 API Key：

- **InsightRAG**：中文知识库混合检索、证据回放、逐句引用校验与金标评测。
- **PromptLens**：不可变提示词版本、可复现实验、失败隔离与 HTML 对比报告。
- **DataChat BI**：自然语言到只读 SQL 的多层守护，以及不记录参数原文的本地查询审计。

包含 96 项自动化测试与 Ubuntu / Windows CI。演示指标只用于验证工程链路，不代表生产效果。

### [DeepScope](https://github.com/8hjkkwikl8/deepscope)

多智能体深度研究助手，覆盖规划、研究、批判与写作；提供 SSE 实时事件流、事件去重和来源编号引用校验。

## 工程原则 / Engineering Principles

把模型输出当作不可信输入；保留证据、数据哈希与运行清单；同时展示指标口径和限制。优先交付可以运行、可以测试、也可以被反驳的项目，而不是截图或概念稿。

Treat model output as untrusted input. Preserve evidence and run manifests, state metric limitations clearly, and prefer runnable, testable, refutable projects over screenshots.
