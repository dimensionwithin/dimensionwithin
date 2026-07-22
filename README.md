# Joshua Kriegbaum — DimensionWithin

**AI / Agent Engineer × systematic crypto-trading developer.**
Funded trader turning a live, self-sustaining trading edge into rigorously-tested
automated infrastructure and LLM-agent tooling (MCP).

I build two kinds of things: **LLM/agent systems** (MCP servers, tool-calling agents,
production LLM pipelines) and **crypto trading infrastructure** (backtesting, execution,
risk gating). Most of my work ships with strict typing, heavy test coverage, and explicit
safety gates before anything touches real capital.

---

## What I focus on

- **Agentic / LLM tooling** — from-scratch MCP servers, tool-calling agents, and production
  LLM pipelines with prompt-caching, mock modes, and human-in-the-loop gates.
- **Quant / trading systems** — Hyperliquid & Polymarket integrations, backtesting and
  execution infrastructure, statistically-gated strategy promotion.
- **Shipping real software** — a live production platform, packaged desktop tools with real
  users, strict typing (mypy/TS strict), and high test coverage.

---

## Selected projects

### dimensionwithin.cloud — live production market hub
A modular "markets × data" hub that surfaces live Hyperliquid market data through a
self-built proxy/cache layer. Fastify + TypeScript backend implementing a generic
TTL + stale-while-revalidate + single-flight cache over ~25 upstream sources behind one
typed `Source` contract; Vite + React SPA frontend; SQLite snapshot history; Dockerized
behind Traefik with TLS. **Live:** https://dimensionwithin.cloud
`TypeScript` · `Fastify` · `React/Vite` · `SQLite` · `Docker/Traefik`

### Matrix Auto Cutter — automated video post-production
A local desktop app that automates the tedious first pass of editing long market-analysis
videos: transcribes locally, trims dead time and filler, **protects chart-reading pauses**
so nothing important gets cut, plans CTA overlays, and produces an EDL/JSON/HTML review
before final render. Built as a phased, side-effect-audited pipeline. Runs fully offline —
no cloud, no internet required for transcription.
`Python 3.12` · `Pydantic v2` · `mypy --strict` · `100% branch coverage` · `Hypothesis (property-based tests)`

### Back-Catalog Thumbnail Agent — real LLM pipeline with human sign-off
An automation pipeline that regenerates thumbnails across a full YouTube back-catalog: pulls
metadata, decides headline + stance via the Claude API, renders through a Playwright/HTML
compositor, builds a contact sheet for review, and **publishes only after manual approval**.
Includes prompt-caching for cost control and a deterministic mock mode so the whole pipeline
runs credential-free in tests.
`Node.js` · `Anthropic Claude API` · `YouTube Data API v3 (OAuth)` · `Playwright`

### Advanced LLM System — *private, walkthrough on request*
A local quant-research platform exposed to an LLM agent through a from-scratch **MCP server**
with a hard read/write trust boundary — the agent gets *exactly the same gated tools* as a
human operator, never more. Strategy promotion is gated by real academic statistics
(Deflated Sharpe Ratio, walk-forward validation), and the operator cockpit is event-sourced.
Repo is private to protect the underlying strategies; happy to give a live walkthrough or
temporary read access in an interview.
`Python` · `MCP (official SDK)` · `TypeScript` · `event-sourcing` · `LLM tool-calling`

---

## Trading track record

- **Funded Trader — Breakout** (crypto prop firm): passed the evaluation and trade a
  risk-managed funded account (2026).
- **Top 1% of all traders — Polymarket** (2025 year-end ranking).
- Self-employed; systematic and discretionary crypto trading is my primary income.

---

## Background

- **Blockchain Professional** certification — Blockchain Akademie (2023).
- **Founder & host, DimensionWithin** — a German-language markets-education channel and
  community (2K+ subscribers, since 2024).

---

## Tech

**Languages:** Python · TypeScript · JavaScript (Node)
**AI / agents:** MCP · tool-calling · Anthropic API · OpenRouter · local inference (whisper.cpp)
**Backend / web:** FastAPI · Fastify · React/Vite · SQLite · Docker/Traefik · Playwright
**Discipline:** mypy/TS strict · ruff · pytest · property-based testing · staged safety gates

---

## Reach me

- Live project: https://dimensionwithin.cloud
- LinkedIn: *(add link)*
- Email: dimensionwithinde@gmail.com
