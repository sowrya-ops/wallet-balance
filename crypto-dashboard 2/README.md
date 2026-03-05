# 🌐 Multichain Portfolio Tracker

A live, multi-team crypto portfolio dashboard deployable to Vercel in one click.

## Teams & Chains

| Team | Chains |
|------|--------|
| 🇮🇳 INR | BSC · Polygon · Ethereum · Arbitrum · Base · Solana · TRON · TON · Ronin · Aptos |
| 🇵🇭 PHP | BSC · Polygon · Ethereum · Arbitrum · Base · Solana · TRON · Ronin |
| 🇮🇩 IDR | BSC · Polygon · Ethereum · Arbitrum · Base · Solana · TRON · Ronin |

## Features

- 🔄 Live balances fetched on page load + manual refresh
- 👥 Team switcher — view INR / PHP / IDR individually or all at once
- 🔗 Chain filter tabs — drill down by network
- 💰 USD values via CoinGecko (free, no key)
- 📊 Per-team stats cards + per-network breakdown cards
- 🎨 Dark themed, Syne + Space Mono fonts

## Deploy to Vercel

### Option 1 — Drag & Drop (60 seconds)
1. Go to [vercel.com](https://vercel.com) → **Add New Project**
2. Drag this folder onto the page
3. Click **Deploy** → get your URL instantly

### Option 2 — GitHub Integration (recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → Import from GitHub
3. Select the repo → **Deploy**
4. Every `git push` auto-deploys

### Option 3 — Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

## APIs Used (all free, no key required)

| Chain | API |
|-------|-----|
| BSC, Polygon, ETH, Arbitrum, Base | [Ankr Multichain](https://ankr.com) |
| Solana | Public Solana RPC |
| TRON | [TronGrid](https://trongrid.io) |
| TON | [TonCenter](https://toncenter.com) + [TonAPI](https://tonapi.io) |
| Ronin | Ronin Public RPC |
| Aptos | [Aptos Labs REST API](https://api.mainnet.aptoslabs.com) |
| Prices | [CoinGecko](https://coingecko.com) |

## Files

```
├── index.html      # Single-file dashboard (all HTML + CSS + JS)
├── vercel.json     # Vercel deployment config
└── README.md       # This file
```
