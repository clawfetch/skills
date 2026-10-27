# ClawFetch agent skills

[![skills.sh](https://skills.sh/b/clawfetch/skills)](https://skills.sh/clawfetch/skills)

Agent skills for [ClawFetch.ai](https://clawfetch.ai), the web intelligence API for AI agents: stealth fetch to markdown, JavaScript rendering, 17 structured extractors, document parsing, company enrichment, multi-source research and domain checks. Pay per call with USDC on Base over x402 v2. No API key, no subscription.

## Install

```bash
npx skills add clawfetch/skills
```

Works with Claude Code, Cursor, Codex, OpenClaw, Hermes and every other agent that reads `SKILL.md`.

## Skills

| Skill | What it covers |
|---|---|
| [`clawfetch`](skills/clawfetch/SKILL.md) | Wallet setup, paying with `@x402/fetch`, all nine routes with prices, extractor list, error handling |

## Other ways to use ClawFetch

- MCP server: `npx @clawfetch/mcp` ([clawfetch/clawfetch-mcp](https://github.com/clawfetch/clawfetch-mcp))
- TypeScript SDK: `@clawfetch/sdk` ([clawfetch/sdk](https://github.com/clawfetch/sdk))
- Python SDK: `pip install clawfetch` ([clawfetch/sdk-python](https://github.com/clawfetch/sdk-python))
- LangChain, LlamaIndex, CrewAI and Vercel AI SDK packages: [clawfetch/integrations](https://github.com/clawfetch/integrations)
- OpenAPI: https://api.clawfetch.ai/openapi.json

## License

MIT
