# LumaChain Smart Contracts

This directory contains all audited-ready smart contracts used in the LumaChain (LUMA) ecosystem.  
All contracts follow the OpenZeppelin standard and are fully open-source under the MIT License.

---

## 📌 Contracts Included

### **1. LumaToken.sol**
Core ERC-20 token contract for the LumaChain ecosystem.

- Standard ERC-20 implementation  
- Based on OpenZeppelin  
- Initial supply minted at deployment  
- Symbol: **LUMA**  
- Network: **Polygon PoS**  
- Contract Address:  
  `0x453453096e669a8a48772287210098faa55bd64b`

---

### **2. SimpleTokenTimelock_Dev.sol**
Timelock contract securing the **Team / Developer allocation**.

- **Timelock Contract:**  
  `0xeb92f951f5a486e8d65569e737baf5b5fd494284`

- **Beneficiary (Team Wallet):**  
  `0x6D5dAbdA8d16484A7026DE4d9229beAed59fF7b3`

- **Amount Locked:** 60,000,000 LUMA  
- **Lock Duration:** 12 months  
- **Unlock Date:** April 2026  

---

### **3. SimpleTokenTimelock_Treasury.sol**
Timelock contract for securing the **Treasury allocation**.

- **Timelock Contract:**  
  `0xE022379FbA9E3CE816DC973494791072b3ebE5C9`

- **Beneficiary (Treasury Wallet):**  
  `0x9853A0B88Fce5DD672678b5986d96AdD4bD22288`

- **Amount Locked:** 30,000,000 LUMA  
- **Lock Duration:** 6 months  
- **Unlock Date:** April 2026  

---

## 📄 License

All LumaChain contracts are fully open-source and licensed under the **MIT License**.
