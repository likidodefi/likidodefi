### Hey — I'm building [RiskState](https://riskstate.ai)

Deterministic risk governance for autonomous crypto trading agents.

One API call before every trade. Your agent gets: policy level, max position size, leverage limits, blocked actions.

```
POST /v1/risk-state { "asset": "BTC" }

→ max_size: 35%  →  leverage_max: 1.5x  →  blocked: ["LEVERAGE_GT_2X"]
```

Not a signal. Not an oracle. A policy engine that tells agents **how much risk is allowed**.

---

**Stack:** 30+ real-time signals (macro, on-chain, derivatives, DeFi) · 5-level policy engine · SHA-256 audit trail · BTC + ETH

**Integrate via:** [REST API](https://github.com/likidodefi/riskstate-docs/blob/main/docs/api-v1.md) · [SKILL.md](https://github.com/likidodefi/riskstate-docs/blob/main/SKILL.md) · [MCP Server](https://github.com/likidodefi/riskstate-mcp) (`npx @riskstate/mcp-server`)

**Listed on:** [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) · [Glama](https://glama.ai) · [ClawHub](https://clawhub.ai) · [skills.sh](https://skills.sh) · [LobeHub](https://lobehub.com)

---

<a href="https://riskstate.ai">riskstate.ai</a> · <a href="https://github.com/likidodefi/riskstate-docs">Docs</a> · <a href="https://x.com/riskstate_ai">@riskstate_ai</a>

<sub>API v1.2.0 · Free during beta · Built by Digital Venture Asset LLC</sub>
