# Solidity Project Collection

This repository contains multiple Solidity smart contract projects, each designed to demonstrate and implement different blockchain concepts using Ethereum's smart contract capabilities.

## 📂 Projects Overview

### 1. Crowd_Funding
A decentralized crowdfunding platform where users can create campaigns and others can contribute funds securely using smart contracts.

**Features:**
- Create new fundraising campaigns with a goal and deadline.
- Allow contributors to send Ether directly to the campaign.
- Automatically transfer funds to the creator when the goal is reached.
- Refund contributors if the goal is not met before the deadline.

---

### 2. Crypto_Payment
A simple payment gateway smart contract for sending and receiving cryptocurrency on the Ethereum blockchain.

**Features:**
- Accept Ether payments from users.
- Store and track payment records.
- Allow withdrawals by the contract owner.
- Can be extended for subscription-based payments.

---

### 3. ERC20_Token
An implementation of the ERC-20 standard token contract, widely used for creating fungible tokens on Ethereum.

**Features:**
- Token creation (minting) and destruction (burning).
- Transfer tokens between accounts.
- Allow token approvals and delegated transfers.
- Fully ERC-20 compliant.

---

### 4. Lottery
A decentralized lottery system built using Solidity where participants can enter by paying Ether, and a random winner is chosen.

**Features:**
- Accept participant entries with a fixed entry fee.
- Randomly select a winner using blockchain randomness (e.g., `block.timestamp` / `block.difficulty`).
- Transfer the entire prize pool to the winner.
- Only the contract owner can pick the winner.

---

## 🛠️ Tech Stack
- **Language:** Solidity
- **Blockchain:** Ethereum
- **Tools:**  Remix IDE, MetaMask
- **Network:** Local blockchain (Ganache) or Ethereum Testnets (Goerli, Sepolia)

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/BlockChain.git
    