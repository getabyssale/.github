# Abyssale

**Generate images, videos, HTML5 banner ads, and print-ready PDFs — programmatically.**

Abyssale is a creative automation platform with a REST API, dynamic image URLs, and webhook support. Design templates once in the Abyssale app, then produce thousands of on-brand creatives at scale via code or no-code integrations.

---

## Get started

- 📖 [Developer documentation](https://developers.abyssale.com) — REST API guides, authentication, and webhooks
- 📐 [API Reference](https://api-reference.abyssale.com) — OpenAPI v3 specification
- 🚀 [Open the app](https://app.abyssale.com)

---

## SDKs & integrations

| Tool / Integration | Repository | Package / Marketplace Link |
|---|---|---|
| **Node.js / TypeScript SDK** | [abyssale-sdk](https://github.com/getabyssale/abyssale-sdk) | [@abyssale/sdk on npm](https://www.npmjs.com/package/@abyssale/sdk) |
| **Python SDK** | [abyssale-python-sdk](https://github.com/getabyssale/abyssale-python-sdk) | [abyssale on PyPI](https://pypi.org/project/abyssale/) |
| **MCP server** | - | [`https://mcp.abyssale.com/mcp`](https://developers.abyssale.com/mcp/overview) |
| **n8n Node** | [n8n-nodes-abyssale](https://github.com/getabyssale/n8n-nodes-abyssale) | [n8n Integration Page](https://n8n.io/integrations/abyssale/) |
| **Zapier** | - | [Zapier Integration](https://zapier.com/apps/abyssale/integrations) |
| **Make.com** | - | [Make Integration](https://www.make.com/en/integrations/abyssale) |
| **Airtable** | - | [Airtable Marketplace App](https://airtable.com/marketplace/blkB14c3EShbFLlh4/abyssale) |

---

## Use Abyssale from your AI assistant (MCP)

The [Abyssale MCP server](https://developers.abyssale.com/mcp/overview) connects AI assistants such as Claude, ChatGPT/Codex, and Cursor directly to your Abyssale workspace. From a conversation, your agent can browse designs and projects, look up fonts and credits, generate banners, videos, and PDFs, and import new designs from JSON, with no code written against the REST API.

- **Endpoint:** `https://mcp.abyssale.com/mcp` (Streamable HTTP, OAuth)
- **Setup guides:** [Claude Code, Claude.ai, ChatGPT/Codex, Cursor](https://developers.abyssale.com/mcp/overview)
- **Reference:** [Tools](https://developers.abyssale.com/mcp/tools-reference) · [Permissions](https://developers.abyssale.com/mcp/permissions) · [Skills](https://developers.abyssale.com/mcp/skills)

---

## What you can build

- **Programmatic image generation** — generate on-brand visuals from a template + JSON data via REST API.
- **Dynamic image URLs** — embed personalized images on the fly using URL query parameters (cached for 1 year).
- **Bulk creative production** — asynchronous batch generation with webhook callbacks for high-volume workflows.
- **Print-ready PDFs** — export pixel-perfect, high-resolution PDFs from templates at scale, including OOH (out-of-home) formats.
- **HTML5 banner ads** — generate dynamic, animated banner ads programmatically.
- **Create designs from JSON** *(API only — alpha)* — build a full design from a single JSON payload via [Design Import](https://developers.abyssale.com/rest-api/designs/import/).

---

[abyssale.com](https://www.abyssale.com)