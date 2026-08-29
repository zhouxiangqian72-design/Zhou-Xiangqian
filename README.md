# Awesome TRAE

> A curated list of awesome resources, tools, tutorials, projects, and community content for [TRAE](https://www.trae.cn/) — the AI-native development product family.

[English](./README.md) | [中文](./README_zh.md)

---

## Contents

- [Official Resources](#official-resources)
- [Product Family](#product-family)
- [Core Features](#core-features)
- [Working Environment](#working-environment)
- [Tools & Extensions](#tools--extensions)
- [Community Resources](#community-resources)
- [MCP Servers](#mcp-servers)
- [Skills](#skills)
- [Custom Agents](#custom-agents)
- [Tutorials & Guides](#tutorials--guides)
- [Templates & Boilerplates](#templates--boilerplates)
- [Learning Resources](#learning-resources)
- [Tips & Tricks](#tips--tricks)
- [Community](#community)
- [Contributing](#contributing)

---

## Official Resources

- [TRAE Official Website (CN)](https://www.trae.cn/) - Official Chinese website
- [TRAE Official Website (Global)](https://www.trae.ai/) - Official global website
- [TRAE Documentation (CN)](https://docs.trae.cn/) - Official Chinese documentation
- [TRAE Documentation (Global)](https://docs.trae.ai/) - Official global documentation
- [TRAE Blog](https://www.trae.ai/blog) - Latest updates, announcements, and feature releases
- [TRAE Forum (CN)](https://forum.trae.cn/) - Official Chinese community forum
- [TRAE Discord](https://discord.gg/trae) - Official community Discord server
- [TRAE Changelog](https://docs.trae.cn/ide_changelog) - Version history and release notes

## Product Family

TRAE is a product family brand for AI-native development and agent experiences.

### TraeCode

AI-native integrated development environment with deep coding assistance and agent workflows.

- [What is TraeCode?](https://docs.trae.cn/ide_what-is-trae-code) - Product overview
- [Download TraeCode](https://www.trae.cn/ide/download) - Get the IDE for your platform
- [Quick Start](https://docs.trae.cn/ide_get-started-with-trae) - Installation and setup guide
- [SOLO Mode Overview](https://docs.trae.cn/ide_solo-mode) - AI-driven full-process development mode

### TraeWork

AI-native workspace available as web, desktop, and mobile, with Work and Code dual modes.

- [TraeWork (Web)](https://www.trae.cn/work) - Access TraeWork online
- [TraeWork Launch Announcement](https://docs.trae.cn/ide_trae-solo-is-now-available) - Introduction to TraeWork client

### TraeCode CLI

Command-line AI coding agent for terminal-centric developers.

- [TraeCode CLI Documentation](https://docs.trae.cn/cli) - Official CLI docs
- [Plugin & CLI Hands-on Guide](https://forum.trae.cn/t/topic/176246) - Community guide for Plugin and CLI

### TraeCode Plugin

AI assistant plugin for VS Code and JetBrains IDEs.

- [TraeCode Plugin Page](https://www.trae.cn/plugin) - Installation and setup
- [Plugin AI Capabilities](https://docs.trae.ai/plugin/use-ai-capabilities) - Feature documentation

## Core Features

### AI Chat & Interaction

- [Sidebar & Inline Chat](https://docs.trae.cn/ide_chat) - Multiple AI conversation modes
- [Super Code Completion: CUE](https://docs.trae.cn/ide_cue) - Advanced AI-powered code completion

### Skills

- [Skills Overview](https://docs.trae.cn/ide_skills) - Reusable capability modules defined by `SKILL.md`
- [How to Write a Good Skill](https://docs.trae.cn/ide_best-practice-for-how-to-write-a-good-skill) - Best practices guide
- [Top 10 Recommended Skills for Development](https://docs.trae.cn/ide_top-10-recommended-skills-for-development-scenarios) - Curated skill recommendations

### Rules

- [Rules Overview](https://docs.trae.cn/ide_rules) - Global and project rules to guide AI behavior

### Memories

- [Memories Overview](https://docs.trae.cn/ide_memories) - Global and project-level memory system

### Commands

- [Slash Commands](https://docs.trae.cn/ide_slash-commands) - Quick shortcuts for repetitive tasks

### Agents

- [Agent Overview](https://docs.trae.cn/ide_agent-overview) - Built-in and custom agents
- [Built-in Agent: SOLO Agent](https://docs.trae.cn/ide_built-in-agent) - Full-process development agent
- [Create & Manage Custom Agents](https://docs.trae.cn/ide_agent) - Custom agent configuration
- [Subagents](https://docs.trae.cn/ide_subagents) - Sub-agent system with independent context
- [Auto-run & Security](https://docs.trae.cn/ide_auto-run-and-security) - Automated execution and safety

### Code Review

- [Agent-Powered Code Review](https://docs.trae.cn/ide_agent-powered-code-review) - AI-driven code review with visual diagrams

### Built-in Workflows

- [Plan, Spec & Goal](https://docs.trae.cn/ide_built-in-workflows) - Structured development workflows

### Models

- [Built-in & Custom Models](https://docs.trae.cn/ide_models) - Model configuration and management
- [Auto Mode](https://docs.trae.cn/ide_auto-mode) - Automatic model selection

### Context Management

- [Basic Context Usage](https://docs.trae.cn/ide_basic-usage-of-context) - Context fundamentals
- [# Reference Context](https://docs.trae.cn/ide_number-sign) - Using `#` to reference context
- [Codebase Indexing](https://docs.trae.cn/ide_codebase-indexing) - Workspace code indexing
- [Ignore Files](https://docs.trae.cn/ide_ignore-files) - Excluding files from AI context
- [Context Compaction](https://docs.trae.cn/ide_context-compaction) - Managing long conversations

### SOLO Mode

- [Multi-task Parallel](https://docs.trae.cn/ide_task-management) - Managing multiple tasks simultaneously
- [Tool Panel](https://docs.trae.cn/ide_tool-panel) - Editor, docs, terminal, and more
- [Figma Design to Code](https://docs.trae.cn/ide_figma-to-code) - Design restoration feature

### Other

- [Beta Features](https://docs.trae.cn/ide_beta-features) - Early access experimental features

## Working Environment

- [WSL Remote Development](https://docs.trae.cn/ide_wsl) - Windows Subsystem for Linux integration
- [SSH Remote Development](https://docs.trae.cn/ide_ssh-remote) - Connect to remote hosts via SSH
- [Source Code Management](https://docs.trae.cn/ide_source-control) - Git integration with AI-powered commits
- [Sandbox](https://docs.trae.cn/ide_sandbox) - Restricted execution environment for agent commands

### IDE Settings

- [IDE Settings Overview](https://docs.trae.cn/ide_ide-settings) - General configuration
- [Keyboard Shortcuts](https://docs.trae.cn/ide_keyboard-shortcuts) - Keybindings reference
- [Privacy Mode](https://docs.trae.cn/ide_privacy-mode) - Data privacy controls
- [Process Resource Explorer](https://docs.trae.cn/ide_resource-explorer) - Monitor resource usage

## Tools & Extensions

- [Browser Use](https://docs.trae.cn/ide_browser-use) - AI-driven browser automation
- [Computer Use](https://docs.trae.cn/ide_computer-use) - AI control of desktop applications
- [Extensions Management](https://docs.trae.cn/ide_manage-extensions) - Install, disable, and uninstall plugins
- [TRAE Editor for Unity](https://docs.trae.cn/ide_trae-editor-for-unity-tutorial) - Unity editor integration plugin

## Community Resources

### TRAE Community Organization

The official [trae-community](https://github.com/trae-community) organization on GitHub maintains a growing ecosystem of resources:

- [trae-community/awesome-trae](https://github.com/trae-community/awesome-trae) - Central resource index of the TRAE community
- [trae-community/trae-mcp](https://github.com/trae-community/trae-mcp) - Community-maintained MCP server collection
- [trae-community/trae-skills](https://github.com/trae-community/trae-skills) - Reusable Agent Skills for TRAE
- [trae-community/trae-agents](https://github.com/trae-community/trae-agents) - Custom agent configurations and design patterns
- [trae-community/trae-demos](https://github.com/trae-community/trae-demos) - Runnable demos and real-world case studies
- [trae-community/trae-templates](https://github.com/trae-community/trae-templates) - AI coding project templates
- [trae-community/trae-learning](https://github.com/trae-community/trae-learning) - Structured learning paths for AI-native development
- [trae-community/trae-co-creation-projects](https://github.com/trae-community/trae-co-creation-projects) - Collaborative AI coding projects
- [trae-community/trae-co-creation-demo-wall](https://github.com/trae-community/trae-co-creation-demo-wall) - Demo submission and showcase platform
- [trae-community/trae-discussions](https://github.com/trae-community/trae-discussions) - AI coding practice discussions
- [trae-community/trae-friends-events](https://github.com/trae-community/trae-friends-events) - TRAE Friends community event information
- [trae-community/.github](https://github.com/trae-community/.github) - Contribution guidelines and collaboration rules

### Community Projects

- [HighMark-31/TRAE-Agents](https://github.com/HighMark-31/TRAE-Agents) - Collection of 150+ specialized TRAE Agents for software development, frontend, backend, automation, UI/UX, SEO, and DevOps with direct installation links
- [HighMark-31/TRAE-Tips](https://github.com/HighMark-31/TRAE-Tips) - Advanced TRAE workflow & agent engineering. Winner of the 2025 TRAE Global Best Practice Challenge
- [HighMark-31/TRAE-Skills](https://github.com/HighMark-31/TRAE-Skills) - Catalog of 150+ skills covering frontend, backend, automation, UI/UX, SEO, and DevOps
- [jojomensah89/awesome-trae](https://github.com/jojomensah89/awesome-trae) - Community prompts, memories, and agent configurations
- [UrwLee/skill-trae-cn](https://github.com/UrwLee/skill-trae-cn) - Trae CN Skill for OpenClaw with IDE launch, project creation, and MCP configuration

## MCP Servers

Model Context Protocol (MCP) servers extend TRAE with external tools and data sources.

### Official MCP Tutorials

- [Popular MCP Servers Guide](https://docs.trae.cn/ide_most-used-mcp-servers-in-trae) - Top 10 commonly used MCP servers in TraeCode
- [MCP: Figma Design to Frontend Code](https://docs.trae.cn/ide_tutorial-mcp-figma) - Convert Figma designs to code
- [MCP: Web Automation Testing with Playwright](https://docs.trae.cn/ide_tutorial-mcp-playwright) - Automated browser testing
- [MCP: Trip Planning with Amap](https://docs.trae.cn/ide_tutorial-mcp-amap) - Location and route planning

### Community MCP Collections

- [trae-community/trae-mcp](https://github.com/trae-community/trae-mcp) - Community-maintained MCP server collection with tested configurations
  - CloudBase MCP - Tencent CloudBase integration (AI models, auth, databases, cloud functions, storage, CloudRun)

### MCP Learning Resources

- [Model Context Protocol Official Documentation](https://modelcontextprotocol.io/) - MCP standard specification
- [Anthropic MCP Announcement](https://www.anthropic.com/news/model-context-protocol) - Original announcement
- [MCP Quick Start Guide (Chinese)](https://github.com/liaokongVFX/MCP-Chinese-Getting-Started-Guide) - Chinese-language MCP tutorial

## Skills

Skills are reusable, scenario-specific capability modules defined by `SKILL.md` files.

### Official Skill Resources

- [Skills Documentation](https://docs.trae.cn/ide_skills) - Complete skill system overview
- [How to Write a Good Skill](https://docs.trae.cn/ide_best-practice-for-how-to-write-a-good-skill) - Best practices for skill design and iteration
- [Top 10 Recommended Skills](https://docs.trae.cn/ide_top-10-recommended-skills-for-development-scenarios) - Curated development scenario skills

### Community Skill Collections

- [trae-community/trae-skills](https://github.com/trae-community/trae-skills) - Community-maintained Agent Skills with `SKILL.md` definitions, scripts, templates, and examples
- [HighMark-31/TRAE-Skills](https://github.com/HighMark-31/TRAE-Skills) - 150+ specialized skills for development tasks

## Custom Agents

### Official Agent Resources

- [Custom Agents Ready for One-Click Import](https://docs.trae.cn/ide_custom-agents-ready-for-one-click-import) - Pre-built agents for UI design, frontend/backend architecture, API testing, and more
- [Create & Manage Custom Agents](https://docs.trae.cn/ide_agent) - Full agent configuration guide
- [Subagents Documentation](https://docs.trae.cn/ide_subagents) - Sub-agent system with independent context windows

### Community Agent Collections

- [trae-community/trae-agents](https://github.com/trae-community/trae-agents) - Community agent configurations with prompts, tools, and MCP recommendations
- [HighMark-31/TRAE-Agents](https://github.com/HighMark-31/TRAE-Agents) - 150+ agents with direct import links, covering C, C++, C#, Java, Kotlin, Python, Go, Rust, and more
- [HighMark-31/TRAE-Tips](https://github.com/HighMark-31/TRAE-Tips) - Advanced workflow engineering with custom agents, rule systems, and model selection strategy

## Tutorials & Guides

### Getting Started

- [Quick Start Guide](https://docs.trae.cn/ide_get-started-with-trae) - Installation, configuration, and first steps
- [What is TraeCode?](https://docs.trae.cn/ide_what-is-trae-code) - Product introduction and feature overview
- [Device Limit](https://docs.trae.cn/ide_device-limit) - Account device management

### Advanced Tutorials

- [TRAE Editor for Unity Tutorial](https://docs.trae.cn/ide_trae-editor-for-unity-tutorial) - AI integration in Unity development
- [Plugin & CLI Hands-on Guide](https://forum.trae.cn/t/topic/176246) - Practical guide for TraeCode Plugin and CLI

### Best Practices

- [How to Write a Good Skill](https://docs.trae.cn/ide_best-practice-for-how-to-write-a-good-skill) - Skill design standards and iteration process
- [Top 10 Recommended Skills for Development](https://docs.trae.cn/ide_top-10-recommended-skills-for-development-scenarios) - Scenario-based skill recommendations
- [Popular MCP Servers](https://docs.trae.cn/ide_most-used-mcp-servers-in-trae) - 10 commonly used MCP servers with use cases

### Troubleshooting

- [Get Logs or SessionID](https://docs.trae.cn/ide_get-logs-or-session-id) - Debugging and support information
- [Common Issues](https://docs.trae.cn/ide_troubleshoot-general-issues) - Known issues and solutions
- [Error Codes](https://docs.trae.cn/ide_error-codes) - Complete error code reference
- [Programming Language Issues](https://docs.trae.cn/ide_prigramming-languages-related) - Python and other language-specific troubleshooting

## Templates & Boilerplates

- [trae-community/trae-templates](https://github.com/trae-community/trae-templates) - AI coding project templates for quick starts
- [trae-community/trae-demos](https://github.com/trae-community/trae-demos) - Runnable demos and real-world case studies

## Learning Resources

- [trae-community/trae-learning](https://github.com/trae-community/trae-learning) - Structured learning paths for AI-native development with practice projects
- [TRAE Forum (CN)](https://forum.trae.cn/) - Community discussions, tips, and shared projects
- [TRAE Blog](https://www.trae.ai/blog) - Product announcements and feature deep-dives

## Tips & Tricks

- When working on a Markdown file, use keyboard shortcuts to preview the formatted output.
- If you suspect TRAE is not respecting your rules, ask it to "check your guidelines and revise your suggestion."
- Don't run chats indefinitely. Start fresh sessions periodically to avoid context degradation.
- Use the `#` symbol in the sidebar to reference code, files, and other context types for more accurate AI responses.
- Enable the sandbox for agent commands to prevent unauthorized file access.
- Use Plan mode for medium-sized features and Spec mode for complex system-level tasks.
- Keep an eye on the Problems panel when using AI coding tools.
- Have solid testing code in place — TRAE is smart but not AGI.

## Community

- [TRAE Forum (CN)](https://forum.trae.cn/) - Official Chinese community
- [TRAE Discord](https://discord.gg/trae) - Official Discord server
- [GitHub Discussions](https://github.com/trae-community/awesome-trae/discussions) - Community discussions
- [TRAE Co-creation Demo Wall](https://github.com/trae-community/trae-co-creation-demo-wall) - Showcase your TRAE-built projects
- [Contact Us](https://docs.trae.cn/ide_contact-us) - Official support channels

## Contributing

Contributions are welcome! Please read the [contribution guidelines](./CONTRIBUTING.md) before submitting a pull request.

### How to Add an Item

1. Make sure the item is related to TRAE and provides real value to the community
2. Fork this repository and create a new branch
3. Add your item following the format: `- [Name](link) - Description.`
4. Submit a pull request

### What Makes Something Awesome?

- High quality and well-maintained
- Useful to the TRAE community
- Clear documentation
- Active development (for projects)
- Positive community feedback

## License

[MIT](./LICENSE)
