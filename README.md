# shioaji-stable-trading-framework
Production-oriented auto trading for Taiwan stock market using Shioaji API.  這是一個專門為台灣股市打造的自動交易框架，核心用 Shioaji API。它能幫你接行情、跑策略、控風險，最後自動下單，整套流程都能在生產環境穩定運行。

## Focus

- Stable intraday auto trading
- Auto reconnect mechanism
- Tick integrity monitoring
- Real-time logging
- Risk control architecture
- VPS deployment

---

## Why This Project?

Most retail trading bots focus only on strategy logic.

However, real-world trading systems must also handle:

- API disconnects
- TCP 10053 errors
- Tick interruptions
- Session expiration
- Network instability
- Market open volatility

This project focuses on building stable and production-ready trading systems.

---

## Core Modules

### Reconnect Manager
Handles:
- TCP reconnect
- Session recovery
- Auto retry

### Tick Monitor
Detects:
- Tick interruption
- Delayed data
- Missing market feed

### Logger System
Provides:
- Real-time logs
- Error tracking
- Daily reports

---

## Roadmap

- [ ] Auto reconnect manager
- [ ] Tick stream monitor
- [ ] VPS deployment guide
- [ ] Dashboard monitoring
- [ ] Risk control module

---

## Disclaimer

This project is for educational and research purposes only.

Trading involves financial risk.
Use at your own risk.
