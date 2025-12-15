# Stable Coin: Mechanisms and Market Failures

![Topic](https://img.shields.io/badge/Topic-DeFi%20Stability-blue)
![Status](https://img.shields.io/badge/Status-Research%20Archive-green)
![Focus](https://img.shields.io/badge/Focus-Algorithmic%20Failure-red)

**Principal Investigator:** Vishal Chaurasia
**Advisor:** Prof. Bina Ramamurthy, Blockchain ThinkLab
**Institution:** University at Buffalo (SUNY)

---

## 📄 Abstract
This research study provides a forensic analysis of the theoretical frameworks underlying Decentralized Finance (DeFi) stablecoins. It specifically investigates the trade-offs between collateralized and algorithmic stabilization models, offering a critical deconstruction of **Seigniorage** (share-style) algorithms and the specific failure modes inherent in "Burn-to-Mint" protocols.

The full analysis is available here: [Stable Coin_v2 (2).docx](https://github.com/BinaRam/stablecoin/blob/main/Stable%20Coin_v2%20(2).docx)

## 🔍 Key Findings & Analysis

### 1. The "Death Spiral" Vulnerability
The research identifies critical flaws in non-collateralized algorithmic models. Specifically, it analyzes the **Terra Money** ecosystem and the **TerraUSD (UST)** collapse:
* **Seigniorage Risk:** Analyzes how reliance on a volatility-absorbing token (LUNA) creates a feedback loop during market contractions.
* **Hyper-Inflationary Mechanics:** Details the mathematical inevitability of the "Death Spiral" once the peg deviates beyond a recovery threshold.

### 2. The Anchor Protocol Liquidity Trap
The study examines the role of high-yield savings protocols in creating artificial demand. It analyzes how the **20% APY** offered by Anchor Protocol led to a concentration of risk ($14B deposited), creating a liquidity crisis when **$2 billion** was withdrawn during a de-pegging event.

### 3. Systemic Risk Classification
The paper classifies stablecoin architectures by risk profile:
* **Fiat-Collateralized (Tether/USDT):** Centralization and audit risks.
* **Crypto-Collateralized (DAI):** Over-collateralization and Game Theory incentives.
* **Algorithmic (Terra/UST):** Supply elasticity and contraction failure modes.

## 📉 Research Significance
Following the **$40 Billion collapse** of the Terra ecosystem in May 2022, understanding the mechanics of algorithmic failure has become critical for regulatory frameworks. This research serves as a reference for:
* Identifying "Ponzi-like" structures in DeFi yield farming.
* Evaluating the solvency of algorithmic pegs under high-frequency volatility.
* Designing "Zero-Trust" financial architectures.

---
*This repository serves as a public archive for research into distributed consensus failures and DeFi market dynamics.*