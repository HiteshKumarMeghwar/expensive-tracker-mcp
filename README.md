# expensive-tracker-mcp

A local MCP server designed to help you track and manage expenses across apps, forms, or spreadsheets. This server integrates with Claude Desktop for streamlined usage and easy testing.

---

## Setup and Installation

Follow these steps to get your MCP server up and running:

### 1. Install `uv`
Install the UV package manager (required for MCP development):

```bash
pip install uv
mkdir fastmcp-demo-server
cd fastmcp-demo-server
code .
uv init
uv add fastmcp
fastmcp version
# create main.py with server logic
uv run fastmcp dev main.py
uv run fastmcp run main.py
uv run fastmcp install claude-desktop main.py
