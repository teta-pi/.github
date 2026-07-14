# TETA+PI (Θ+π)

**Trust Infrastructure for Digital Entities.**

AI agents are already searching, booking, and transacting autonomously —
but there's no standard way to verify who they're dealing with. People,
companies, APIs, AI models, MCP servers, and agents all need a way to prove
who they are and be found. TETA+PI closes that gap.

## What we build

| Repo | Description |
|------|-------------|
| [api](https://github.com/teta-pi/api) | FastAPI backend — registry/email/domain verification, C2PA + Bitcoin proof chain |
| [web](https://github.com/teta-pi/web) | Next.js 15 app — claim and manage a verified profile |
| [mcp](https://github.com/teta-pi/mcp) | MCP server — 7 tools exposing the registry to AI agents |
| [landing](https://github.com/teta-pi/landing) | Marketing site — tetapi.dev |
| [infra](https://github.com/teta-pi/infra) | Canonical docs + deploy configuration |

## The analogy

SSL made HTTPS trustworthy.
MCP connected agents to tools.
**TETA+PI makes digital entities verifiable.**

## Connect an agent

```json
{
  "mcpServers": {
    "tetapi": {
      "url": "https://mcp.tetapi.dev/sse"
    }
  }
}
```

🌐 [tetapi.dev](https://tetapi.dev)
