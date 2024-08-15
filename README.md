# FundMe Smart Contract

## Overview

This project implements a FundMe smart contract using Solidity. It allows users to send funds to the contract, which can then be withdrawn by the contract owner. This project demonstrates my proficiency in blockchain development, particularly in creating and testing smart contracts.

## Key Technologies

- Solidity: Smart contract programming language
- Foundry: Development environment for Ethereum
- Ethereum: Blockchain platform

## Features and Functionality

- Fund Collection: Users can send ETH to the contract
- Minimum Contribution: Enforces a minimum funding amount
- Withdrawal: Only the contract owner can withdraw funds
- Funder Tracking: Keeps record of funders and their contributions
- Price Feed Integration: Uses Chainlink price feeds for ETH/USD conversion

## Challenges and Solutions

One significant challenge was ensuring the contract's security against potential vulnerabilities. I implemented rigorous access controls and used Foundry's testing capabilities to thoroughly test edge cases and potential attack vectors. This process enhanced my skills in secure smart contract development and testing.

## Future Enhancements

- Implement a time-lock feature for withdrawals
- Add a feature to allow funders to reclaim their funds under certain conditions
- Integrate with a front-end dApp for easier interaction

## Installation and Usage

```bash
# Clone the repository
git clone https://github.com/kenn-eth/fundMe-smart_contract.git

# Navigate to the project directory
cd fundme-contract

# Install Foundry (if not already installed)
curl -L https://foundry.paradigm.xyz | bash
foundryup

# Compile the contract
forge build

# Run tests
forge test
```
