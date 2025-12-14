<div align="center">

# Erold

### AI-Native Project Management for Developers

Let Claude Code, Cursor, and AI assistants manage your projects directly.

[Website](https://erold.dev) · [Documentation](https://erold.dev/docs) · [Get Started](https://app.erold.dev/auth/register)

</div>

---

## The Problem

Traditional project management tools weren't built for AI-assisted development. Every time you work with Claude, Cursor, or other AI assistants, you have to:

- Copy-paste task descriptions into chat
- Manually update progress after each session
- Re-explain project context every conversation
- Switch between tools constantly

**Erold solves this.** It's the first project management platform where AI assistants can directly read tasks, update progress, and access project knowledge.

## How It Works

Your AI assistant connects to Erold via MCP (Model Context Protocol) and can:

```
You: "Create a task for implementing OAuth"
Claude: ✓ Created task in "Backend API" project (Priority: High)

You: "What's left on the authentication feature?"
Claude: 3 tasks remaining: OAuth setup, session management, JWT refresh

You: "Mark the OAuth task as complete"
Claude: ✓ Updated task_7kd9f2 to Done
```

No copy-paste. No context switching. Just natural conversation.

## Developer Tools (Open Source)

We provide two open-source tools for developers:

| Tool | Description | Install |
|------|-------------|---------|
| **[@erold/cli](https://github.com/erold-dev/cli)** | Manage tasks from your terminal | `npm install -g @erold/cli` |
| **[@erold/mcp-server](https://github.com/erold-dev/mcp-server)** | Connect AI assistants to Erold | `npm install -g @erold/mcp-server` |

## Why Developers Choose Erold

- **API-First** — 68+ REST endpoints, MCP server with 27+ tools
- **CLI-Native** — Full functionality from your terminal
- **Knowledge Base** — Persistent memory for AI across sessions
- **Team Ready** — Collaborate with your team in real-time
- **Fair Pricing** — Free tier available, then $5/month for Pro

## Get Started in 2 Minutes

1. **Sign up** at [app.erold.dev](https://app.erold.dev/auth/register)
2. **Install the CLI**: `npm install -g @erold/cli`
3. **Login**: `erold login`
4. **Create your first project**: `erold projects create "My Project"`

For AI integration, see our [MCP setup guide](https://erold.dev/docs/mcp).

## Built by Yet Technologies

Erold is developed by [Yet Another Artificial Intelligence Company](https://yet.lu), a Luxembourg-based company building AI-powered tools for developers.

---

<div align="center">

**[Start Free →](https://app.erold.dev/auth/register)**

</div>
