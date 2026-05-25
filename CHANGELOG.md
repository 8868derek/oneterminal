# Changelog

All notable changes to One Terminal will be documented in this file.

## [1.0.0] — 2025-05-25

### 🚀 Initial Release

**Core Engine**
- Agent Mode: autonomous task execution with 30+ tools
- Chat Mode: lightweight conversation with full context awareness
- Context Management: automatic micro/full compaction with model-specific thresholds
- Multi-Agent Delegation: parallel sub-agent execution via specialist agents
- Hook Pipeline: security audit, workspace isolation, result truncation

**Multimodal Production**
- Text: copywriting, document generation, report output
- Code: read/write/edit files, run shell commands, debug
- Image: AI generation, screenshot analysis, design assets
- Video: script, subtitle, editing automation support

**Tools**
- `read_file`, `write_file`, `edit_file`, `multi_edit_file` (with AST fallback)
- `search_files`, `list_directory`, `create_file`, `create_directory`
- `run_shell` (sandboxed with workspace isolation)
- `web_search`, `read_url`, `browse_url`
- `analyze_image`, `image_search`
- `present_plan`, `task_complete`, `delegate_to_agent`
- `emit_references` (Learning Trail integration)
- tree-sitter AST-aware editing for Rust, JavaScript, TypeScript, Python, Go

**Git Integration**
- Auto-init git for new workspaces
- Per-iteration checkpoint commits
- Task completion tags (`ot/task_{id}/done`)

**LSP Integration**
- Multi-language LSP server management
- Real-time diagnostics after file edits
- Go-to-definition and find-references support

**Social Features**
- Built-in community: posts, comments, categories, upvotes
- Contacts & direct messaging (ephemeral, E2E encrypted)
- Friend requests, cloud user search
- Zero Terminal integration for enterprise collaboration

**Desktop App**
- Native macOS app (Tauri v2 + Rust backend)
- Apple Silicon optimized (M1/M2/M3/M4)
- Embedded browser with multi-tab support
- Terminal panel with PTY integration
- File explorer with drag-and-drop
- Knowledge Vault for persistent knowledge management
- Learning Trail for cognitive growth tracking

**Knowledge & Learning**
- MEMORY.md + ONETERMINAL.md project context
- Auto-learning knowledge vault
- Learning Trail: auto-tagged references and study notes
- Agent memory accumulation across tasks
