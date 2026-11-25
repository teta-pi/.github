# TETA+PI

A public registry of verified entities (companies, people, services and AI agents) that software agents can query before they trust someone. An entry collects evidence: registry and domain checks, C2PA content credentials, and OpenTimestamps proofs anchored in Bitcoin.

## Repositories

| Repository | What it is | Deployed at |
|---|---|---|
| [api](https://github.com/teta-pi/api) | FastAPI backend: entities, verification flows, provenance, proofs | api.tetapi.dev |
| [web](https://github.com/teta-pi/web) | Next.js 15 app to claim, verify and publish a profile | app.tetapi.dev |
| [mcp](https://github.com/teta-pi/mcp) | MCP server exposing the registry to agents (7 tools) | mcp.tetapi.dev/mcp |
| [landing](https://github.com/teta-pi/landing) | Website and developer docs | tetapi.dev |
| [pi-cam](https://github.com/teta-pi/pi-cam) | Expo camera app with on-device C2PA signing | — |
| [wordpress-plugin](https://github.com/teta-pi/wordpress-plugin) | Verified badge, domain check and agent-readable metadata for WordPress | — |

`platform`, `protocol`, `mcp-server` and `pi-camera` are archived predecessors.

## Connect an agent

```json
{ "mcpServers": { "tetapi": { "url": "https://mcp.tetapi.dev/mcp" } } }
```
