# Blockchain-Final
* RWA Tokenization Platform

## 1. Project Overview

This project is a blockchain platform for tokenizing real-world assets (RWA).  
Users can hold asset-backed ERC-20 tokens, deposit them into an ERC-4626 vault, and participate in DAO governance.

## 2. Main Features

- ERC-20 asset-backed token
- ERC-4626 yield vault
- Role-based minting for authorized issuers
- Chainlink price feed / Proof of Reserve
- DAO governance with Governor + Timelock
- The Graph indexing
- Frontend dApp
- L2 testnet deployment

## 3. Team Roles

Bibarys , Yeraly , Ersultan


Yeraly 1 — Smart Contracts

Responsible for Solidity backend

Tasks:

Implement ERC-20 RWA token
Implement ERC-4626 vault
Add role-based minting (AccessControl)
Integrate Chainlink price feed
Implement UUPS upgradeable contract
Create Factory contract (CREATE + CREATE2)

Bibarys 2 — Governance & Testing

Responsible for DAO + security tests

Tasks:

Implement ERC20Votes governance token
Build Governor + TimelockController
Configure voting rules (delay, period, quorum)
Write tests (unit, fuzz, invariant)
Add reentrancy and access-control vulnerability examples

Ersultan 3 — Frontend & DevOps

Responsible for UI + deployment

Tasks:

Build frontend with wallet connection
Show token balance, vault shares, proposals
Implement deposit / withdraw / vote buttons
Create The Graph subgraph
Deploy contracts to L2 testnet
Setup CI pipeline and documentation
