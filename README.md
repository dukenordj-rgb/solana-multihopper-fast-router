# Solana MultiHopper Fast Router

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Network: Solana Mainnet](https://img.shields.io/badge/Solana-Mainnet-black?logo=solana)](https://solana.com)
[![Superteam Earn: Bounty Ready](https://img.shields.io/badge/Superteam%20Earn-MultiHopper%20Challenge-blue)](https://earn.superteam.fun)

A high-performance Solana multi-hop payment routing and liquidity execution engine built for the **MultiHopper Build & Route Challenge** ($5,000 guaranteed + up to $50,000 revenue share).

---

## ⚡ Overview

Moving capital across Solana with minimal slippage and rapid settlement requires intelligent split-routing. 
**Solana MultiHopper Fast Router** dynamically analyzes on-chain AMM pools (Raydium, Orca, Whirlpools) to construct optimal multi-hop paths for micro-payments, automated AI agent settlements, and cross-token disbursements.

---

## 🚀 Key Features

1. **Split-Hop Routing Engine:**
   - Decomposes high-volume trades across multiple pools to avoid price impact.
   - Micro-second routing path calculation matching active leader slot windows.
2. **Built-in Revenue Share:**
   - Accrues native protocol fees on every routed hop, directed to designated settlement wallets.
3. **Agent-to-Agent Micro-Payment Support:**
   - Ready for integration with autonomous bots, paying via native SPL USDC.

---

## ⚙️ Quickstart

Run with Python 3.10+:

```bash
python router.py
```

Or deploy as a background container:

```bash
docker compose up -d --build
```

---

## 💼 Developer & Wallet Credentials

- **Developer:** NILSON (`dukenordj-rgb`)
- **Superteam Earn Profile:** NILSON
- **Destination Solana Wallet:** `Gu8RhvagFJVZar4NvWdcD1Q4m2GXMXZca271q8iU79B3`
- **Secondary Wallet:** `3x1JsXS6PW47CQ4EctVyUHGuq1WNZ5tm22gerX1YFFrm`

---

## 📄 License
MIT License. Open source.
