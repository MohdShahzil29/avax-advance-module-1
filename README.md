# ERC20 Token and Vault Smart Contract

# Title
Solidity Token and Vault Contracts

# Description

This repository contains two Solidity smart contracts: token.sol and vault.sol. The token.sol contract implements a basic ERC-20 token with functionalities like transfer, approve, mint, and burn. The vault.sol contract, on the other hand, acts as a vault for the ERC-20 token, allowing users to deposit and withdraw tokens while managing the total supply and individual balances.

# Getting Started with Remix:

# Prerequisites:
1. Install Remix IDE in your web browser.
2. Ensure you have a compatible Ethereum wallet (e.g., MetaMask) for interacting with the contracts on the Ethereum blockchain.
# Steps:
3. Open Remix IDE:
4. Open your web browser and navigate to Remix IDE.
# Import Contracts:
5. Copy the contents of token.sol and vault.sol.
6. In Remix, create new files named token.sol and vault.sol.
7. Paste the respective contents into each file.
# Compile Contracts:
8. In Remix, go to the "Solidity" tab.
9. Select the appropriate version for the Solidity compiler (e.g., ^0.8.17).
10. Click the "Compile" button to compile the contracts.
# Deploy Token Contract:
11. Switch to the "Deploy & Run Transactions" tab.
12. Select token.sol in the contract dropdown.
13. Click the "Deploy" button to deploy the ERC-20 token contract.
# Copy Token Address:

14. After deployment, copy the deployed token contract address from the Remix console.
Deploy Vault Contract:
15. Select vault.sol in the contract dropdown.
16. Paste the ERC-20 token contract address into the constructor parameter for Vault.
17. Click the "Deploy" button to deploy the vault contract.
# Interact with Contracts:

Once deployed, you can interact with the contracts using the provided functions.
Connect your Ethereum wallet to Remix to perform transactions.
# Authors
Mohd Shahzil
# License:
This project is licensed under the MIT License. See the LICENSE file for details.
