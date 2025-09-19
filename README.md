# Nia - Context Augmentation for Agents

[![Website](https://img.shields.io/badge/Website-trynia.ai-blue)](https://trynia.ai)
[![Documentation](https://img.shields.io/badge/Docs-docs.trynia.ai-green)](https://docs.trynia.ai)
[![Y Combinator](https://img.shields.io/badge/Y%20Combinator-S25-orange)](https://www.ycombinator.com/companies/nozomio)

> **Context-augmentation layer for agents, primarily designed for coding agents**

Nia is a context-augmentation layer that provides agents with an up-to-date knowledge base and improves their performance by 27%. This repository serves as the public issue tracker and community hub for Nia.

## What is Nia?

Nia is a **context-augmentation layer** that enhances coding agents with:

- **Deep Repository Understanding** - Index entire GitHub repositories for architectural context
- **Documentation Integration** - Index and access any website or documentation
- **Package Search** - Execute grep across the source code of a public package, search package source using regex or semantic understanding, and read exact lines from a source file.
- **Universal Agent Support** - Works with Cursor, Claude Desktop, Continue, VS Code Cline, Windsurf, and any MCP-compatible tool
- **API** - Available as an API so you can enhance your own custom agents 24/7.

### Example: Using Nia in Cursor with Package and Documentation Search

<div align="center">

[![Watch the demo](https://img.youtube.com/vi/NnxppAg4yBo/0.jpg)](https://www.youtube.com/watch?v=NnxppAg4yBo)

🎥 **[Watch Demo →](https://www.youtube.com/watch?v=NnxppAg4yBo)**

</div>

## ⚡ Quick Start

### For Cursor Users (Under 2 minutes)

1. **Get your API key** at [app.trynia.ai](https://app.trynia.ai) (3 indexing jobs free, no credit card needed)

2. **Install the MCP server:**
   ```bash
   pipx install nia-mcp-server
   ```

3. **Run setup:**
   ```bash
   pipx run --no-cache nia-mcp-server setup YOUR_API_KEY
   ```

That's it! Restart Cursor and you're ready to go.

### For Other Coding Assistants

Check out our [comprehensive setup guide](https://docs.trynia.ai) for:
- Windsurf
- Claude Desktop
- Continue
- VS Code Cline
- Any MCP-compatible tool

## 🔧 Core Features

### Repository
- **Index GitHub repos** for instant code understanding
- **Search codebases** using natural language queries
- **Package search** through source code of any package

### Docs & Web Search
- **Index documentation** from any website
- **Natural language search** across indexed docs
- **Intelligent discovery** of trending repositories and libraries

### Enterprise Ready
- **SOC-2 compliant** with enterprise-grade security
- **Local hosting options** for complete data sovereignty
- **Unlimited usage** with dedicated support
- **Custom models** and usage limits

## 🤝 Community & Support

### 📝 Report Issues
Found a bug or have a feature request? We'd love to hear from you!

- **[Report a Bug](../../issues/new?assignees=&labels=bug&template=bug_report.md)**
- **[Request a Feature](../../issues/new?assignees=&labels=enhancement&template=feature_request.md)**
- **[Ask a Question](../../issues/new?assignees=&labels=question&template=question.md)**
- **[General Feedback](../../issues/new?assignees=&labels=feedback&template=general_feedback.md)**

### 📚 Resources

- **[Documentation](https://docs.trynia.ai)** - Complete setup guides and API reference
- **[Get API Key](https://app.trynia.ai)** - Start using Nia AI today

### 🏢 Enterprise Contact

Need enterprise features, custom deployment, or have questions about SOC-2 compliance?

**Contact CEO:** [arlan@nozomio.com](mailto:arlan@nozomio.com)

## 🔒 Privacy & Security

- **SOC-2 compliant** enterprise-grade security
- **No AI training** - Your data is never used to train external AI models
- **Enterprise encryption** and secure data handling

## 📈 Pricing

- **Free Tier** - Get started with 3 indexing jobs (no credit card required)
- **Solo developers** - $15/mo for extended solo usage
- **Startups** - $50-100/mo/engineer for pretty much unlimited usage
- **Enterprise** - Unlimited usage, custom models, dedicated support, and local hosting options
- Contact us for custom pricing and enterprise features

---

**Made with ❤️ by [Nozomio Labs](https://nozomio.com) in San Francisco**