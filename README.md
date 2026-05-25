<div align="center">

<img src="assets/logo.png" width="80" height="80" alt="One Terminal Logo" style="border-radius: 16px;" />

# One Terminal

### Multimodal AI Production Terminal

**One window. All productivity.**

Text, code, images, video — configure once, produce instantly.

[![Download](https://img.shields.io/badge/Download-macOS_DMG-F59E0B?style=for-the-badge&logo=apple&logoColor=white)](https://oterminal-web.zeabur.app/api/download)
[![Website](https://img.shields.io/badge/Website-oterminal--web.zeabur.app-18181B?style=for-the-badge&logo=safari&logoColor=white)](https://oterminal-web.zeabur.app)
[![Community](https://img.shields.io/badge/Community-Join_Us-10B981?style=for-the-badge&logo=discourse&logoColor=white)](https://oterminal-web.zeabur.app/community)

---

[English](#features) · [中文](#功能特性)

</div>

<br />

<div align="center">

<img src="assets/screenshots/hero.png" width="800" alt="One Terminal — Multimodal AI Production Terminal" />

</div>

<br />

## What is One Terminal?

One Terminal is a **native macOS desktop app** built for people who want AI to **actually produce results** — not just answer questions.

Give it a goal. It reads your codebase, writes code, runs commands, searches the web, generates images, and delivers finished work. Then it **remembers what it learned** and shares knowledge with your team.

**Three pillars:**

> 🎯 **Produce** — Multimodal AI agent that handles text, code, image, and video tasks autonomously
>
> 👥 **Connect** — Built-in community, contacts, and encrypted real-time messaging
>
> 🧠 **Learn** — Every task makes both you and the AI smarter through Learning Trail

<br />

## Features

### 🎯 Multimodal Production

One person does the work of four. Text, code, image, video — one production line.

<table>
<tr>
<td width="25%" align="center"><strong>✍️ Text</strong><br/><sub>Copywriting, docs, reports — from idea to final draft</sub></td>
<td width="25%" align="center"><strong>💻 Code</strong><br/><sub>Read/write code, run commands, debug — full-stack dev</sub></td>
<td width="25%" align="center"><strong>🖼 Image</strong><br/><sub>AI generation, screenshot analysis, design assets</sub></td>
<td width="25%" align="center"><strong>🎬 Video</strong><br/><sub>Scripts, subtitles, editing automation</sub></td>
</tr>
</table>

**How it works:**
- You describe a task → the Agent **plans, executes, and delivers**
- 30+ built-in tools: file I/O, shell, web search, image analysis, browser automation
- Workspace-aware: understands your project structure, files, and dependencies
- Multi-agent delegation: specialist agents work in parallel on complex tasks

<div align="center">

<img src="assets/screenshots/agent.png" width="800" alt="Agent Mode — Autonomous task execution" />

<sub><strong>Agent Mode</strong> — Autonomous execution: read files, write code, run commands, plan & track</sub>

</div>

<br />

---

### 👥 Social — Community & Encrypted Messaging

One Terminal isn't a lonely tool. It has people inside.

- **Community** — Share skills, post workflows, discover plugins, upvote useful content
- **Contacts** — Add friends, send direct messages in real-time
- **Ephemeral Messaging** — Messages are deleted from the server the moment they're delivered. No logs, no history on our end
- **Enterprise Sync** — Connect [Zero Terminal](https://oterminal-web.zeabur.app) for CEO → team task dispatch with real-time results

<div align="center">

<img src="assets/screenshots/contacts.png" width="380" alt="Contacts & Encrypted Messaging" />
&nbsp;&nbsp;
<img src="assets/screenshots/community.png" width="380" alt="Community" />

<sub><strong>Left:</strong> Real-time encrypted messaging &nbsp;|&nbsp; <strong>Right:</strong> Community — share skills & workflows</sub>

</div>

<br />

---

### 🧠 Learning Trail — You Get Smarter Too

Most AI tools make you **dependent**. One Terminal makes you **stronger**.

Every task the Agent performs generates a trail of knowledge — and it's yours to keep.

- **📖 Learning Trail** — Every theory, data source, and reference the Agent uses — auto-tagged, auto-recorded. Not search results — a traceable knowledge path
- **📓 Study Notes** — Pin valuable references with one click, add your understanding. What the Agent teaches you stays forever
- **🧠 Compound Cognition** — Every task teaches you something new. Your Agent doesn't just do things — it helps you build a knowledge system

<div align="center">

<img src="assets/screenshots/learning-trail.png" width="800" alt="Learning Trail — Cognitive Growth Journal" />

</div>

<br />

---

### 🔒 Privacy First

- All data stored **locally on your machine**
- Bring your own API keys — no middleman, no subscription
- No cloud dependency, no tracking, no telemetry
- Messages: E2E encrypted, deleted on delivery

<br />

## Architecture

```
User Goal → Orchestrator → Agent Loop → Tool Execution → Delivered Result
                ↑                              ↓
          Context Management          30+ Tools (parallel + serial)
          (auto-compaction)           (hooks, sandboxing, git tracking)
```

Built with **Rust** (Tauri v2) + **React** + **SQLite**. Key internals:

- **4-phase tool pipeline**: pre-process → parallel readonly → serial write → multi-agent delegation
- **AST-aware editing**: tree-sitter fallback for Rust, JS/TS, Python, Go
- **Git integration**: auto-checkpoint per iteration, task completion tags
- **LSP integration**: multi-language diagnostics and code intelligence
- **Context management**: automatic compaction with model-specific thresholds

<br />

## Pricing

| | Individual | Enterprise |
|---|---|---|
| **Price** | **$0** — Free forever | Custom pricing |
| Multimodal production | ✅ Text, code, image, video | ✅ |
| Auto-learning knowledge vault | ✅ | ✅ |
| Community & plugin sharing | ✅ | ✅ |
| Encrypted real-time messaging | ✅ | ✅ |
| Zero Terminal admin dashboard | — | ✅ |
| CEO → team task dispatch | — | ✅ |
| Team output tracking & reports | — | ✅ |

<br />

## Download

<div align="center">

### [⬇️ Download for macOS (Apple Silicon)](https://oterminal-web.zeabur.app/api/download)

macOS 12+ · Apple Silicon (M1/M2/M3/M4) · ~15MB

</div>

<br />

## Community

- 💬 [**Discussions**](https://github.com/8868derek/oneterminal/discussions) — Ask questions, share workflows, request features
- 🐛 [**Issues**](https://github.com/8868derek/oneterminal/issues) — Report bugs
- 🌐 [**Web Community**](https://oterminal-web.zeabur.app/community) — Share skills, discover plugins

<br />

## License

One Terminal is **proprietary software**. Free for individual use. See [LICENSE](LICENSE) for details.

<br />

---

<div align="center">

<sub>© 2025 Beijing Ape Tail Technology Co., Ltd. All rights reserved.</sub>

<br />

**[Website](https://oterminal-web.zeabur.app)** · **[Download](https://oterminal-web.zeabur.app/api/download)** · **[Community](https://oterminal-web.zeabur.app/community)**

</div>

---

<br />

<a name="功能特性"></a>

## 中文介绍

### One Terminal · 小莓 🍓

**一个窗口，全部生产力。**

不是又一个 AI 工具，而是你的**多模态 AI 生产终端**。

文字、代码、图片、视频 — 配好即用，协同即产出。

### 三大核心

#### 🎯 多模态生产

| 模态 | 描述 |
|------|------|
| ✍️ **文字** | 文案撰写、文档生成、报告输出 — 从创意到终稿一步完成 |
| 💻 **代码** | 读写代码、运行命令、调试修复 — 全栈开发即刻交付 |
| 🖼 **图片** | AI 生成、截图分析、设计素材 — 视觉内容随需而生 |
| 🎬 **视频** | 脚本、字幕、剪辑自动化 — 多媒体生产全链覆盖 |

#### 👥 社交

- **社区** — 分享技能、交流工作流、发现社区插件
- **联系人** — 添加好友，实时消息通讯
- **阅后即焚** — 消息送达即从服务器删除，不留存
- **企业协同** — 连接 Zero Terminal，CEO 下发任务 → 小莓自动执行 → 结果实时回传

#### 🧠 学习

- **来时路 (Learning Trail)** — Agent 用到的理论、数据源、延伸阅读，自动标记、自动记录
- **学习笔记** — 一键收藏有价值的参考，加上你的理解。Agent 教你的不会忘
- **认知复利** — 每次任务都让你多懂一点。不是效率工具，是知识伙伴

### 定价

- **个人版**：¥0，永久免费。自带 API Key，无订阅，无追踪，数据不出本地
- **企业版**：按需定价。连接 Zero Terminal 获得团队协同、任务派发、产出追踪

### [⬇️ 下载 macOS 版](https://oterminal-web.zeabur.app/api/download)