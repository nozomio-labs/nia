# Nia - Context for AI Agents

[![Website](https://img.shields.io/badge/Website-trynia.ai-blue)](https://trynia.ai)
[![Documentation](https://img.shields.io/badge/Docs-docs.trynia.ai-green)](https://docs.trynia.ai)
[![Y Combinator](https://img.shields.io/badge/Y%20Combinator-S25-orange)](https://www.ycombinator.com/companies/nozomio)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289da)](https://discord.gg/BBSwUMrrfn)

> **Context layer for AI coding agents - backed by Y Combinator ($6.2M raised)**

Nia gives better context to coding agents. It reduces hallucinations by 43% by allowing agents to index any remote codebase, docs, or package. We continuously monitor and update sources automatically.

## What is Nia?

Nia is an **API layer** that provides agents with up-to-date, continuously monitored context from libraries, research papers, and technical documentation.

**Core Capabilities:**

- **Universal Search** - Sub-5s responses across millions of indexed pages and GitHub files
- **Instant Package Search** - Search 3,000+ pre-indexed packages (PyPI, NPM, Crates.io, Go modules) - no indexing required
- **Repository Indexing** - Index entire GitHub repositories for deep architectural understanding
- **Documentation Integration** - Index and search any website or documentation
- **Research Papers** - Index and search arXiv papers for academic context
- **Oracle Research Agent** - Autonomous deep research across codebases and documentation
- **Context Sharing** - Save conversation histories, plans, and decisions between different agents
- **Local Folder Sync** - Sync local folders, databases, and chat history to Nia
- **Auto-Sync** - Sources are continuously monitored and updated automatically
- **API & MCP** - Available as an API or MCP server for any coding agent

### Example: Using Nia in Cursor with Package and Documentation Search

<div align="center">

[![Watch the demo](https://img.youtube.com/vi/NnxppAg4yBo/0.jpg)](https://www.youtube.com/watch?v=NnxppAg4yBo)

🎥 **[Watch Demo →](https://www.youtube.com/watch?v=NnxppAg4yBo)**

</div>

## Quick Start

### One-Command Install (Under 1 minute)

```bash
npx nia-wizard@latest
```

This wizard handles everything:
- Creates your account or logs you in
- Generates your API key automatically
- Auto-detects and configures your IDE
- Works for Cursor, VS Code, Claude Code, Windsurf, and 30+ other agents

**Alternative methods:**
```bash
pnpx nia-wizard@latest       # pnpm
bunx nia-wizard@latest       # bun (fastest)
yarn dlx nia-wizard@latest   # yarn
```

### Supported Coding Agents

Nia works with **30+ coding agents** including:

| Agent | Agent | Agent |
|-------|-------|-------|
| Cursor | VS Code | Claude Code |
| Windsurf | Cline | Continue.dev |
| Claude Desktop | Zed | JetBrains AI |
| OpenAI Codex | Copilot CLI | Gemini CLI |
| Amazon Q | Roo Code | Kilo Code |
| Qwen Coder | Mistral Vibe | And many more... |

See our [full setup guide](https://docs.trynia.ai/integrations/nia-mcp) for all supported agents.

## Core Features

### Package Search (No Indexing Required!)
- **3,000+ pre-indexed packages** from PyPI, NPM, Crates.io, Go modules
- **Regex search** (`nia_package_search_grep`) - find exact code patterns
- **Semantic search** (`nia_package_search_hybrid`) - AI-powered understanding
- **Read source files** - get complete context around snippets

### Universal Indexing
- **GitHub repositories** - index any public repo for deep code understanding
- **Documentation sites** - index any website or docs
- **Research papers** - index arXiv papers for academic context
- **Local folders** - sync private folders, databases, and chat history

### Search & Research
- **Universal search** - query across all indexed sources with natural language
- **Oracle Research Agent** - autonomous deep research across codebases and docs
- **Deep Research Agent** - comprehensive multi-step analysis and comparisons
- **Web search** - discover trending repos, libraries, and content

### Context Management
- **Context sharing** - save conversation histories and plans between agents
- **Auto-sync** - sources are continuously monitored and updated
- **Local sync** - sync local folders with privacy-first design

### Enterprise Ready
- **SOC-2 Type 1 Verified** with enterprise-grade security
- **Local hosting options** for complete data sovereignty
- **Unlimited usage** with dedicated support
- **Custom infrastructure** and security options

## Community & Support

### Report Issues
Found a bug or have a feature request? We'd love to hear from you!

- **[Report a Bug](../../issues/new?assignees=&labels=bug&template=bug_report.md)**
- **[Request a Feature](../../issues/new?assignees=&labels=enhancement&template=feature_request.md)**
- **[Ask a Question](../../issues/new?assignees=&labels=question&template=question.md)**
- **[General Feedback](../../issues/new?assignees=&labels=feedback&template=general_feedback.md)**

### Resources

- **[Documentation](https://docs.trynia.ai)** - Complete setup guides and API reference
- **[Get API Key](https://app.trynia.ai)** - Start using Nia today
- **[Discord Community](https://discord.gg/BBSwUMrrfn)** - Join 1000+ engineers using Nia
- **[API Reference](https://docs.trynia.ai/api-reference)** - Build custom agents with Nia API

### Enterprise Contact

Need enterprise features, custom deployment, or have questions about SOC-2 compliance?

**Contact CEO:** [arlan@nozomio.com](mailto:arlan@nozomio.com)

## Privacy & Security

- **SOC-2 Type 1 Verified** enterprise-grade security
- **No AI training** - Your data is never used to train external AI models
- **Enterprise encryption** and secure data handling
- **350+ exclusion patterns** protect sensitive files from being synced

## Pricing

| Feature | Free | Pro | Startup | Enterprise |
|---------|------|-----|---------|------------|
| **Price** | $0 | $15/month | $50/engineer/month | Custom |
| **Queries** | 50/month | 1,000/month | 5,000/month | Unlimited |
| **Web Searches** | 20/month | 200/month | 1,000/month | Unlimited |
| **Package Search** | 50/month | Unlimited | Unlimited | Unlimited |
| **Contexts** | 5 | 100 | 500 | Unlimited |
| **Deep Research** | - | 30/month | 100/month | Unlimited |
| **Oracle** | - | 30/month | 100/month | Unlimited |
| **Indexing** | 3 lifetime | 50/month | 150/month | Unlimited |

**Credit Packs** - Need more? Buy credits on-demand starting at $3 for 100 credits.

See [full pricing details](https://docs.trynia.ai/pricing) for credit costs per operation.

---

**Made with care by [Nozomio Labs](https://nozomio.com) in San Francisco**