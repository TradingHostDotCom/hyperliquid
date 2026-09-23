# TradingHost + Hyperliquid

Build and deploy DeFi perpetual futures bots on [Hyperliquid](https://hyperliquid.xyz) using [TradingHost](https://tradinghost.com).

## What is this?

This repository is an AI-powered development scaffold. Use it as a template (click "Use this template" on GitHub), open your new repo in your AI coding tool (Cursor, Claude, Codex), and tell the AI what you want to build. The rules in `.cursor/rules/` teach the AI everything it needs to know about Hyperliquid and TradingHost to help you create a production-quality trading bot.

Hyperliquid is an on-chain order book DEX for perpetual futures — no KYC, no intermediaries, sub-second execution, and up to 50x leverage. All trading happens on Hyperliquid's custom L1 blockchain.

## Getting Started

1. **Click "Use this template"** → Create a new repository (you can make it private)
2. **Open in Cursor** (or your preferred AI coding tool)
3. **Tell the AI what to build** — e.g. "Build me a market making bot for BTC perps on Hyperliquid"
4. **Set credentials** — add your wallet private key as a TradingHost strategy secret (`HYPERLIQUID_PRIVATE_KEY`); edit non-secret tunables (symbols, testnet) in `config.json`. Secrets are environment variables, never committed to git.
5. **Deploy on TradingHost** — link this repo as a strategy, create a deployment, and you're live

## TradingHost Deployment

1. Create an account at [tradinghost.com](https://tradinghost.com)
2. Link this GitHub repository as a strategy
3. Create a deployment (choose region: London, New York, or Tokyo)
4. Your bot runs 24/7 with persistent storage, monitoring, and real-time logs

## Documentation

- [TradingHost Docs](https://tradinghost.com/docs)
- [Hyperliquid Python SDK](https://github.com/hyperliquid-dex/hyperliquid-python-sdk)
- [Hyperliquid API Docs](https://hyperliquid.gitbook.io/hyperliquid-docs)

## Risk Warning

Trading perpetual futures involves significant risk of loss including liquidation of your entire position. This software is provided as-is with no guarantees. Always test on testnet before trading real funds.
