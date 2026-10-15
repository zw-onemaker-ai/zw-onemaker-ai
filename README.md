<div align="center">

# 👋 zw-onemaker-ai

**AI 应用工程师 · AI 工程化交付系统**

用多 Agent 工程管线，把产品交付跑成标准化流水线：需求 → 设计 → 代码 → 验证 → 上线

<sub>Building reliable multi-agent pipelines — so every step of AI collaboration can be trusted.</sub>

</div>

---

## 🛡️ 精选项目

### [x402-seller-starter](https://github.com/zw-onemaker-ai/x402-seller-starter) — 面向 AI Agent 的付费 API 生产级骨架

> **把一次真实上线踩过的坑，做成了开箱闸门** — Express + x402 · Base USDC 按次收款 · 预检脚本 · 发现层入册清单

[![CI](https://github.com/zw-onemaker-ai/x402-seller-starter/actions/workflows/ci.yml/badge.svg)](https://github.com/zw-onemaker-ai/x402-seller-starter/actions/workflows/ci.yml)
![License](https://img.shields.io/badge/license-MIT-green)

- 💰 **收款引擎** — x402 协议：账单即价签，机器买家直接付费（Base 主网 USDC）
- 🚪 **预检闸门** — 五类静默杀手开箱即检：账单截断 / 字段超长 / HEAD 泄漏 / 缺输出 schema
- 📇 **发现层清单** — Agent 与目录实际会看的五个入口，照着入册
- 📖 **十条实战笔记** — 每一条都对应仓库里的一道闸门

### [OneMaker Pipeline](https://github.com/zw-onemaker-ai/onemaker-pipeline) — AI 工程化交付系统

> **把完整工程团队的工序编进一条多 Agent 管线** — 14 角色 · 质量门禁 · EXIT_CODE 指纹 · 定向回环 · 三层记忆

[![CI](https://github.com/zw-onemaker-ai/onemaker-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/zw-onemaker-ai/onemaker-pipeline/actions/workflows/ci.yml)
![License](https://img.shields.io/badge/license-MIT-green)

- 🏭 **14 角色管线** — 需求 → 设计 → 开发 → 验证 → 上线，角色隔离、按需加载
- 🚪 **三道验证闸门** — 文件存在 · EXIT 指纹 · 脱敏检查，不通过不路由
- 🔁 **定向回环** — 按问题类型回退到对应角色（Bug→开发 / 架构→产品 / 安全→安全）
- 🧠 **三层记忆** — 硬上限 + 自动裁剪 + 快照保险
- 📦 **3 个零依赖演示** — 5 分钟看完整条管线怎么跑

### [AgentGate](https://github.com/zw-onemaker-ai/agent_gate) — 多 Agent 管线可靠性操作系统

> **「Agent 管编，闸门管信」** — 主流多 Agent 框架默认「Agent 产出可信」；AgentGate 默认「不可信，验证过才算」。

![CI](https://github.com/zw-onemaker-ai/agent_gate/actions/workflows/ci.yml/badge.svg)
![License](https://img.shields.io/badge/license-MIT-green)
![Tests](https://img.shields.io/badge/tests-127-brightgreen)

- 🚪 **验证拦截** — 三道闸门：文件存在性 / EXIT 指纹 / 交叉验证，不合格产出不放行
- 🔁 **定向回环** — 按错误类型精确回环到对应 Agent 修复，而不是盲目重启管线
- 🧠 **双脑架构** — 设计脑（LLM）生成管线配置，执行脑（纯规则引擎）执行验证
- 🩺 **自愈** — Pipeline Doctor 自动诊断卡死管线；人工闸门兜底不可分类错误
- 📦 **零依赖** — 纯 Python 标准库，直连 OpenAI 兼容端点 + Ollama

📖 [技术文章：为什么验证层必须存在](https://github.com/zw-onemaker-ai/agent_gate/blob/master/docs/articles/01_zhihu_5layer_reliability.md) · 💬 [Discussions](https://github.com/zw-onemaker-ai/agent_gate/discussions)

## 🧰 技能栈

`Python` · `LLM 应用工程` · `多 Agent 编排` · `提示词工程` · `可靠性工程` · `FastAPI` · `React` · `Docker`

## 📫 联系

- 💬 [AgentGate Discussions](https://github.com/zw-onemaker-ai/agent_gate/discussions)
- 🌐 更多项目陆续开源中

