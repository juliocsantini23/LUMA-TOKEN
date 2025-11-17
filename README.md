# LUMA-TOKEN
Official repository for the LumaChain ecosystem — token contracts, timelocks, token lists, documentation and assets for the LUMA token on Polygon.
# LumaChain (LUMA) – Official Repository

🔗 **Official Website:** https://www.lumachain.com.br

This repository serves as the **official and authoritative source** for all technical, documentation, infrastructure, and integration resources of the **LumaChain (LUMA)** ecosystem.

It centralizes:

- Smart Contracts (ERC-20 + Timelocks)
- Branding Assets (Logos, Icons, SVG/PNG)
- Tokenomics & Supply Transparency
- Documentation for DEX, Wallet & Exchange Integration
- Public Supply API
- Ecosystem Links & Community Channels

---

## 📌 Token Information

| Field | Value |
|-------|-------|
| **Token Name** | LumaChain |
| **Symbol** | LUMA |
| **Network** | Polygon PoS |
| **Contract Address** | `0x453453096e669a8a48772287210098faa55bd64b` |
| **Decimals** | 18 |
| **Total Supply** | 300,000,000 LUMA |
| **Circulating Supply (API)** | https://www.lumachain.com.br/assets/supply.json |
| **Whitepaper (v1)** | https://www.lumachain.com.br/assets/LUMA_Whitepaper_v1.pdf |

---

## 📊 Supply Transparency

LumaChain provides a live JSON endpoint with **total supply, circulating supply, and timestamp updates**.

### **Supply API (Official)**  
➡️ https://www.lumachain.com.br/assets/supply.json

Designed for:

- Exchanges  
- DEX Aggregators  
- Wallets  
- Analytics Platforms  
- Block Explorers  
- Auditors  

---

## 🔐 Locked Wallets Transparency

LumaChain uses public on-chain timelock contracts to secure institutional allocations.

### **Team / Dev Allocation (Locked)**  
- **Wallet:** `0x6D5dAbdA8d16484A7026DE4d9229beAed59fF7b3`  
- **Timelock Contract:** `0xeb92f951f5a486e8d65569e737baf5b5fd494284`  
- **Amount Locked:** 60,000,000 LUMA  
- **Unlock Date:** April 2026  

### **Treasury Allocation (Locked)**  
- **Wallet:** `0x9853A0B88Fce5DD672678b5986d96AdD4bD22288`  
- **Timelock Contract:** `0xE022379FbA9E3CE816DC973494791072b3ebE5C9`  
- **Amount Locked:** 30,000,000 LUMA  
- **Unlock Date:** April 2026  

All allocations are verifiable on the Polygon blockchain.

---

## 💧 Liquidity Pool (DEX)

### **Uniswap (Polygon) – Official LUMA/USDC Pool**

This is the **only official liquidity pool** for LUMA at this time.

- **Pool Address:**  
  `0xa5a8f3E7E30C7A2B49A2c4D5638C2Ad15E847Fd4`

DexScreen link:  
➡️ https://dexscreener.com/polygon/0xa5a8f3e7e30c7a2b49a2c4d5638c2ad15e847fd4

---

## 📈 Market Data & Analytics

### **CoinMarketCap (DEX Tracker)**  
➡️ https://dex.coinmarketcap.com/token/Polygon/0x453453096e669a8a48772287210098faa55bd64b/

### **GeckoTerminal (Official LUMA/USDC Pool)**  
➡️ https://geckoterminal.com/polygon_pos/pools/0xa5a8f3e7e30c7a2b49a2c4d5638c2ad15e847fd4

---

## 📁 Repository Structure

```txt
lumachain/
│
├── README.md
├── LICENSE
│
├── assets/
│   ├── logo.png
│   ├── logo.svg
│   ├── icon-32.png
│   ├── icon-128.png
│   └── brand-guidelines.pdf
│
├── contracts/
│   ├── LumaToken.sol
│   ├── SimpleTokenTimelock_Dev.sol
│   ├── SimpleTokenTimelock_Treasury.sol
│   └── README.md
│
├── docs/
│   ├── whitepaper.md
│   ├── tokenomics.md
│   ├── transparency.md
│   └── integration.md
│
└── data/
    └── supply.json
