LumaChain – Integration Guide

This document provides all technical details required to integrate the LumaChain (LUMA) token into wallets, DEXs, dApps, exchanges, indexers and analytic platforms.

⸻

1. Token Contract Information

Network: Polygon PoS
Token Standard: ERC-20
Name: LumaChain
Symbol: LUMA
Decimals: 18
Contract Address: 0x453453096e669a8a48772287210098faa55bd64b

PolygonScan:
https://polygonscan.com/token/0x453453096e669a8a48772287210098faa55bd64b

⸻

2. Adding LUMA to MetaMask
	1.	Open MetaMask
	2.	Click “Import Token”
	3.	Paste the contract: 0x453453096e669a8a48772287210098faa55bd64b
	4.	Confirm

⸻

3. Adding LUMA to WalletConnect Apps

Any WalletConnect-enabled app can integrate the token using the same ERC-20 address:

0x453453096e669a8a48772287210098faa55bd64b

⸻

4. Supply API (for Exchanges & Indexers)

LumaChain provides a public endpoint with total supply, circulating supply and timestamp.

Supply API:
https://www.lumachain.com.br/assets/supply.json

Example JSON:
{
“token”: “LumaChain”,
“symbol”: “LUMA”,
“network”: “Polygon PoS”,
“total_supply”: 300000000,
“circulating_supply”: 25992961.20,
“last_updated”: “2025-10-25T05:55:39Z”
}

Used by:
	•	CoinMarketCap
	•	CoinGecko
	•	Exchanges
	•	Trackers
	•	Bots
	•	Auditors

⸻

5. Liquidity Pool (DEX Integration)

Official Uniswap Pool (Polygon):
Pair: LUMA / USDC
Pool Address: 0xa5a8f3E7E30C7A2B49A2c4D5638C2Ad15E847Fd4

DexScreener:
https://dexscreener.com/polygon/0xa5a8f3e7e30c7a2b49a2c4d5638c2ad15e847fd4
GeckoTerminal:
https://geckoterminal.com/polygon_pos/pools/0xa5a8f3e7e30c7a2b49a2c4d5638c2ad15e847fd4

⸻

6. Smart Contract Infrastructure

Token Contract:
0x453453096e669a8a48772287210098faa55bd64b

Team/Dev Timelock:
0xeb92f951f5a486e8d65569e737baf5b5fd494284

Treasury Timelock:
0xE022379FbA9E3CE816DC973494791072b3ebE5C9

All contracts use OpenZeppelin standards.

⸻

7. Explorer References

Token Contract:
https://polygonscan.com/token/0x453453096e669a8a48772287210098faa55bd64b

Team Timelock:
https://polygonscan.com/address/0xeb92f951f5a486e8d65569e737baf5b5fd494284

Treasury Timelock:
https://polygonscan.com/address/0xE022379FbA9E3CE816DC973494791072b3ebE5C9

Liquidity Pool:
https://polygonscan.com/address/0xa5a8f3E7E30C7A2B49A2c4D5638C2Ad15E847Fd4

⸻

8. Contact & Support

Website: https://www.lumachain.com.br
Telegram: https://t.me/lumachaincrypto
GitHub: https://github.com/lumacha
