# 🦡 HONEY BADGER ($HNYBG)

![Logo](https://raw.githubusercontent.com/HNYBG/hnybg-assets/main/logo-256.png)

[![Network: Base](https://img.shields.io/badge/network-Base-blue?logo=coinbase)](https://base.org)
[![Token Standard: ERC20](https://img.shields.io/badge/token-ERC20-green)](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)
[![License: MIT](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)
[![Website](https://img.shields.io/badge/visit-hnybg.io-orange)](https://hnybg.io)

---

## 💬 About

Hey there 👋  
This repo holds the **official logo** and **token metadata** for **HONEY BADGER ($HNYBG)** — a community-driven ERC20 token running on **Base Mainnet**.

We keep everything here public so that wallets, explorers, and partners can easily integrate $HNYBG visuals and info.  
Whether you’re a developer, holder, or just curious — you’re in the right place. 🦡✨

---

## 🪙 Token Details

| Field | Value |
|-------|-------|
| **Token Name** | HONEY BADGER |
| **Symbol** | HNYBG |
| **Decimals** | 18 |
| **Network** | Base Mainnet |
| **Chain ID** | 8453 |
| **Contract** | [`0x6EdA5E0EDCc40bC8F492eeF7f270880Ea9362dB6`](https://basescan.org/token/0x6EdA5E0EDCc40bC8F492eeF7f270880Ea9362dB6) |
| **Website** | [https://hnybg.io](https://hnybg.io) |
| **Total Supply** | 1,000,000,000,000 HNYBG |
| **Tax Structure** | 1% burn + 4% treasury (reduced over time) |
| **Treasury Wallet** | `0x4A3964C75ad93453731afbf48318f72d28B43ba6` |

---

## 🧩 Token List (for integrations)

This repo also includes a `tokenlist.json` file following the [Uniswap Token Lists standard](https://tokenlists.org/).  
You can reference it directly in your app, aggregator, or custom list manager.

```json
{
  "name": "HONEY BADGER Official List",
  "timestamp": "2025-10-08T00:00:00Z",
  "version": { "major": 0, "minor": 1, "patch": 0 },
  "tokens": [
    {
      "chainId": 8453,
      "address": "0x6EdA5E0EDCc40bC8F492eeF7f270880Ea9362dB6",
      "name": "HONEY BADGER",
      "symbol": "HNYBG",
      "decimals": 18,
      "logoURI": "https://raw.githubusercontent.com/HNYBG/hnybg-assets/main/logo-256.png",
      "extensions": {
        "website": "https://hnybg.io"
      }
    }
  ]
}
