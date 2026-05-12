# AI README Skill

`ai-readme` 是一个面向 Cursor 等 AI Coding 工具的项目规则提示词，用于在代码项目中生成面向 AI 和开发者共用的项目说明与规则文档。

## 功能简介

该 Skill 会引导 AI 扫描项目结构、依赖文件和核心源码，并生成：

- `AGENTS.md`：项目入口说明，帮助 AI 快速理解项目；
- `.cursor/rules/ai-readme/RULE.mdc`：Cursor 项目规则入口与导航；
- `generated/`：由 AI 根据代码扫描生成的技术事实文档；
- `manual/`：预留给开发者补充业务知识和历史经验的模板。

## 适用场景

- 在 Cursor 等 AI Coding 工具中初始化项目规则；
- 给已有项目补充 AI 可读的项目上下文；
- 帮助 AI 更快理解项目结构、技术栈、开发命令和核心流程；
- 让团队沉淀可持续维护的项目规则文档。

## 使用方式

将 `SKILL.md` 中的规则内容添加到 Cursor 等 AI Coding 工具的项目规则中，然后在目标项目中触发 `ai-readme` 相关任务，即可生成项目说明与规则文档。
