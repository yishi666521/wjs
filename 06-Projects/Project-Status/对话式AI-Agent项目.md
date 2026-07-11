---
type: project
status: planning
created: 2026-07-11
tags:
  - type/project
  - topic/agent
  - topic/codex
  - topic/mcp
---

# 对话式 AI Agent 项目

> 3 个月目标：做出一个能对话、能调用工具的 AI Agent

## 项目状态
- **状态**: 🚧 规划中
- **开始日期**: 2026-07-11
- **目标日期**: 2026-10-11
- **核心方向**: 对话式 Agent（Tool Use + MCP）

## 项目概述
构建一个基于大语言模型的对话式 AI Agent，具备：
1. 自然语言对话能力
2. 工具调用（Function Calling）
3. 通过 MCP 协议连接外部服务
4. 可扩展的工具生态

## 技术栈（规划）
- **LLM**: OpenAI API / Claude API
- **Agent 框架**: Codex Agent / OpenAI Agents SDK / 自建
- **工具协议**: MCP (Model Context Protocol)
- **工具链**: Codex, Cursor, VS Code
- **知识源**: Obsidian 知识库

## 学习路线

### 阶段 1：理论基础（第 1-2 周）
- [ ] 理解 Agent 核心架构（ReAct / Plan-and-Execute）
- [ ] 学习 Function Calling 原理
- [ ] 了解 MCP 协议基础
- [ ] 研究 Codex Agent 模式

### 阶段 2：动手实验（第 3-4 周）
- [ ] 用 OpenAI API 实现简单的 Function Calling
- [ ] 搭建第一个 MCP Server
- [ ] 跑通 Codex Agent 的自定义工具
- [ ] 实现"对话 + 工具调用"的基础链路

### 阶段 3：功能完善（第 5-8 周）
- [ ] 扩展工具集（搜索、笔记、文件操作等）
- [ ] 连接 Obsidian 知识库作为数据源
- [ ] 实现记忆/上下文管理
- [ ] 优化对话体验

### 阶段 4：落地部署（第 9-12 周）
- [ ] 本地运行稳定版本
- [ ] 输出项目文档
- [ ] 制作抖音/小红书内容展示成果

## 里程碑
| 时间 | 里程碑 | 交付物 |
|------|--------|--------|
| 第 2 周 | 理论框架完成 | 研究笔记 5+ 篇 |
| 第 4 周 | 第一个 MVP 跑通 | 能对话 + 调用 1 个工具的 Agent |
| 第 8 周 | 功能完善 | 多工具 + MCP 集成 |
| 第 12 周 | 项目完成 | 完整的 Agent + 文档 + 内容 |

## 已完成事项
- [x] 确定知识库架构
- [x] 确定 AI Agent 为核心研究方向
- [x] 知识库中已建立 AI Agent 目录

## 下一步
- [ ] 开始阶段 1：研究 Agent 架构基础
- [ ] 阅读相关文档和教程
- [ ] 整理学习笔记到 04-Research/AI/Agent/

## 风险
- GitHub 同步受网络限制（可本地开发）
- 部分 API 需要科学上网访问

## 决策记录
| 日期 | 决策 | 理由 |
|------|------|------|
| 2026-07-11 | 对话式 Agent 方向 | 适合学习和内容创作，展示效果好 |

## 参考资料
- [OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling)
- [MCP 协议文档](https://modelcontextprotocol.io/)
- [Codex CLI](https://github.com/openai/codex)
- [Agent Hub](/Agent Hub.md)
- [MCP Hub](/MCP Hub.md)
