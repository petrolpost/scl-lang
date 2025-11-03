# SCL v1.0 — Slash Command Language  
**The First Formal, Reversible, Context-Aware Command Language for AI Agents**

[![SCL Certified](https://img.shields.io/badge/SCL-Certified-v1.0-success)]
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
[![Spec](https://img.shields.io/badge/Spec-v1.0-brightgreen)](spec.md)

> **发布日期**：2025年11月3日  
> **版本**：v1.0.0  
> **状态**：正式发布（Official Release）  
> **治理**：SCL Working Group

---

## 🌟 这是什么？

**SCL（Slash Command Language）** 是专为 **人机协同 AI Agent** 设计的 **结构化、可逆、上下文感知的命令语言标准**。

- `/draw cat --style anime` ↔ “画一只动漫猫”  
- 自动推荐、参数补全、执行复现、跨框架兼容  
- 支持 **LangChain、CLI、Web、AutoGen、LlamaIndex**

---

## 核心特性

| 特性 | 说明 |
|------|------|
| **形式化语法** | BNF + AST + JSON Schema 验证 |
| **双向可逆** | 自然语言 ⇄ SCL 指令 |
| **潜上下文绑定** | 实时感知对话、意图、历史 |
| **即插即用** | 5 分钟接入任意 Agent |
| **自扩展生态** | 动态指令注册 + Tag 智能聚类 |

---

## 快速开始

```bash
# 安装官方 CLI
pip install scl-lang

# 启动本地 Agent
scl agent start --model qwen2:7b

# 使用
/draw "astronaut cat" --style sci-fi --hd
# → 自动生成图像 + 自然语言解释
