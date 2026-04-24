# mcp-hello

Hello-world MCP server built while learning the protocol. Minimal MCP server with a single `ping` tool that returns `"pong"`. Built with the Python SDK and uv.

## Run

```bash
uv run python server.py
```

Or via the MCP CLI (stdio transport, useful for testing):

```bash
uv run mcp dev server.py
```

The `mcp dev` command starts an interactive inspector at `http://localhost:5173` where you can call the `ping` tool directly.