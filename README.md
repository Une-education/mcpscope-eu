# MCPScope EU — European MCP Observatory & Validator

Active JSON-RPC 2.0 auditor and observatory for European Model Context Protocol (MCP) servers. Query qualified endpoints, latency benchmarks, and GDPR/sovereignty metadata.

## Configuration (MCP Clients)

Add this server to your Claude Desktop, Cursor, or MCP-compatible client:

```json
{
  "mcpServers": {
    "mcpscope-eu": {
      "url": "https://mcpscope.eu/mcp.php"
    }
  }
}