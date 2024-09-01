
# DeFi Kingdom Clone on Avalanche

## Project Overview

This project is a simplified clone of the popular DeFi Kingdom game, built on the Avalanche network. The primary focus is on setting up a custom EVM Subnet, creating a native token, and deploying foundational smart contracts that serve as the building blocks for a decentralized finance (DeFi) gaming experience.

## Features

- **Custom EVM Subnet:** A dedicated subnet on Avalanche to host the game’s smart contracts with low transaction fees.
- **Native Currency:** Creation of a custom ERC20 token used as the in-game currency.
- **Smart Contracts:** Deployment of essential smart contracts including an ERC20 token contract and a Vault contract for managing in-game assets and rewards.
- **Metamask Integration:** Full integration with Metamask for managing in-game assets and interacting with the deployed contracts.

## Smart Contracts

### ERC20 Token Contract

This contract implements the ERC20 standard for creating a native token used within the game. Key functionalities include minting, burning, transferring tokens, and managing allowances.

### Vault Contract

The Vault contract allows users to deposit tokens in exchange for shares and withdraw them later, providing a mechanism to store and manage assets within the game.

## Tools & Technologies

- **Avalanche CLI:** Used to set up the EVM Subnet.
- **Solidity:** Programming language for writing smart contracts.
- **Remix IDE:** An online IDE for deploying and interacting with smart contracts.
- **Metamask:** A crypto wallet and gateway to blockchain apps, used for interacting with the deployed contracts.

## How to Run the Project

1. **Set Up EVM Subnet:** Use the Avalanche CLI to create a custom EVM Subnet on the Avalanche Fuji Testnet.
2. **Deploy Smart Contracts:** Use Remix to deploy the ERC20 and Vault contracts to your EVM Subnet.
3. **Connect Metamask:** Add your EVM Subnet to Metamask and use it to interact with the deployed contracts.
4. **Test the Application:** Use Remix and Metamask to test the functionality of your contracts, including minting tokens, depositing to the Vault, and withdrawing assets.

## Deployment

The contracts are deployed on the Avalanche Fuji Testnet. Ensure Metamask is configured to connect to this network.

## Video Walkthrough

A video walkthrough of the project is available [here](https://www.loom.com/share/e4bf545748944d9fa138a74be33ff74e?sid=f90afc7b-b6ee-4a64-bd75-b43b67264279).


## License

This project is licensed under the MIT License.

