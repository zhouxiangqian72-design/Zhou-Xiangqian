# Awesome TRAE

> 精选的 [TRAE](https://www.trae.cn/) 资源列表 —— 包含工具、教程、项目和社区内容。TRAE 是 AI 原生开发产品家族品牌。

[English](./README.md) | [中文](./README_zh.md)

---

## 目录

- [官方资源](#官方资源)
- [产品家族](#产品家族)
- [核心功能](#核心功能)
- [工作环境](#工作环境)
- [工具与扩展](#工具与扩展)
- [社区资源](#社区资源)
- [MCP 服务器](#mcp-服务器)
- [技能（Skill）](#技能skill)
- [自定义智能体](#自定义智能体)
- [教程与指南](#教程与指南)
- [模板与脚手架](#模板与脚手架)
- [学习资源](#学习资源)
- [使用技巧](#使用技巧)
- [社区](#社区)
- [贡献指南](#贡献指南)

---

## 官方资源

- [TRAE 官网（中文）](https://www.trae.cn/) - 官方中文网站
- [TRAE 官网（国际）](https://www.trae.ai/) - 官方国际网站
- [TRAE 文档（中文）](https://docs.trae.cn/) - 官方中文文档
- [TRAE 文档（国际）](https://docs.trae.ai/) - 官方国际文档
- [TRAE 博客](https://www.trae.ai/blog) - 最新动态、公告和功能发布
- [TRAE 官方中文社区](https://forum.trae.cn/) - 官方中文社区论坛
- [TRAE Discord](https://discord.gg/trae) - 官方 Discord 社区
- [更新日志](https://docs.trae.cn/ide_changelog) - 版本历史和发布说明

## 产品家族

TRAE 是 AI 原生开发与智能体体验的产品家族品牌。

### TraeCode

AI 原生集成开发环境，深度融合 AI 编程能力和智能体工作流。

- [什么是 TraeCode？](https://docs.trae.cn/ide_what-is-trae-code) - 产品概览
- [下载 TraeCode](https://www.trae.cn/ide/download) - 获取适用于你平台的 IDE
- [快速开始](https://docs.trae.cn/ide_get-started-with-trae) - 安装和配置指南
- [SOLO 模式概览](https://docs.trae.cn/ide_solo-mode) - AI 主导的全流程开发模式

### TraeWork

AI 原生工作台，支持网页版、桌面版和移动版，设有 Work 与 Code 双模式。

- [TraeWork（网页版）](https://www.trae.cn/work) - 在线访问 TraeWork
- [TraeWork 客户端上线公告](https://docs.trae.cn/ide_trae-solo-is-now-available) - TraeWork 客户端介绍

### TraeCode CLI

面向终端开发者的命令行 AI 编程智能体。

- [TraeCode CLI 文档](https://docs.trae.cn/cli) - 官方 CLI 文档
- [Plugin 与 CLI 实战上手指南](https://forum.trae.cn/t/topic/176246) - 社区实战指南

### TraeCode Plugin

适用于 VS Code 和 JetBrains IDE 的 AI 助手插件。

- [TraeCode Plugin 页面](https://www.trae.cn/plugin) - 安装和配置
- [Plugin AI 能力](https://docs.trae.ai/plugin/use-ai-capabilities) - 功能文档

## 核心功能

### AI 对话与交互

- [侧边对话与行内对话](https://docs.trae.cn/ide_chat) - 多种 AI 对话模式
- [超级代码补全：CUE](https://docs.trae.cn/ide_cue) - 高级 AI 代码补全

### 技能（Skill）

- [技能概览](https://docs.trae.cn/ide_skills) - 通过 `SKILL.md` 定义的可复用能力模块
- [如何写好一个 Skill](https://docs.trae.cn/ide_best-practice-for-how-to-write-a-good-skill) - 最佳实践指南
- [研发场景十大热门 Skill 推荐](https://docs.trae.cn/ide_top-10-recommended-skills-for-development-scenarios) - 精选技能推荐

### 规则（Rule）

- [规则概览](https://docs.trae.cn/ide_rules) - 全局规则和项目规则，规范 AI 行为

### 记忆（Memory）

- [记忆概览](https://docs.trae.cn/ide_memories) - 全局记忆和项目级记忆系统

### 命令（Command）

- [斜杠命令](https://docs.trae.cn/ide_slash-commands) - 快速执行重复性任务的快捷方式

### 智能体（Agent）

- [智能体概览](https://docs.trae.cn/ide_agent-overview) - 内置智能体和自定义智能体
- [内置智能体：SOLO Agent](https://docs.trae.cn/ide_built-in-agent) - 全流程开发智能体
- [创建并管理自定义智能体](https://docs.trae.cn/ide_agent) - 自定义智能体配置
- [子智能体（Subagent）](https://docs.trae.cn/ide_subagents) - 拥有独立上下文窗口的子智能体系统
- [自动运行与安全性](https://docs.trae.cn/ide_auto-run-and-security) - 自动化执行和安全策略

### 智能体审查

- [智能代码审查](https://docs.trae.cn/ide_agent-powered-code-review) - AI 驱动的代码审查，支持可视化图表

### 内置工作流

- [Plan、Spec 与 Goal](https://docs.trae.cn/ide_built-in-workflows) - 结构化开发工作流

### 模型

- [内置模型与自定义模型](https://docs.trae.cn/ide_models) - 模型配置和管理
- [Auto 模式](https://docs.trae.cn/ide_auto-mode) - 自动模型选择

### 上下文管理

- [基础用法](https://docs.trae.cn/ide_basic-usage-of-context) - 上下文基础
- [通过 # 符号引用上下文](https://docs.trae.cn/ide_number-sign) - 使用 `#` 引用上下文
- [工作区代码索引](https://docs.trae.cn/ide_codebase-indexing) - 工作区代码索引
- [忽略文件](https://docs.trae.cn/ide_ignore-files) - 排除文件不进入 AI 上下文
- [上下文压缩](https://docs.trae.cn/ide_context-compaction) - 管理长对话上下文

### SOLO 模式

- [多任务并行](https://docs.trae.cn/ide_task-management) - 同时管理多个任务
- [工具面板](https://docs.trae.cn/ide_tool-panel) - 编辑器、文档、终端等工具
- [Figma 设计还原](https://docs.trae.cn/ide_figma-to-code) - 设计稿转代码功能

### 其他

- [Beta 功能](https://docs.trae.cn/ide_beta-features) - 前沿探索功能

## 工作环境

- [WSL 远程开发](https://docs.trae.cn/ide_wsl) - Windows Subsystem for Linux 集成
- [SSH 远程开发](https://docs.trae.cn/ide_ssh-remote) - 通过 SSH 连接远程主机
- [源代码管理](https://docs.trae.cn/ide_source-control) - Git 集成与 AI 辅助提交
- [沙箱](https://docs.trae.cn/ide_sandbox) - 智能体命令的受限执行环境

### IDE 设置

- [IDE 设置总览](https://docs.trae.cn/ide_ide-settings) - 通用配置
- [快捷键](https://docs.trae.cn/ide_keyboard-shortcuts) - 快捷键参考
- [隐私模式](https://docs.trae.cn/ide_privacy-mode) - 数据隐私控制
- [进程资源管理器](https://docs.trae.cn/ide_resource-explorer) - 资源使用监控

## 工具与扩展

- [浏览器控制（Browser Use）](https://docs.trae.cn/ide_browser-use) - AI 驱动的浏览器自动化
- [电脑控制（Computer Use）](https://docs.trae.cn/ide_computer-use) - AI 操控桌面应用
- [插件管理](https://docs.trae.cn/ide_manage-extensions) - 安装、禁用和卸载插件
- [TRAE Editor for Unity](https://docs.trae.cn/ide_trae-editor-for-unity-tutorial) - Unity 编辑器集成插件

## 社区资源

### TRAE 社区组织

官方 [trae-community](https://github.com/trae-community) 组织在 GitHub 上维护着不断增长的资源生态：

- [trae-community/awesome-trae](https://github.com/trae-community/awesome-trae) - TRAE 社区资源总索引
- [trae-community/trae-mcp](https://github.com/trae-community/trae-mcp) - 社区维护的 MCP 服务器集合
- [trae-community/trae-skills](https://github.com/trae-community/trae-skills) - 可复用的 Agent 技能
- [trae-community/trae-agents](https://github.com/trae-community/trae-agents) - 自定义智能体配置和设计模式
- [trae-community/trae-demos](https://github.com/trae-community/trae-demos) - 可运行的实践案例
- [trae-community/trae-templates](https://github.com/trae-community/trae-templates) - AI 编程项目模板
- [trae-community/trae-learning](https://github.com/trae-community/trae-learning) - AI 原生开发学习路径
- [trae-community/trae-co-creation-projects](https://github.com/trae-community/trae-co-creation-projects) - 多人协作 AI 编程共创项目
- [trae-community/trae-co-creation-demo-wall](https://github.com/trae-community/trae-co-creation-demo-wall) - 作品提交与展示平台
- [trae-community/trae-discussions](https://github.com/trae-community/trae-discussions) - AI 编程实践讨论区
- [trae-community/trae-friends-events](https://github.com/trae-community/trae-friends-events) - TRAE Friends 社区活动信息
- [trae-community/.github](https://github.com/trae-community/.github) - 社区协作规范与贡献约定

### 社区项目

- [HighMark-31/TRAE-Agents](https://github.com/HighMark-31/TRAE-Agents) - 150+ 专用 TRAE 智能体集合，覆盖前端、后端、自动化、UI/UX、SEO 和 DevOps，含直接安装链接
- [HighMark-31/TRAE-Tips](https://github.com/HighMark-31/TRAE-Tips) - 高级 TRAE 工作流与智能体工程实践。2025 TRAE 全球最佳实践挑战赛获奖作品
- [HighMark-31/TRAE-Skills](https://github.com/HighMark-31/TRAE-Skills) - 150+ 技能目录，覆盖前端、后端、自动化、UI/UX、SEO 和 DevOps
- [jojomensah89/awesome-trae](https://github.com/jojomensah89/awesome-trae) - 社区提示词、记忆和智能体配置
- [UrwLee/skill-trae-cn](https://github.com/UrwLee/skill-trae-cn) - OpenClaw 的 Trae CN 集成技能，支持 IDE 启动、项目创建和 MCP 配置

## MCP 服务器

模型上下文协议（MCP）服务器通过外部工具和数据源扩展 TRAE 的能力。

### 官方 MCP 教程

- [热门 MCP Server 详解](https://docs.trae.cn/ide_most-used-mcp-servers-in-trae) - TraeCode 中常用的 10 个 MCP 服务器
- [MCP 教程：Figma 设计稿转前端代码](https://docs.trae.cn/ide_tutorial-mcp-figma) - 将 Figma 设计稿转化为代码
- [MCP 教程：网页自动化测试](https://docs.trae.cn/ide_tutorial-mcp-playwright) - 使用 Playwright 实现自动化浏览器测试
- [MCP 教程：使用高德地图规划行程](https://docs.trae.cn/ide_tutorial-mcp-amap) - 位置和路线规划

### 社区 MCP 集合

- [trae-community/trae-mcp](https://github.com/trae-community/trae-mcp) - 社区维护的 MCP 服务器集合，含测试配置
  - CloudBase MCP - 腾讯云 CloudBase 集成（AI 模型、认证、数据库、云函数、存储、CloudRun）

### MCP 学习资源

- [Model Context Protocol 官方文档](https://modelcontextprotocol.io/) - MCP 标准规范
- [Anthropic MCP 公告](https://www.anthropic.com/news/model-context-protocol) - 原始发布公告
- [MCP 编程快速入门指南（中文）](https://github.com/liaokongVFX/MCP-Chinese-Getting-Started-Guide) - 中文 MCP 教程

## 技能（Skill）

技能是通过 `SKILL.md` 文件定义的可复用、场景化的能力模块。

### 官方技能资源

- [技能文档](https://docs.trae.cn/ide_skills) - 完整的技能系统概览
- [如何写好一个 Skill](https://docs.trae.cn/ide_best-practice-for-how-to-write-a-good-skill) - 技能设计与迭代最佳实践
- [研发场景十大热门 Skill 推荐](https://docs.trae.cn/ide_top-10-recommended-skills-for-development-scenarios) - 按场景推荐技能

### 社区技能集合

- [trae-community/trae-skills](https://github.com/trae-community/trae-skills) - 社区维护的 Agent 技能，含 `SKILL.md` 定义、脚本、模板和示例
- [HighMark-31/TRAE-Skills](https://github.com/HighMark-31/TRAE-Skills) - 150+ 专用开发技能目录

## 自定义智能体

### 官方智能体资源

- [支持一键导入的自定义智能体](https://docs.trae.cn/ide_custom-agents-ready-for-one-click-import) - 预构建智能体（UI 设计师、前端架构师、后端架构师、API 测试工程师等）
- [创建并管理自定义智能体](https://docs.trae.cn/ide_agent) - 完整的智能体配置指南
- [子智能体文档](https://docs.trae.cn/ide_subagents) - 拥有独立上下文窗口的子智能体系统

### 社区智能体集合

- [trae-community/trae-agents](https://github.com/trae-community/trae-agents) - 社区智能体配置，含提示词、工具和 MCP 推荐
- [HighMark-31/TRAE-Agents](https://github.com/HighMark-31/TRAE-Agents) - 150+ 智能体，含直接导入链接，覆盖 C、C++、C#、Java、Kotlin、Python、Go、Rust 等
- [HighMark-31/TRAE-Tips](https://github.com/HighMark-31/TRAE-Tips) - 高级工作流工程实践，含自定义智能体、规则系统和模型选择策略

## 教程与指南

### 入门

- [快速开始](https://docs.trae.cn/ide_get-started-with-trae) - 安装、配置和上手操作
- [什么是 TraeCode？](https://docs.trae.cn/ide_what-is-trae-code) - 产品介绍和功能概览
- [设备数量限制](https://docs.trae.cn/ide_device-limit) - 账号设备管理

### 进阶教程

- [TRAE Editor for Unity 教程](https://docs.trae.cn/ide_trae-editor-for-unity-tutorial) - Unity 开发中的 AI 集成
- [Plugin 与 CLI 实战上手指南](https://forum.trae.cn/t/topic/176246) - TraeCode Plugin 和 CLI 的实战指南

### 最佳实践

- [如何写好一个 Skill](https://docs.trae.cn/ide_best-practice-for-how-to-write-a-good-skill) - 技能设计标准和迭代流程
- [研发场景十大热门 Skill 推荐](https://docs.trae.cn/ide_top-10-recommended-skills-for-development-scenarios) - 按场景推荐技能
- [热门 MCP Server 详解](https://docs.trae.cn/ide_most-used-mcp-servers-in-trae) - 10 个常用 MCP 服务器及使用场景

### 问题排查

- [获取日志或 SessionID](https://docs.trae.cn/ide_get-logs-or-session-id) - 调试和支持信息
- [常见问题](https://docs.trae.cn/ide_troubleshoot-general-issues) - 已知问题和解决方案
- [错误码](https://docs.trae.cn/ide_error-codes) - 完整错误码参考
- [编程语言相关问题](https://docs.trae.cn/ide_prigramming-languages-related) - Python 等语言特定问题排查

## 模板与脚手架

- [trae-community/trae-templates](https://github.com/trae-community/trae-templates) - AI 编程项目模板，快速启动
- [trae-community/trae-demos](https://github.com/trae-community/trae-demos) - 可运行的实践案例和真实场景

## 学习资源

- [trae-community/trae-learning](https://github.com/trae-community/trae-learning) - AI 原生开发结构化学习路径，含实践项目
- [TRAE 官方中文社区](https://forum.trae.cn/) - 社区讨论、技巧分享和项目展示
- [TRAE 博客](https://www.trae.ai/blog) - 产品公告和功能深度解析

## 使用技巧

- 处理 Markdown 文件时，使用快捷键预览格式化输出。
- 如果感觉 TRAE 没有遵守你的规则，可以提示它"检查你的准则并修改建议"。
- 不要让对话无限运行。定期开启新会话以避免上下文退化。
- 在侧边对话中使用 `#` 符号引用代码、文件等上下文类型，让 AI 响应更准确。
- 为智能体命令启用沙箱，防止未经授权的文件访问。
- 中小型功能开发使用 Plan 模式，复杂系统任务使用 Spec 模式。
- 使用 AI 编程工具时留意 Problems 面板。
- 确保有完善的测试代码 — TRAE 很聪明，但不是 AGI。

## 社区

- [TRAE 官方中文社区](https://forum.trae.cn/) - 官方中文社区
- [TRAE Discord](https://discord.gg/trae) - 官方 Discord 服务器
- [GitHub Discussions](https://github.com/trae-community/awesome-trae/discussions) - 社区讨论
- [TRAE 共创作品墙](https://github.com/trae-community/trae-co-creation-demo-wall) - 展示你用 TRAE 构建的项目
- [联系我们](https://docs.trae.cn/ide_contact-us) - 官方支持渠道

## 贡献指南

欢迎贡献！请在提交 Pull Request 之前阅读 [贡献指南](./CONTRIBUTING.md)。

### 如何添加项目

1. 确保项目与 TRAE 相关，并为社区提供真正的价值
2. Fork 本仓库并创建新分支
3. 按格式添加项目：`- [项目名](链接) - 简短描述。`
4. 提交 Pull Request

## 许可证

[MIT](./LICENSE)
