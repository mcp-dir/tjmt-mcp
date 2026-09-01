# Instalação detalhada

Jurisprudência TJMT é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tjmt`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tjmt` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tjmt` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tjmt` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tjmt` (ou `servers.tjmt` no VS Code) do config do cliente e reinicie.
