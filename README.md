# 👁️ Agentic Eye — Viral Content Intelligence for the Agent Economy

> **ERC-8004 Agent #1865 on Celo Mainnet** | Track 1 (Best Agent on Celo) + Track 3 (Highest 8004scan Rank)

![Agentic Eye](https://agenticeye.co/og-image.png)

---

## What is Agentic Eye?

Agentic Eye is a **content intelligence agent** that predicts which content will go viral — before it does.

Any AI agent, brand, or creator calls the API with a topic or niche. Agentic Eye fires 17 live data sources simultaneously, scores the viral probability using STEPPS framework, and returns actionable intelligence in under 12 seconds.

**Not trained on stale data. Fetched from reality — right now.**

---

## Why It's an Agent (Not Just an API)

- Registered on Celo Mainnet as **ERC-8004 Agent #1865**
- Discoverable by any agent in the ecosystem via `agenticeye.co/agent.json`
- Accepts **x402 payments** in cUSD, USDC, USDT on Celo — agent-to-agent commerce
- **Venice TEE inference** — zero data retention, private cognition
- **Self Protocol ZK identity** — Agent #52, verified on Celo
- **A2A compliant** — other agents can hire Agentic Eye programmatically
- Cooperates with **Loopuman** (Agent #17) — the human compute layer

---

## Live Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `agenticeye.co` | GET | Agent home + capability manifest |
| `agenticeye.co/analyze` | POST | Full viral intelligence (17 sources) |
| `agenticeye.co/score` | GET/POST | Pre-publish STEPPS hook scoring (free) |
| `agenticeye.co/titles` | GET/POST | Viral title generator (free) |
| `agenticeye.co/compare` | GET/POST | A/B hook comparison (free) |
| `agenticeye.co/hot` | GET | What's trending right now (free) |
| `agenticeye.co/trending-now` | GET | Cross-platform trend signals |
| `agenticeye.co/agent.json` | GET | ERC-8004 agent card |
| `agenticeye.co/skill.md` | GET | Agent skill manifest |
| `agenticeye.co/mcp` | GET | MCP discovery endpoint |

---

## How to Call It (Agent-to-Agent)

```bash
# Free score check — no payment needed
curl "https://agenticeye.co/score?hook=This+AI+is+replacing+your+job&platform=tiktok"

# Full analysis — x402 payment via Celo
curl -X POST https://agenticeye.co/analyze \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_TOKEN" \
  -d '{
    "niche": "AI agents replacing humans",
    "location": "US",
    "idea_count": 5
  }'
```

---

## 17 Live Data Sources

Agentic Eye fires all sources simultaneously via `asyncio.gather()`:

1. YouTube Comments (YouTube Data API v3)
2. TikTok Comments (ScrapeCreators)
3. Reddit Discussions (Free JSON API)
4. Google Trends (Tavily + native)
5. YouTube Autocomplete
6. Google Autocomplete
7. Google News RSS
8. Quora Questions
9. Amazon Autocomplete
10. YouTube Trending Feed
11. Spotify/iTunes Podcast Titles
12. HackerNews (early tech signals)
13. Twitter/X Signals (Tavily)
14. LinkedIn Signals (Tavily)
15. Instagram Signals (Tavily)
16. Deepgram Audio Transcription
17. Venice AI Private Inference

---

## ViralEdge Scoring (STEPPS Framework)

Every piece of content is scored across 6 psychological dimensions:

| Dimension | Weight | What it measures |
|-----------|--------|-----------------|
| **S**ocial Currency | 15% | Does sharing make you look smart? |
| **T**riggers | 15% | Is it top of mind? |
| **E**motion | 25% | High-arousal emotion = shares |
| **P**ublic | 15% | Is it visible/observable? |
| **P**ractical Value | 20% | Is it useful enough to save? |
| **S**tory | 10% | Is there a narrative? |

Combined with Comment Velocity, Cross-Platform Echo, and Trend Momentum → **ViralEdge Score 0–100**.

---

## On-Chain Identity

| Property | Value |
|----------|-------|
| Agent Name | Agentic Eye |
| ERC-8004 ID | #1865 |
| Chain | Celo Mainnet |
| Chain ID | 42220 |
| Agent Wallet | `0x02e97e243204780842d5cA34dFEF465A959b18b3` |
| 8004scan | [View Agent](https://8004scan.io/agents/celo/1865) |
| Self Agent ID | #52 (ZK verified) |
| Registry | `0x8004A169FB4a3325136EB29fA0ceB6D2e539a432` |

---

## Payment (x402 — Agent Native)

Agentic Eye accepts payments via the **x402 protocol** — no accounts, no invoices, no friction.

| Token | Network | Contract |
|-------|---------|----------|
| cUSD | Celo Mainnet | `0x765DE816845861e75A25fCA122bb6898B8B1282a` |
| USDC | Celo Mainnet | `0xcebA9300f2b948Ad130e0Be0368f1AC7b59dA51c` |
| USDT | Celo Mainnet | `0x48065fbbe25f71C9282ddf5e1cD6D6A887483D5e` |
| USDC | Base Mainnet | `0x833589fCD6eDb6E08f4c7C32D4f71b54bdA02913` |

Pricing:
- 1 analysis: $0.50
- 5 analyses: $1.50
- 10 analyses: $3.00
- 25 analyses: $8.00

---

## Privacy — Venice TEE

All inference runs on **Venice AI** with zero data retention.

- Your content strategy is never stored
- Never logged
- Never used to train models
- Private cognition → public trustworthy output

---

## Cooperation with Loopuman

Agentic Eye integrates with **Loopuman** (ERC-8004 Agent #17):

- When human execution is needed, Agentic Eye posts tasks to Loopuman
- Workers receive tasks via WhatsApp/Telegram, paid in cUSD in ~8 seconds
- Creates a closed loop: AI intelligence → human action → on-chain proof

---

## Agent Discovery

```json
{
  "name": "Agentic Eye",
  "version": "3.2.0",
  "erc8004_id": "1865",
  "chain": "celo",
  "url": "https://agenticeye.co",
  "mcp": "https://agenticeye.co/mcp",
  "skill": "https://agenticeye.co/skill.md",
  "a2a": "https://agenticeye.co/.well-known/agent-card.json"
}
```

---

## Hackathon Tracks

- **Track 1 — Best Agent on Celo:** Real, live, deployed agent with genuine utility. Paying users. x402 payments. Venice TEE. Self Protocol ZK identity. A2A compliant.
- **Track 3 — Highest 8004scan Rank:** Agent #1865 consistently ranked in top 5 on 8004scan for Celo (score 93.85).

---

## Links

- 🌐 Live: [agenticeye.co](https://agenticeye.co)
- 🤖 8004scan: [8004scan.io/agents/celo/1865](https://8004scan.io/agents/celo/1865)
- 📦 npm: [agentic-eye](https://npmjs.com/package/agentic-eye)
- 🐦 X: [@agenticeye](https://x.com/agenticeye)
