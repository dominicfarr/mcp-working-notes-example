# mcp-working-notes-example

Simple reference implementation of a FastMCP server, client using STDIO for my working notes blog


### Setup

```bash
python3.11 -m venv mcp_client_env
source mcp_client_env/bin/activate

pip install mcp==1.16.0 fastmcp==2.12.5
```

### Launch Server and  Client Processes
```bash
python mcp_client.py mcp_server.py
```

### Test
```bash
call
Tool name: echo
Arguments (as JSON, for example, {"text": "hello"}): 
{"text": "Hello MCP!"}

Result: Echo: Hello MCP!
```
