# LumaChain – Exchange Listing Technical Package

This document summarizes the main technical and transparency information that centralized and decentralized exchanges may need in order to integrate and list the **LumaChain (LUMA)** token.

---

## 1. Project Overview

**LumaChain (LUMA)** is an ERC-20 token deployed on the Polygon PoS network.  
The ecosystem roadmap includes infrastructure (LumaNetwork), payments (LumaPay), a Luma-based distribution token and RealFi-oriented modules focused on real-world use cases.

This repository provides:

- Full source code for the core smart contracts  
- On-chain transparency (locks, treasury, supply)  
- Technical documentation for integrations

Nothing in this document constitutes financial advice or an investment offer.

---

## 2. Token Details

- **Name:** LumaChain  
- **Symbol:** LUMA  
- **Standard:** ERC-20  
- **Network:** Polygon PoS (Mainnet)  
- **Chain ID:** 137  
- **Contract address:** `0x453453096e669a8a48772287210098faA55bd64b`  
- **Decimals:** 18  
- **Total supply:** 300,000,000 LUMA  

For ABI and contract source code, see the `Contratos/` directory in this repository.

---

## 3. Supply, Distribution and Locks

A detailed description of tokenomics is available in:

- `Documentos/Tokenomics.md`  
- `Documentos/Transparency.md`  
- `Dados/Supply.json`  

Key lock information (summary):

- **Team & Development wallet:**  
  - Wallet: `0x6D5dAbdA8d16484A7026DE4d9229beAed59fF7b3`  
  - Locked amount: 60,000,000 LUMA  
  - Timelock contract: `0xeb92f951f5a486e8d65569e737baf5b5fd494284`  
  - Lock until approximately April 2026  

- **Treasury & Ecosystem wallet:**  
  - Wallet: `0x9853A0B88Fce5DD672678b5986d96AdD4bD22288`  
  - Locked amount: 30,000,000 LUMA  
  - Timelock contract: `0xE022379FbA9E3CE816DC973494791072b3ebE5C9`  
  - Lock until approximately April 2025  

All official addresses are consolidated in `ENDEREÇOS_DO_CONTRATO.md`.

Circulating supply and allocation breakdown are maintained in `Dados/Supply.json` and may be updated over time.

---

## 4. Liquidity and Trading

- **Main DEX pool:** `0xebad4840bf2a7eeeb64918bb71f48ab9db4400ce` (Polygon)  

Additional pools or liquidity venues, if created in the future, will be documented in:

- `Dados/Pools.json`  
- `ENDEREÇOS_DO_CONTRATO.md`  

---

## 5. Roadmap (High-Level)

A high-level technical roadmap is available in `Documentos/Roadmap.md`, currently including:

1. Token Foundation  
2. Integrations & Listings  
3. LumaNetwork (core infrastructure)  
4. LumaPay (payments)  
5. Luma-based distribution token (subject to compliance)  
6. RealFi modules (penultimate phase)  
7. Tools for community & developers  

All roadmap items are indicative and may change over time. None of them imply promised returns or fixed yields.

---

## 6. Risk and Legal Disclaimers

Risk and transparency disclosures are detailed in:

- `Documentos/Transparency.md`  
- `SEGURANÇA.md` (Security Policy)  

Key points:

- LUMA is **not** a guaranteed-return product.  
- Interacting with smart contracts involves risk of partial or total loss of funds.  
- Nothing in this repository or its documents should be interpreted as:
  - financial advice,  
  - a public offering of securities,  
  - or a promise of profits.

Exchanges are encouraged to perform their own legal, technical and compliance due diligence.

---

## 7. Technical Contacts

For technical integration questions, security notifications or listing-related coordination, please contact:
  
- **Security reports:** `lumachaincrypto@gmail.com`  

(Replace with the official project emails.)

---

This document may be updated as the project evolves. Exchanges should always refer to the latest version in the official repository.
