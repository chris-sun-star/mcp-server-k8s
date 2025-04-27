# mcp-server-k8s
A simple MCP server for Kubernetes

Uploading Screen Recording 2025-04-27 at 16.13.43.mov…



## How to use this MCP server
By configuring the following contents in `~/Library/Application Support/Claude/claude_desktop_config.json`, and replace the directory with real project path, you can easily use it with Claude Desktop
```
{
  "mcpServers": {
    "k8s": {
        "command": "uv",
        "args": [
            "--directory",
            "/path/to/mcp-server-k8s",
            "run",
            "main.py"
        ]
    }
  }
}
```
