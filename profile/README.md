<img src="banner.png" alt="looot: one key for 2,500+ data endpoints" width="100%">

looot gives an AI agent one key and one prepaid balance for 2,500+ data API endpoints from 90+ providers: work emails, phone numbers, company and people search, Google results, web pages, news, LinkedIn profiles, local businesses. The agent searches the catalog, sees the price before it runs, and pays per call. A failed call costs nothing. Top up from $5, no subscription.

### Install

```bash
# Claude Code, or any MCP client (browser sign-in, no key in config)
claude mcp add --transport http looot https://api.looot.ai/mcp

# CLI
npm install -g looot
```

REST: `POST https://api.looot.ai/v1/runs` with a bearer token. Docs at [docs.looot.ai](https://docs.looot.ai).

### Repos

| Use looot from | Repo |
| --- | --- |
| MCP clients | [looot-mcp](https://github.com/loootai/looot-mcp) |
| Claude Code, Codex, Cursor plugin | [looot-plugin](https://github.com/loootai/looot-plugin) |
| Agent skills (`npx skills add loootai/looot-skills`) | [looot-skills](https://github.com/loootai/looot-skills) |
| TypeScript and Python | [looot-js](https://github.com/loootai/looot-js), [looot-python](https://github.com/loootai/looot-python) |
| Vercel AI SDK, LangChain | [looot-ai-sdk](https://github.com/loootai/looot-ai-sdk), [langchain-looot](https://github.com/loootai/langchain-looot) |
| n8n, Activepieces, Dify | [n8n-nodes-looot](https://github.com/loootai/n8n-nodes-looot), [looot-activepieces](https://github.com/loootai/looot-activepieces), [looot-dify](https://github.com/loootai/looot-dify) |
| VS Code, JetBrains, Zed | [looot-vscode](https://github.com/loootai/looot-vscode), [looot-jetbrains](https://github.com/loootai/looot-jetbrains), [looot-zed](https://github.com/loootai/looot-zed) |
| GitHub Actions | [looot-action](https://github.com/loootai/looot-action) |

| Start from a template | Repo |
| --- | --- |
| Domains in, verified work emails out (CSV) | [looot-lead-gen-agent](https://github.com/loootai/looot-lead-gen-agent) |
| Weekly Google rank report for a keyword list | [looot-seo-monitor](https://github.com/loootai/looot-seo-monitor) |
| Open-source Clay-style enrichment tables (Next.js + Supabase) | [looot-tables](https://github.com/loootai/looot-tables) |
| Recipes: enrichment, research, SEO, scraping | [looot-cookbook](https://github.com/loootai/looot-cookbook) |

[looot.ai](https://looot.ai) · [Docs](https://docs.looot.ai) · [Privacy](https://looot.ai/privacy) · [Terms](https://looot.ai/terms) · [Contact](https://looot.ai/contact)
