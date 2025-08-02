
🗳️ Voting Smart Contract (Remix - Sepolia)

 📋 Overview

This smart contract allows token-based voting on proposals. Only accounts with allocated tokens can vote. Built in Solidity and tested using Remix on the Sepolia testnet.

 🚀 Features

- ✅ Mint voting tokens to an address
- ✅ Cast votes using tokens
- ✅ Track proposal vote counts
- ✅ Restrict voting access with a custom modifier
- ✅ Emits an event when a vote is cast

 🛠️ Contract Details

- **Solidity Version:** `^0.8.2`
- **Deployed On:** Sepolia Testnet
- **Filename:** `Voting.sol`

 🔧 Functions Tested (via Remix)

| Function | Description |
|----------|-------------|
| `addTokens(address voter, uint amount)` | Mints tokens to the voter |
| `vote(uint proposalId)` | Casts a vote on the proposal |
| `getVotes(uint proposalId)` | Returns the number of votes for a proposal |

 📜 Example Usage

1. Call `addTokens()` with account address and amount (e.g., `10`).
2. Call `vote()` with a proposal ID like `1`.
3. Call `getVotes()` to view total votes for a given proposal.

📦 Contract Structure

- **1 mapping:** To track votes per proposal
- **1 modifier:** Restricts voting to token holders only
- **1 event:** `VoteCast` is emitted upon a successful vote

🧪 Deployment & Testing

All tests were done using:

- **Remix IDE** (browser)
- **Injected Web3** (MetaMask on Sepolia)
- Screenshots available on request or submitted separately.

 🔗 GitHub

This repository contains:

- `Voting.sol` — Smart contract source code
- `README.md` — Project documentation
