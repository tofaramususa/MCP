- Expose data and functionality to LLMs
-  FastMCP server is your core interface to the MCP protocol. It handles connection management, protocol compliance, and message routing

Transport methods: how clients and servers actually communicate
- stdio transport --> input/output for communication,  local processes
- HTTP with SSE transport --> Server-Sent Events for server-to-client messages, HTTP POST for client-to-server messages
- MCP Inspector tool to check the MCP
- Streamable HTTP Transport. Note: Streamable HTTP transport is superseding SSE transport for production deployments.