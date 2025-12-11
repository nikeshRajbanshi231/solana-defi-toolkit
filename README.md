<div align="center">

<img src="https://raw.githubusercontent.com/solana-labs/token-list/main/assets/mainnet/So11111111111111111111111111111111111111112/logo.png" width="120" alt="Solana">

# 🛠️ Solana DeFi Toolkit

### Portfolio Tracker, Yield Optimizer & Trading Utilities

[![Solana](https://img.shields.io/badge/Solana-9945FF?style=for-the-badge&logo=solana&logoColor=white)](https://solana.com)
[![DeFi](https://img.shields.io/badge/DeFi-Tools-green?style=for-the-badge)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

<br>

💰 **Track portfolio** | **Optimize yields** | **Automate trading** | **Multi-DEX support**

<br>

[Quick Start](#-quick-start) · [Features](#-features) · [Configuration](#%EF%B8%8F-configuration) · [FAQ](#-faq)

</div>

---

## 🎯 What is Solana DeFi Toolkit?

A comprehensive suite of DeFi tools for Solana. Track your portfolio across wallets, find the best yields, and automate your trading strategies.

<div align="center">

| Manual DeFi                        | With DeFi Toolkit          |
| ---------------------------------- | -------------------------- |
| ❌ Track multiple wallets manually | ✅ Unified portfolio view  |
| ❌ Miss best yield opportunities   | ✅ Auto yield optimization |
| ❌ Manual swaps on each DEX        | ✅ Best route aggregation  |
| ❌ No performance tracking         | ✅ PnL analytics           |

</div>

---

## ✨ Features

<div align="center">

| Feature                  | Description                     |
| ------------------------ | ------------------------------- |
| 📊 **Portfolio Tracker** | Track all tokens across wallets |
| 💰 **Yield Optimizer**   | Find best APY across protocols  |
| 🔄 **DEX Aggregator**    | Best swap routes via Jupiter    |
| 📈 **PnL Analytics**     | Track profit/loss over time     |
| 🔔 **Price Alerts**      | Custom notifications            |
| 🤖 **Auto-compound**     | Reinvest yields automatically   |

</div>

---

## 🚀 Quick Start

### Step 1: Clone & Install

```bash
git clone https://github.com/solana-tools/defi-toolkit.git
cd solana-defi-toolkit
npm install
```

### Step 2: Configure

```bash
cp .env.example .env
```

Edit `.env`:

```env
# Your wallet private key (as JSON array)
PRIVATE_KEY=[your,private,key,array]

# RPC endpoint
RPC_URL=https://api.mainnet-beta.solana.com

# Settings
AUTO_COMPOUND=false
ALERT_THRESHOLD=5
```

### Step 3: Run

```bash
npm start
```

---

## 📖 How It Works

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   1. TRACK            2. OPTIMIZE          3. EXECUTE          │
│   ───────            ──────────           ─────────            │
│                                                                 │
│   • Portfolio        • Find yields        • Auto-swap          │
│   • Token prices     • Compare APY        • Compound           │
│   • PnL history      • Risk analysis      • Rebalance          │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### CLI Interface

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║           🛠️  SOLANA DEFI TOOLKIT v2.0  🛠️                      ║
║                                                                  ║
║          Portfolio • Yields • Trading                           ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝

? Select tool:
  ❯ 📊 Portfolio Tracker
    💰 Yield Optimizer
    🔄 Swap (Jupiter)
    📈 Analytics

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📊 Portfolio Summary
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SOL:     10.5 ($2,100)
USDC:    500 ($500)
RAY:     100 ($150)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Total: $2,750 | 24h: +5.2%
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## ⚙️ Configuration

### Toolkit Settings

```javascript
// config.js
module.exports = {
  portfolio: {
    wallets: ["wallet1...", "wallet2..."],
    refreshInterval: 60, // seconds
  },

  yields: {
    protocols: ["raydium", "orca", "marinade"],
    minAPY: 5,
    autoCompound: false,
  },

  trading: {
    slippage: 1, // percent
    preferredDex: "jupiter",
  },
};
```

### Supported Protocols

| Protocol     | Features          |
| ------------ | ----------------- |
| **Raydium**  | Swaps, LP, Farms  |
| **Orca**     | Swaps, Whirlpools |
| **Jupiter**  | Aggregator        |
| **Marinade** | Liquid Staking    |

---

## 📊 Analytics

- Portfolio value over time
- Token allocation breakdown
- Yield performance tracking
- Transaction history

---

## ❓ FAQ

<details>
<summary><b>Is this free?</b></summary>

Yes! Completely free and open-source.

</details>

<details>
<summary><b>Is my private key safe?</b></summary>

Your private key never leaves your machine.

</details>

---

## ⚠️ Disclaimer

This tool is for **educational purposes only**. DeFi involves risk. Only use funds you can afford to lose.

---

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

---

<div align="center">

**Your complete Solana DeFi companion** 🛠️

[⬆ Back to top](#%EF%B8%8F-solana-defi-toolkit)

</div>
