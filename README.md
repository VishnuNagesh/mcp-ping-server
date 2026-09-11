# MCP Ping Server

A minimal [Model Context Protocol](https://modelcontextprotocol.io/) server built with Python, [uv](https://docs.astral.sh/uv/), and [FastMCP](https://gofastmcp.com/).

It exposes one tool:

- `ping` returns `pong`

## Run locally

Install [uv](https://docs.astral.sh/uv/getting-started/installation/), then run:

```bash
uv sync
uv run fastmcp run server.py:mcp
```

The server uses stdio transport by default and is ready to connect to from an MCP client.

## Inspect with the MCP Inspector

```bash
uv run fastmcp dev server.py
```

## References

- [FastMCP quickstart](https://gofastmcp.com/getting-started/quickstart)
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)
