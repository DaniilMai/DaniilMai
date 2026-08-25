# Danylo Pantielieiev

**GTM and Full Stack Engineer** — I make company systems and data readable for AI: MCP servers over CRM and marketing data, agent workflows with evals, and the automation glue in between. A decade of full-stack engineering, now pointed at go-to-market systems.

Most GTM engineering happens inside SaaS tools and leaves no commits. This profile is where that invisible work becomes reproducible, tested systems.

## Systems

| System | What it does | Stack | Status |
|---|---|---|---|
| [salesforce-pardot-mcp](https://github.com/DaniilMai/salesforce-pardot-mcp) | Remote MCP server for Salesforce + Pardot: 22 tools, full MCP OAuth 2.1 Authorization Server (PKCE + Dynamic Client Registration), multi-tenant, read-only by default, 170 tests in CI | Python · FastMCP · Docker · Railway | **In production since Jan 2026** · 20+ users |

Next up: sanitized n8n + Clay GTM workflows with architecture diagrams and honest "what broke" sections, a dbt semantic layer over GTM data that an LLM can query directly, and an eval harness for LLM lead scoring. Rows get added here when there is code to read.

## How I measure AI work

An AI feature isn't done when the prompt works once — it's done when there's something that fails loudly when quality drops: fixtures, a pass rate, a cost per run, a baseline to beat. `salesforce-pardot-mcp` ships with 170 CI tests covering OAuth, injection, and field protection; the same bar — measured, not vibes-checked — is how I treat model-facing work.

## Stack

`Python` · `SQL` · `Salesforce / Pardot APIs` · `MCP` · `n8n` · `Clay` · `dbt` · `Docker` · `Railway`

## Contact

[LinkedIn](https://www.linkedin.com/in/danylo-pantielieiev/)
