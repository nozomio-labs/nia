# Nia - Index Anything. Search It with AI.

[![Website](https://img.shields.io/badge/Website-trynia.ai-blue)](https://trynia.ai)
[![Documentation](https://img.shields.io/badge/Docs-docs.trynia.ai-green)](https://docs.trynia.ai)
[![Y Combinator](https://img.shields.io/badge/Y%20Combinator-S25-orange)](https://www.ycombinator.com/companies/nozomio)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289da)](https://discord.gg/BBSwUMrrfn)

> **Index docs, repos, PDFs, and datasets -- then search them with AI. Backed by Y Combinator ($6.2M raised)**

Nia lets you index docs, repos, PDFs, datasets, spreadsheets, Slack, Google Drive, and more -- then gives your AI agent a search API to query them. Your agent gets real answers instead of hallucinations.

## What is Nia?

Nia is an **API layer** that gives agents up-to-date, continuously monitored context across repositories, documentation, PDFs, datasets, Slack, Google Drive, and local knowledge sources. It handles indexing, search, reading, research, and handoffs so agents can work from real source material instead of guesswork.

You can use it with agents like Cursor or Claude Code as an MCP server, or build your own applications with the Nia API.

**Core Capabilities:**

- **Universal Indexing** - Index GitHub repos, documentation sites, PDFs, arXiv papers, HuggingFace datasets, spreadsheets, and local folders
- **Universal Search** - Sub-5s semantic search across all indexed sources
- **Package Search** - Search 150M+ pre-indexed documents from PyPI, NPM, Crates.io, and Go modules -- no indexing required
- **Document Agent** - Deploy an autonomous AI agent into any indexed PDF or document for deep research with cited answers
- **Data Extraction** - Extract structured data from PDFs into JSON using custom schemas
- **Tracer** - Search GitHub code without indexing using specialized sub-agents (Fast mode with Haiku, Deep mode with Opus)
- **Oracle Research Agent** - Autonomous deep research across codebases and documentation
- **Context Sharing** - Save plans, discoveries, and conversation state between different agents
- **Connectors** - Integrate Notion, Confluence, and other external sources via OAuth/API key
- **Google Drive Integration** - Browse, select, index, and keep Drive content synced
- **Slack Search** - Index Slack workspaces and search conversations semantically
- **E2E Encryption** - Zero-knowledge sync for iMessage, WhatsApp, Apple Notes, Contacts, and more
- **Local Sync** - Sync local folders, databases, and chat history with continuous monitoring
- **Scoped MCP** - Create task-specific MCP surfaces for focused workflows
- **Auto-Sync** - Sources are continuously monitored and updated automatically
- **API & MCP** - Available as an API or MCP server for any agent

### Example: Using Nia in Cursor with Package and Documentation Search

<div align="center">

[![Watch the demo](https://img.youtube.com/vi/NnxppAg4yBo/0.jpg)](https://www.youtube.com/watch?v=NnxppAg4yBo)

**[Watch Demo](https://www.youtube.com/watch?v=NnxppAg4yBo)**

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

### Supported Agents

Nia works with **30+ agents** including:

| Agent | Agent | Agent |
|-------|-------|-------|
| Cursor | VS Code | Claude Code |
| Windsurf | Cline | Continue.dev |
| Claude Desktop | Zed | JetBrains AI |
| OpenAI Codex | Copilot CLI | Gemini CLI |
| Amazon Q | Roo Code | Kilo Code |
| Qwen Coder | Mistral Vibe | And many more... |

See our [full setup guide](https://docs.trynia.ai/integrations/nia-mcp) for all supported agents.

## Source Types

Nia can index and search across a wide range of knowledge sources:

| Source Type | How to Index | Notes |
|-------------|-------------|-------|
| **Code & Repositories** | `index` or Tracer | Grep, semantic search, file trees |
| **Documentation Sites** | `index` on any URL | `llms.txt` aware, supports crawl filters |
| **PDFs & Research Papers** | `index` on PDF/arXiv URL | Section-aware retrieval, Document Agent |
| **HuggingFace Datasets** | `index` on dataset URL | Row-level search, schema discovery |
| **Google Drive** | OAuth integration | Docs, Sheets, Slides, PDFs with incremental sync |
| **Spreadsheets** | `index` CSV/TSV/XLSX/XLS | Row-aware, header-aware indexing |
| **Slack** | Workspace integration | Real-time sync via Events API |
| **X (Twitter)** | Account indexing | Semantic search over posts and threads |
| **Local Folders** | `index(folder_path=...)` | Continuous sync available |
| **Connectors** | Notion, Confluence, etc. | OAuth and API key auth with scheduled sync |
| **E2E Encrypted** | TypeScript SDK | iMessage, WhatsApp, Notes, Contacts, Reminders |

## Key Features

### Document Agent
Deploy an autonomous AI agent into any indexed PDF or document. It plans its own research strategy, navigates document structure, and produces answers with section-aware citations. Supports structured JSON output and streaming.

### Data Extraction
Extract structured records from PDFs -- financial filings, invoices, spec sheets, engineering drawings. Three modes: table extraction, visual element detection, and engineering extraction.

### Tracer
Search GitHub code without indexing. Tracer delegates tasks to specialized sub-agents operating in parallel. **Fast mode** (Haiku) for quick lookups, **Deep mode** (Opus 1M context) for thorough investigations.

### Package Search (No Indexing Required)
Search 150M+ pre-indexed documents from PyPI, NPM, Crates.io, and Go modules. Regex and semantic search across public package source code.

### Oracle Research Agent
Autonomous deep research across codebases and documentation. Chains multiple searches and builds dynamic knowledge trees for complex questions.

### Context Sharing
Save plans, discoveries, edited files, and conversation state so another agent can pick up where you left off. Supports scratchpad, episodic, fact, and procedural memory types.

### Connectors
Integrate external data sources through a unified framework. Supports Notion, Confluence, and more with OAuth/API key authentication, scheduled syncing, and status monitoring.

### E2E Encryption
Zero-knowledge sync for personal data -- iMessage, WhatsApp, Apple Notes, Contacts, Reminders, Stickies, and Screenshots. Plaintext never leaves your device.

## Use Cases

Developers are building diverse applications with Nia's API:

- **Community forum search** (Cursor Forum Search -- 5,000+ pages indexed)
- **Knowledge base Q&A** (Paul Graham Essays, Naval Wisdom)
- **Document archives** (Epstein Archive, legal research)
- **Blog search** (Simon Willison's Weblog -- 4,500+ posts)
- **Dataset exploration** (HuggingFace datasets)
- **Code review agents** that fetch up-to-date documentation on demand
- **Law research agents** indexing legal PDFs
- **PDF book agents** for students and researchers
- **Custom search engines** for any content

See [trynia.ai/use-cases](https://trynia.ai/use-cases) for featured projects.

## Enterprise Ready

- **SOC-2 Compliance** for enterprise customers
- **SLA Guarantees** with dedicated support
- **Self-hosted deployment** for complete data sovereignty
- **No AI training** -- your data is never used to train external models
- **E2E encryption** and advanced data handling
- **Custom infrastructure** and security options

## Community & Support

### Report Issues
Found a bug or have a feature request? We'd love to hear from you!

- **[Report a Bug](../../issues/new?assignees=&labels=bug&template=bug_report.md)**
- **[Request a Feature](../../issues/new?assignees=&labels=enhancement&template=feature_request.md)**
- **[Ask a Question](../../issues/new?assignees=&labels=question&template=question.md)**
- **[General Feedback](../../issues/new?assignees=&labels=feedback&template=general_feedback.md)**

### Resources

- **[Documentation](https://docs.trynia.ai)** - Complete setup guides, capabilities, and API reference
- **[Get API Key](https://app.trynia.ai)** - Start using Nia today
- **[Discord Community](https://discord.gg/BBSwUMrrfn)** - Join our community
- **[API Reference](https://docs.trynia.ai/api-reference)** - Build custom agents with Nia API

### Enterprise Contact

Need enterprise features, custom deployment, or have questions about SOC-2 compliance?

**Contact Founders:** [founders@nozomio.com](mailto:founders@nozomio.com)

## Privacy & Security

- **SOC-2 Compliance** for enterprise customers
- **No AI training** - Your data is never used to train external AI models
- **E2E encryption** available for sensitive personal data
- **Data opt-out** from AI providers (Anthropic, OpenAI, Gemini) -- they do not store or train on your data
- **350+ exclusion patterns** protect sensitive files from being synced

## Pricing

| Feature | Free | Builder | Team | Business | Enterprise |
|---------|------|---------|------|----------|------------|
| **Price** | $0 | $15/month | $50/seat/month | $99/seat/month | Custom |
| **Queries** | 50/month | 1,000/month | 5,000/month | Unlimited | Unlimited |
| **Web Searches** | 20/month | 200/month | 1,000/month | Unlimited | Unlimited |
| **Package Search** | 50/month | Unlimited | Unlimited | Unlimited | Unlimited |
| **Contexts** | 5 | 100 | 1,000 | Unlimited | Unlimited |
| **Deep Research** | Credits only | 30/month | 200/month | Unlimited | Unlimited |
| **Oracle** | Credits only | 30/month | 200/month | Unlimited | Unlimited |
| **Tracer** | Credits only | 30/month (3 concurrent) | 200/month (10 concurrent) | Unlimited (50 concurrent) | Unlimited (100 concurrent) |
| **Indexing** | 3 lifetime | 50/month | 500/month | Unlimited | Unlimited |
| **Concurrent Indexes** | 1 | 5 | 50 | Unlimited | Unlimited |
| **SOC 2** | - | - | - | - | Yes |
| **SLA** | - | - | - | - | Yes |
| **Dedicated Support** | - | - | - | Yes | Yes |

**Credit Packs** - Need more? Buy credits on-demand. Credits never expire.

| Pack | Credits | Price | Per Credit |
|------|---------|-------|------------|
| Starter | 100 | $3 | $0.030 |
| Plus | 300 | $7 | $0.023 |
| Developer | 1,000 | $18 | $0.018 |
| Growth | 5,000 | $50 | $0.010 |
| Scale | 30,000 | $149 | $0.005 |
| Max | 100,000 | $499 | $0.005 |

**Credit Costs per Operation:**

| Operation | Credits |
|-----------|---------|
| Search & Context | 1 |
| Indexing & Sync | 10 |
| Deep Research | 10 |
| Oracle | 15 |
| Tracer | 15 |

See [full pricing details](https://docs.trynia.ai/pricing) for more information.

---

**Made with care by [Nozomio Labs](https://nozomio.com) in San Francisco**
