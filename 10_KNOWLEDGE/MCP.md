# MCP — Model Context Protocol

## Simple Definition

MCP is an open standard that helps AI applications connect to external tools, files, databases, systems, and workflows in a consistent way.

## Human Analogy

MCP is like a USB-C port for AI applications: one standard interface that can connect many kinds of external context and tools.

## Core Architecture

- MCP Host: the AI application, such as an AI IDE or chat app
- MCP Client: the connector inside the host
- MCP Server: exposes resources, tools, or prompts
- External System: files, databases, SaaS apps, APIs, internal systems

## Why It Matters

Enterprise AI needs trusted context. A model without context is just guessing. A model connected to the right tools and data can participate in real workflows.

MCP can help connect AI systems to:

- local files
- GitHub repositories
- databases
- Google Drive or Slack-like systems
- internal enterprise applications
- design/project documentation

## Product Lens

MCP is less about “cool integration” and more about making AI useful inside existing work systems.

## Risks

- prompt injection
- unsafe tool execution
- data leakage
- excessive permissions
- untrusted MCP servers
- unclear responsibility between model, host, server, and user

## Violet Connection

MCP could eventually connect Violet AIOS to LLMs, coding assistants, GitHub, learning notes, career materials, project repositories, and AEC documentation.

## Public References

- Official MCP documentation
- Anthropic announcement of Model Context Protocol

---

## How to Use This Note

- Keep this file as the polished concept note.
- Put messy course notes in `30_LEARNING/`.
- When a concept becomes useful for a project, link it from `20_PROJECTS/` or a separate implementation repo.

## Update Log

- Created: 2026-06-25
