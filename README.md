# Ethereum Transaction Concepts

This repository provides an overview of key Ethereum transaction concepts which include transaction fees, gas limits, etc.

## Key Concepts

### 1. Transaction Fee
- **Definition:** Calculated as `Total Gas Used * Gas Price`.
- **Components:**
  - **Gas Used:** Computational units required.
  - **Gas Price:** Comprised of Base and Priority Fees.
- **Example:** If a transaction uses 21,000 gas and the gas price is 100 Gwei, the fee is `21,000 * 100 = 2,100,000 Gwei`.

### 2. Gas Limit
- **Definition:** Maximum amount of gas allowed for a transaction.
- **Example:** In Metamask, navigate to `Market > Advanced > Edit Gas Limit` to set this value.

### 3. Base Gas Fee
- **Definition:** Base fee of a transaction in Gwei, which is cost per gas.
- **Notes:**
  - **Burning Fee:** Fee is burnt to combat inflation (EIP-1559).
  - **Dynamic Adjustment:** Adjusts based on block fullness (EIP-1559).
- **Example:** If the base fee is 50 Gwei and is burnt, it reduces the supply of Ether.

### 4. Max Gas Fee
- **Definition:** Maximum cost per gas the transaction allows.
- **Example:** Configured prior to sending a transaction which ensures you don't overspend.

### 5. Max Priority Fee
- **Definition:** Maximum tip given to miners.
- **Example:** Incentivizes miners to include your transaction in the next block by offering a higher tip.

### 6. Block Confirmations
- **Definition:** Number of blocks confirming your transaction.
- **Example:** More confirmations mean greater certainty of transaction validity. If your transaction has 6 confirmations, it is considered secure.

## Summary
Understanding these concepts helps me in efficiently managing and verifying Ethereum transactions. This ensures cost-effectiveness and security.
