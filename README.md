# Danylo Pantielieiev

**GTM and Full Stack Engineer** — I make company systems and data readable for AI: MCP servers over CRM and marketing data, agent workflows with evals, and the automation glue in between. A decade of full-stack engineering, now pointed at go-to-market systems.

Most GTM engineering happens inside SaaS tools and leaves no commits. This profile is where that invisible work becomes reproducible, tested systems.

## Systems

| System | What it does | Stack | Status |
|---|---|---|---|
| [salesforce-pardot-mcp](https://github.com/DaniilMai/salesforce-pardot-mcp) | Remote MCP server for Salesforce + Pardot: 22 tools, full MCP OAuth 2.1 Authorization Server (PKCE + Dynamic Client Registration), multi-tenant, read-only by default, 170 tests in CI | Python · FastMCP · Docker · Railway | **In production since Jan 2026** · 20+ users |
| [gtm-workflows](https://github.com/DaniilMai/gtm-workflows) | Sanitized production GTM automation: three-route inbound lead orchestration, real-time demo-form grading (enrich → score → route while the visitor waits), and the website visitor play — each with architecture diagrams and honest "what broke" notes | n8n · Clay · Salesforce · Pardot · Lemlist | **In production** |
| [gtm-semantic-layer](https://github.com/DaniilMai/gtm-semantic-layer) | A GTM data model an LLM can query without hand-holding: dbt + DuckDB, synthetic seeds that reproduce seven real CRM data traps, 10 golden questions with pinned answers as CI evals, and a semantic contract executed against the warehouse on every build | dbt · DuckDB · SQL · Python | **Live** — `dbt build` runs anywhere in ~2 min |
| [lead-scoring-evals](https://github.com/DaniilMai/lead-scoring-evals) | Should an LLM grade your inbound leads? A rules baseline (ported from production) vs LLM scorers on a labeled trap-laden dataset: per-segment accuracy with CIs, business-weighted errors, and measured dollars per 1000 leads | Python · Claude API · evals | **Measured** — 4 scorers, opposite failure profiles |


## How I measure AI work

An AI feature isn't done when the prompt works once — it's done when there's something that fails loudly when quality drops: fixtures, a pass rate, a cost per run, a baseline to beat. `salesforce-pardot-mcp` ships with 170 CI tests; `gtm-semantic-layer` pins ten golden questions and executes its semantic contract in CI; `lead-scoring-evals` is the measurement itself — baselines, confusion matrices, and cost per 1000 leads. Measured, not vibes-checked.

## Stack

`Python` · `SQL` · `Salesforce / Pardot APIs` · `MCP` · `n8n` · `Clay` · `dbt` · `Docker` · `Railway`

## Contact

[LinkedIn](https://www.linkedin.com/in/danylo-pantielieiev/)
