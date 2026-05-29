<div align="center">

<img src="assets/logo.png" width="80" height="80" alt="One Terminal Logo" style="border-radius: 16px;" />

# One Terminal · 小莓 🍓

### 多模态 AI 生产终端

**一个窗口，全部生产力。**

文字、代码、图片、视频 — 配好即用，协同即产出。

[![Download](https://img.shields.io/badge/下载-macOS_安装包-F59E0B?style=for-the-badge&logo=apple&logoColor=white)](https://oterminal-web.zeabur.app/api/download)
[![Website](https://img.shields.io/badge/官方网站-oterminal--web.zeabur.app-18181B?style=for-the-badge&logo=safari&logoColor=white)](https://oterminal-web.zeabur.app)
[![Community](https://img.shields.io/badge/社区空间-加入我们-10B981?style=for-the-badge&logo=discourse&logoColor=white)](https://oterminal-web.zeabur.app/community)

---

[English](README.md) · **简体中文**

</div>

<br />

<div align="center">

<img src="assets/screenshots/hero.png" width="800" alt="One Terminal — 多模态 AI 生产终端" />

</div>

<br />

## 什么是 One Terminal？

One Terminal（小莓）是一个**原生 macOS 桌面应用程序**，专为希望 AI **真正产生实际成果**而不仅仅是回答问题的人量身打造。

给它一个目标，它会阅读你的代码库、编写代码、运行命令、搜索网页、生成图像并交付最终的工作成果。然后，它会**记住在过程中学到的东西**，并与你的团队共享知识。

---

## 三大核心支柱

### 🔧 全能瑞士军刀
不只是写代码的 IDE。Word、Excel、PPT、视频、图片 — 日常工作全覆盖。一个人完成过去四个人的活。

**能力覆盖：**
- 📝 **文字 & 文档** — 写报告、改合同、总结会议纪要 — Word、PDF、Markdown 全支持
- 💻 **代码** — 读写代码、运行命令、调试修复 — 全栈开发即刻交付
- 🎨 **图片** — AI 生成、截图分析、PPT 设计素材 — 视觉内容随需而生
- 🎬 **视频** — 脚本、字幕、剪辑自动化 — 多媒体生产全链覆盖
- 📊 **数据** — Excel 分析、数据清洗、图表生成 — 用自然语言处理你的表格
- ⚡ **日常任务** — 排日程、整理文件、格式转换 — 把碎片时间的杂活交给 AI

<div align="center">

<img src="assets/screenshots/agent.png" width="800" alt="Agent 模式 — 自主任务执行" />

<sub><strong>Agent 模式</strong> — 自主执行：读取文件、编写代码、运行命令、规划与打勾追踪</sub>

</div>

---

### 🧠 学中做，做中学 (Learning Trail)
LLM 最大的价值是帮你学新东西。每个任务自动生成复盘、测验、知识卡片 — 不是让 AI 替你干活，是让你越用越强。

**学习系统（来时路）特性：**

| 功能特性 | 详细描述 |
|---------|-------------|
| 📋 **步骤复盘** | Agent 做完任务后，自动生成「为什么这样做」的逐步复盘。不只看到结果，理解每一步背后的逻辑。 |
| 🧪 **即时测验** | 基于任务内容生成思考题，测试你是否真正理解。不是「AI 做了什么」而是「为什么这样做」。 |
| 🃏 **知识卡片** | 关键概念自动生成记忆卡片，间隔重复帮你记住。Anki 式学习，融入工作流。 |
| 🔄 **增量同步** | 继续对话后点击同步，自动检测新内容并更新测验和卡片。已有的学习进度不会丢失。 |

<br />

<div align="center">
  <img src="assets/screenshots/learning-trail.png" width="800" alt="Learning Trail 概览" />
</div>

<br />

| 步骤复盘 | 即时测验 | 知识卡片 |
|:-:|:-:|:-:|
| ![步骤复盘](assets/screenshots/learning-review.png) | ![即时测验](assets/screenshots/learning-quiz.png) | ![知识卡片](assets/screenshots/learning-cards.png) |

---

### 💬 轻社交
内置即时通讯和社区，但不是社交平台。分享 PPT 技巧、好用的 MCP、排查 AI 问题 — 围绕工具、围绕生产力。

- 🔐 **端到端加密即时通讯** — 消息送达即从服务器删除，不留痕，不追踪。
- 🌐 **社区空间** — 分享工作流、发现社区插件、讨论最佳实践。围绕生产力，而非社交。

<br />

<div align="center">
  <img src="assets/screenshots/contacts.png" width="380" alt="联系人与加密聊天" />
  &nbsp;&nbsp;
  <img src="assets/screenshots/community.png" width="380" alt="社区" />
</div>

---

## 隐私第一

- 所有数据**保存在你本地机器**
- 自带 API Key — 没有中间商赚差价，无需订阅
- 无云端依赖，无广告，无隐私追踪
- 消息通讯：端到端加密，送达即焚

---

## 快速开始

1. 从[官方网站](https://oterminal-web.zeabur.app/api/download)**下载**（macOS，Apple Silicon 芯片）
2. **添加你的 API key** — 设置 (Settings) → 密钥 (Keys) → 添加（支持 OpenRouter、DeepSeek、OpenAI、Anthropic、302.AI 以及 10+ 国内大模型厂商）
3. **开始任务** — 用自然语言描述你的目标，让 Agent 自动执行剩下的工作

---

## 技术栈

使用 **Rust** (Tauri v2) + **React** + **SQLite** 构建。关键内部实现：
- **4 阶段工具管道**：预处理 → 并行只读 → 串行写入 → 多 Agent 协作
- **AST 感知编辑**：针对 Rust、JS/TS、Python、Go 等语言的 tree-sitter 回退机制
- **Git 追踪集成**：每次迭代自动生成检查点，任务完成打上标签
- **LSP 深度集成**：多语言诊断和代码补全智能
- **上下文管理**：基于模型阈值的自动 compaction/压缩机制

---

## 定价

| 功能特性 | 个人版 | 企业版 |
|---|---|---|
| **价格** | **¥0** — 永久免费 | 按需定制 |
| 多模态生产能力 | ✅ 文字、代码、图片、视频 | ✅ |
| 自动学习知识库 | ✅ | ✅ |
| 社区与插件分享 | ✅ | ✅ |
| 加密即时通讯 | ✅ | ✅ |
| Zero Terminal 管理后台 | — | ✅ |
| CEO → 员工任务派发 | — | ✅ |
| 团队产出追踪与报表 | — | ✅ |

---

## 许可协议

One Terminal 为**专有软件**。个人使用免费。详情请参阅 [LICENSE](LICENSE)。

<br />

<div align="center">

<sub>© 2025-2026 北京猿尾科技有限公司。保留所有权利。</sub>

</div>
