# Crowdfunding Project in Solidity

Developed and deployed a crowdfunding smart contract on Ethereum to enable secure fundraising.  
Designed features for managing contributions, setting goals, and handling refunds.

## How It Works

In this smart contract, funds are collected from contributors.  
After that, the manager sends a request to withdraw funds.

A manager can withdraw funds **only if the majority of contributors approve the withdrawal**.

If the majority of contributors do not agree to release the funds, the manager cannot take the funds and all collected funds will be returned to the contributors’ accounts.

## Key Features

- Secure and transparent fundraising on Ethereum.
- Contributors can fund campaigns easily.
- Manager can request withdrawals.
- Majority voting system for withdrawal approval.
- Automatic refunds if approval is not reached.

## Tech Stack

- **Blockchain:** Ethereum
- **Smart Contracts:** Solidity
- **Wallet Integration:** MetaMask or similar

## License

This project is for educational and demonstration purposes.
