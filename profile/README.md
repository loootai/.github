<img src="banner.png" alt="looot: one key for 2,500+ data endpoints" width="100%">

**[Showcase](https://loootai.github.io/showcase/)**: every repo built on looot in one gallery, with prices.

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
| GTM workflow skills (`npx skills add loootai/gtm-skills`) | [gtm-skills](https://github.com/loootai/gtm-skills) |
| TypeScript and Python | [looot-js](https://github.com/loootai/looot-js), [looot-python](https://github.com/loootai/looot-python) |
| Vercel AI SDK, LangChain | [looot-ai-sdk](https://github.com/loootai/looot-ai-sdk), [langchain-looot](https://github.com/loootai/langchain-looot) |
| n8n, Activepieces, Dify | [n8n-nodes-looot](https://github.com/loootai/n8n-nodes-looot), [looot-activepieces](https://github.com/loootai/looot-activepieces), [looot-dify](https://github.com/loootai/looot-dify) |
| Zapier, Make | [looot-zapier](https://github.com/loootai/looot-zapier), [looot-make](https://github.com/loootai/looot-make) |
| Attio, HubSpot, Twenty CRM | [looot-attio](https://github.com/loootai/looot-attio), [looot-hubspot](https://github.com/loootai/looot-hubspot), [twenty-app-looot](https://github.com/loootai/twenty-app-looot) |
| Instantly (find, verify, load a campaign) | [looot-instantly](https://github.com/loootai/looot-instantly) |
| Clay (HTTP API column recipes) | [looot-clay-templates](https://github.com/loootai/looot-clay-templates) |
| VS Code, JetBrains, Zed | [looot-vscode](https://github.com/loootai/looot-vscode), [looot-jetbrains](https://github.com/loootai/looot-jetbrains), [looot-zed](https://github.com/loootai/looot-zed) |
| GitHub Actions | [looot-action](https://github.com/loootai/looot-action) |
| Chrome side panel | [looot-chrome](https://github.com/loootai/looot-chrome) |
| Docker images: CLI, MCP bridge | [looot-docker](https://github.com/loootai/looot-docker) |

| Start from a template | Repo |
| --- | --- |
| Domains in, verified work emails out (CSV) | [looot-lead-gen-agent](https://github.com/loootai/looot-lead-gen-agent) |
| Weekly Google rank report for a keyword list | [looot-seo-monitor](https://github.com/loootai/looot-seo-monitor) |
| Open-source Clay-style enrichment tables (Next.js + Supabase) | [looot-tables](https://github.com/loootai/looot-tables) |
| Buying signals on target accounts: news, hiring, page changes (Next.js + Supabase) | [looot-watchlist](https://github.com/loootai/looot-watchlist) |
| Local businesses for agencies: Maps search, website gaps, verified emails (Next.js + Supabase) | [looot-local-leads](https://github.com/loootai/looot-local-leads) |
| Brand and competitor monitoring: mentions, Google results, page diffs, reviews, with a cap per monitor (Next.js + Supabase) | [looot-monitor](https://github.com/loootai/looot-monitor) |
| CRM with buying signals built in: pipeline board, contact enrichment, an intent score per account, quote before every call (Next.js + Supabase) | [looot-crm](https://github.com/loootai/looot-crm) |
| SEO workspace: rank tracking, keyword research, SERP snapshots, competitors, backlinks, with a quote before every refresh (Next.js + Supabase) | [looot-seo](https://github.com/loootai/looot-seo) |
| Add company, email, phone columns to any CSV, quote first | [looot-csv-enrich](https://github.com/loootai/looot-csv-enrich) |
| n8n workflows on core nodes: email, company research, signup score, rank check | [looot-n8n-workflows](https://github.com/loootai/looot-n8n-workflows) |
| Recipes: enrichment, research, SEO, scraping | [looot-cookbook](https://github.com/loootai/looot-cookbook) |
| 12 use cases with prices and copy-paste prompts | [awesome-looot-use-cases](https://github.com/loootai/awesome-looot-use-cases) |
| Open-source GTM engineering tools, curated | [awesome-gtm](https://github.com/loootai/awesome-gtm) |
| The whole catalog as a 3D map ([open it](https://loootai.github.io/catalog-galaxy/)) | [catalog-galaxy](https://github.com/loootai/catalog-galaxy) |
| GPT Researcher retriever plugin | [gptr-looot-retriever](https://github.com/loootai/gptr-looot-retriever) |

### Open-source alternatives built on looot

Paid GTM products rebuilt on one looot key, each with a demo mode and a CLI. The price shows before every run.

| Repo | Replaces | Typical run at list price |
| --- | --- | --- |
| [looot-intent](https://github.com/loootai/looot-intent) | 6sense | $0.18 per account |
| [looot-score](https://github.com/loootai/looot-score) | MadKudu | $0.83 to $1.67 per 100 leads |
| [looot-reveal](https://github.com/loootai/looot-reveal) | RB2B, Clearbit Reveal | about $0.08 per 100 new IPs |
| [looot-techstack](https://github.com/loootai/looot-techstack) | BuiltWith, Wappalyzer | $1.89 per 100 domains |
| [looot-signals](https://github.com/loootai/looot-signals) | TheirStack, Harmonic | up to $0.53 per run of five triggers |
| [looot-lookalike](https://github.com/loootai/looot-lookalike) | Ocean.io | up to $0.21 for 6 seeds |
| [looot-ads](https://github.com/loootai/looot-ads) | Foreplay | about $0.11 for 5 competitors |
| [looot-reviews](https://github.com/loootai/looot-reviews) | ReviewTrackers | up to $0.015 for 5 companies on Google Maps |
| [looot-battlecards](https://github.com/loootai/looot-battlecards) | Klue, Crayon | $0.076 for 5 competitors |
| [looot-mentions](https://github.com/loootai/looot-mentions) | Brand24, Mention | $0.0066 per keyword per run |
| [looot-warm-leads](https://github.com/loootai/looot-warm-leads) | Gojiberry | up to $0.25 per run (new role only), $0.65 with hiring and funding triggers |

[looot.ai](https://looot.ai) · [Docs](https://docs.looot.ai) · [Privacy](https://looot.ai/privacy) · [Terms](https://looot.ai/terms) · [Contact](https://looot.ai/contact)
