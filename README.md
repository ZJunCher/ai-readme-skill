# AI README Skill

`ai-readme` 是一个用于生成项目规则文档的 OpenClaw Skill，适合在已有代码项目中快速生成面向 AI Agent 和开发者共用的项目说明与规则文件。

## 功能简介

该 Skill 会扫描项目结构、依赖文件和核心源码，自动生成：

- `AGENTS.md`：项目入口说明，供 AI Agent 快速理解项目；
- `.cursor/rules/ai-readme/RULE.mdc`：Cursor 项目规则入口与导航；
- `generated/`：由 AI 根据代码扫描生成的技术事实文档；
- `manual/`：预留给人工补充业务知识和历史经验的模板。

## 适用场景

- 给已有项目补充 AI 可读的项目规则文档；
- 为 Cursor 等 AI Coding 工具初始化项目上下文；
- 帮助 AI 更快理解项目结构、技术栈、开发命令和核心流程。

## 使用方式

将 `SKILL.md` 作为 OpenClaw Skill 使用。当需要为项目生成 AI README / 项目规则文档时，触发该 Skill 即可。
