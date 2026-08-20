# Enes Eserkan — Founder & Engineer at Automatia BCN

I build software products end to end: product design, backend, UI, CI/CD, billing and licensing, deployment. Based in Barcelona, relocating to Perth, Australia — open to software engineering roles. Turkish / English / Spanish.

## What I'm building

**ABS Studio** — an AI code editor (VS Code fork) with a self-hosted orchestration engine. Your code stays on your machine.

- Every proposed edit is graded by a judge model before you see it — score and reasoning, not a diff to accept on faith.
- A code graph answers "what else does this touch?" so the blast radius of a change is a number, not a surprise in CI.
- Checks run in the OS's own sandbox (seatbelt / bubblewrap / restricted token). When no sandbox is available it says so — "no checks ran" is never reported as "passed".
- Undo is checkpoint-based (before the agent, not before the last attempt), and commits carry evidence of what was graded and what ran.

Repo: [automatiabcn/abs](https://github.com/automatiabcn/abs) — source-available (BUSL-1.1), 2,600+ tests, CI + CodeQL + nightly Lighthouse.

## Open-source MCP servers

TypeScript, MIT, tests and CI on every one.

| Repository | What it does |
|---|---|
| [leadpipe-mcp](https://github.com/automatiabcn/leadpipe-mcp) | Lead qualification: ingest, enrich, score 0–100, export to CRM |
| [invoiceflow-mcp](https://github.com/automatiabcn/invoiceflow-mcp) | PDF invoices, late-payment risk, cash-flow tracking |
| [shopops-mcp](https://github.com/automatiabcn/shopops-mcp) | Inventory forecasting, pricing, RFM, anomaly detection for Shopify / WooCommerce |
| [adops-mcp](https://github.com/automatiabcn/adops-mcp) | Google Ads & Meta Ads analytics |
| [mcp-server-starter](https://github.com/automatiabcn/mcp-server-starter) | Minimal production-ready MCP template: stdio + HTTP, Zod tools, tests, CI |
| [ai-arena-playground](https://github.com/automatiabcn/ai-arena-playground) | Compare 11 models side by side, self-hosted |
| [cacheflow-ai](https://github.com/automatiabcn/cacheflow-ai) | AI API cost optimizer: caching + free-tier routing |

## How I work

- Verify before claiming done — read the output back, don't trust the green checkmark.
- Write tests that can actually fail; prove new tests with a mutation.
- Honest UI states: a check that didn't run is reported as "didn't run".
- Small, reversible changes; every fix grepped across all of its siblings.

## Stack

```text
TypeScript / Node · Python (FastAPI) · Next.js · Svelte
PostgreSQL · SQLite · Qdrant · Docker · GitHub Actions · Cloudflare Workers · Stripe
LLM providers: Anthropic · Groq · Gemini · Cohere · Cloudflare AI · local Ollama / MLX
```

## Smaller projects

[autoflow-n8n-workflows](https://github.com/enzoemir1/autoflow-n8n-workflows) · [n8n-prompt-library](https://github.com/enzoemir1/n8n-prompt-library) · [n8n-cost-calculator](https://github.com/enzoemir1/n8n-cost-calculator) ([live demo](https://enzoemir1.github.io/n8n-cost-calculator/)) · [n8n-telegram-approval](https://github.com/enzoemir1/n8n-telegram-approval) · [free-ai-prompts](https://github.com/enzoemir1/free-ai-prompts)

## Contact

[automatiabcn.com](https://automatiabcn.com) · [x.com/automatiabcn](https://x.com/automatiabcn) · info@automatiabcn.com
