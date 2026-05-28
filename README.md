# ExNexus

Building **[ExNexus](https://exnexus.co)** — an institutional-grade trading aggregator for crypto and stocks.

## What it does
A security-first multi-exchange aggregator that unifies portfolios, charts, and trading across centralized and decentralized exchanges. Multi-exchange routing (Best Price / Single / Split), AI-powered market intelligence, and unified portfolio across all asset types.

## Key principle
**No custody. No withdrawals. No plaintext keys.** ExNexus is the observer/aggregator layer above exchanges — never another exchange.

## Connected exchanges
Bybit · Binance (spot + futures) · Gate.io · Alpaca (paper + live)

## Stack
- **Frontend:** HTML/JS/Tailwind, deployed via Cloudflare Pages
- **Edge:** Cloudflare Workers (auth signing, request routing)
- **Infrastructure:** Hetzner VPS (Node.js + Caddy) for fixed-IP exchange API access
- **Data:** Multi-exchange API aggregation, TradingView charts, real-time price cache

## Status
Active development · Pre-launch

🌐 **Live terminal:** [exnexus.co/terminal](https://exnexus.co/terminal)
🌐 **Company:** [exnexus.co](https://exnexus.co)
📧 **Contact:** contact@exnexus.co
