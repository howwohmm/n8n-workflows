# n8n-workflows

## project name + description
- n8n-workflows: Local copy of the n8n-MCP server (czlonkowski/n8n-mcp) used for building a CRM entry workflow for a client ("Calum")

## who it's for
- Self — workflow automation for a specific client CRM integration task

## current status
- tool

## what was actually built
- Full n8n-MCP server (v2.10.5) — MCP server giving Claude access to 535 n8n node definitions, documentation, and validation tools
- Client workflow directory: "calum client to crm" with `n8n-mcp` subdirectory
- SQLite database (`nodes.db`) with n8n node properties, operations, and documentation
- Docker + Railway deployment configs for the MCP server
- 1,356-test suite covering MCP protocol compliance, database operations, and performance

## why it was built
- To use n8n-MCP as the AI assistant backend for building an n8n workflow that moves a client (Calum) into a CRM system

## blockers or reasons shelved
- Not shelved — active tool

## wins or progress moments
- n8n-MCP itself is a mature open-source tool (2.10.5, 535 nodes, 88% doc coverage, ~12ms response time)

## pain points
- The actual workflow for "calum client to crm" is not visible — only the MCP server infrastructure is present

## where claude api / ai was used or planned
- Claude (via n8n-MCP) is the primary interface for designing, validating, and deploying n8n workflows — the MCP server gives Claude deep knowledge of all 535 n8n nodes

## what would've helped
- The actual n8n workflow JSON for the Calum CRM integration would complete the picture

## metrics or traction
- none
