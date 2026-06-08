# Drift BET Trading Bot

![Status](https://img.shields.io/badge/status-⚪_roadmap-555?style=flat-square)
[![Engine](https://img.shields.io/badge/engine-shared_core-6e40c9?style=flat-square)](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits)
[![Rust](https://img.shields.io/badge/rust-1.70+-orange.svg?style=flat-square&logo=rust)](https://www.rust-lang.org/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)

> Automated **Drift BET trading bot** — Solana. Part of the [Prediction Market Toolkits](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits) suite: one execution core, one risk layer, every venue.

**Drift BET** is on the **adapter-driven roadmap** — the engine is built; the Drift BET adapter is in the queue. Trade it and want it prioritized? [Reach out](https://t.me/HarrierOnChain) and it moves up.

---

## Strategies on Drift BET

These bots run on Drift BET through a single venue adapter on the shared engine — same risk controls, same TUI, full dry-run support.

| Strategy |
|----------|
| ⚡ **BTC 5m / 15m / 1hr Arbitrage** — speed on short-window BTC Up/Down (~42ms end-to-end) |
| 📊 **Orderbook Imbalance** — the signal *is* the order book, no external feeds |
| 💰 **Market Making** — be the house, not the gambler (two-sided GTD, inventory skew) |
| ⚡ **On-Chain Whale Signal** — 3–30s ahead of the public positions API |

> Want a strategy not listed here on Drift BET? Adapter coverage is demand-driven — [ask](https://t.me/HarrierOnChain).

---

## One engine, every venue

This repo is the **Drift BET** entry point. The execution core, risk layer, and all 20+ venue adapters live in the main toolkit:

### 👉 **[Prediction-Markets-Trading-Bot-Toolkits](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits)** — the full suite

| | |
|---|---|
| **Order execution** | < 100ms end-to-end |
| **Event processing** | < 1ms per event |
| **Safety** | Circuit breaker · depth guard · dry-run · trade floor |
| **Venues** | Polymarket · Kalshi · Limitless live — 20+ on roadmap |

Adding a venue means writing **one adapter** — not rebuilding a bot.

---

## Get access

| Platform | Link |
|----------|------|
| **Full toolkit** | [Prediction-Markets-Trading-Bot-Toolkits](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits) |
| **Telegram** | [@HarrierOnChain](https://t.me/HarrierOnChain) |
| **Discussions** | [GitHub Discussions](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits/discussions) |

*Response time is typically within a few hours.*

---

## Related venues

[Polymarket](https://github.com/HarrierOnChain/Polymarket) · [Kalshi](https://github.com/HarrierOnChain/Kalshi) · [OG.com](https://github.com/HarrierOnChain/OG.com) · [Zeitgeist](https://github.com/HarrierOnChain/Zeitgeist)

> Browse the full venue directory in the [main toolkit →](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits#venue-coverage)

---

## Disclaimer

> Trading prediction markets involves real financial risk. This software is provided as-is, without warranty. It is not financial advice. Always test with `enable_trading: false` before deploying real capital. Ensure compliance with Drift BET's terms of service and your local regulations.

---

<div align="center">

**Drift BET trading bot · built on the [Prediction Market Toolkits](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits) engine**

[![Telegram](https://img.shields.io/badge/Telegram-@HarrierOnChain-26A5E4?style=flat-square&logo=telegram)](https://t.me/HarrierOnChain)

</div>
