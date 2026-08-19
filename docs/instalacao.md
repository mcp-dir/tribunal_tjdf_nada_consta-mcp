# Instalação detalhada

Tribunal TJDF: Nada Consta é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tribunal_tjdf_nada_consta`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tribunal_tjdf_nada_consta` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tribunal_tjdf_nada_consta` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tribunal_tjdf_nada_consta` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tribunal_tjdf_nada_consta` (ou `servers.tribunal_tjdf_nada_consta` no VS Code) do config do cliente e reinicie.
