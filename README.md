# Hi, I'm Ivan 👋

### Solidity / Smart Contract Developer

I'm a software engineer focused on Ethereum, Solidity and DeFi development.

I build smart contracts with an emphasis on protocol mechanics, testing and security.
Currently expanding deeper into smart contract security, EVM internals and Zero-Knowledge cryptography.

## 🛠 Tech Stack

**Smart Contracts & Web3**
- Solidity
- Ethereum / EVM
- DeFi
- ERC-20
- OpenZeppelin

**Testing & Development**
- Foundry
- Hardhat
- ethers.js v6
- viem
- Chai
- Fuzz Testing
- Stateful Invariant Testing

**Languages**
- Solidity
- TypeScript / JavaScript
- Rust

**Currently Learning**
- Smart Contract Security
- EVM Internals
- Zero-Knowledge Proofs
- Finite Fields & Cryptography

## 🚀 Projects

### DeFi Lending Protocol

Overcollateralized ETH lending protocol built with Solidity and Foundry.

Users can deposit ETH as collateral, borrow ERC-20 tokens, repay debt,
withdraw collateral and liquidate unhealthy positions.

Features:
- ETH collateral deposits
- ERC-20 borrowing and repayment
- 70% maximum LTV
- 75% liquidation threshold
- Health factor system
- Partial liquidations
- 5% liquidation bonus
- Oracle-based collateral valuation
- Insolvency and bad-debt edge-case handling
- Reentrancy protection
- SafeERC20 integration
- Custom errors and events
- Unit and fuzz testing
- Stateful invariant testing

Testing:
- 29 tests
- 128,000 stateful invariant calls
- Protocol accounting invariants
- Price crash and insolvency scenarios

`Solidity · Foundry · OpenZeppelin · DeFi · Fuzz Testing · Invariant Testing`

---

### ForgeToken

ERC-20-like token implementation built from scratch.

Features:
- Transfers & allowances
- Mint / Burn
- Ownership
- Pause mechanism
- Maximum supply
- Custom errors
- Events
- Automated tests

`Solidity · Hardhat · ethers.js · Chai`

---

### InvoiceEscrow

Smart contract for trustless buyer/seller payments.

Features:
- Escrow payments
- Seller delivery confirmation
- Buyer/Seller permissions
- Contract state management
- Custom errors

`Solidity · Hardhat · ethers.js`

---

### OwnableVault

ETH vault with protocol fees and owner-controlled fee withdrawals.

Features:
- Deposits
- Withdrawals
- 2% protocol fee
- Ownership
- Transfer failure protection
- Custom errors

`Solidity · Hardhat`

## 🔐 Security Focus

I'm actively developing smart contract security skills through:

- Protocol invariant analysis
- Fuzz testing
- Stateful invariant testing
- Liquidation and insolvency analysis
- DeFi economic edge cases
- Smart contract auditing

One of the key findings while developing my lending protocol was that
a fixed liquidation bonus can worsen bad debt when a position becomes
sufficiently undercollateralized.

## 🎯 Current Goal

Building toward Solidity / Smart Contract Engineering and Smart Contract Security roles.

Currently focused on:
- DeFi protocol development
- Smart contract auditing
- EVM internals
- Foundry testing
- Open-source Web3 contributions
- Solidity security contests and bounties
- Zero-Knowledge cryptography
