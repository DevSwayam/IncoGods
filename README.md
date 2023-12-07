
# Inco Gods NFT Card Game

## Overview

Welcome to the Inco Gods NFT Card Game, a blockchain-based card game developed on the INCO blockchain. This decentralized application (DApp) allows players to participate in battles using unique NFT cards, each with randomized attack and defense strengths. The game leverages on-chain randomness using the TFHE library and provides privacy features by storing certain card attributes using euint8.

## Table of Contents

1. [Smart Contract Overview](#smart-contract-overview)
2. [TFHE Features](#features)
3. [Getting Started](#getting-started)
4. [Game Mechanics](#game-mechanics)
5. [Tokenomics](#tokenomics)
6. [How to Contribute](#how-to-contribute)
7. [License](#license)

## Smart Contract Overview

The smart contract is implemented in Solidity and follows the ERC-1155 standard for NFTs. It includes features for player registration, NFT creation, battle creation and resolution, and more. The contract also integrates the TFHE library for on-chain randomness.

## Features TFHE

- **Player Registration:** Players can register in the game by providing a name and creating a random game token.
- **Battle Creation:** Players can create battles and invite others to join.
- **Battle Resolution:** Battles are resolved based on player moves, attack, defense, and health attributes of their NFT cards.
- **On-chain Randomness:** The game leverages the TFHE library for on-chain randomness in generating attack and defense strengths.
- **Privacy:** Certain attributes of the NFT cards, such as attack and defense strengths, are stored using euint8 for enhanced privacy.

## Getting Started

To get started with the Inco Gods NFT Card Game, follow these steps:

1. **Install Dependencies:** Ensure you have the necessary dependencies, including the INCO blockchain and TFHE library.
2. **Deploy Smart Contract:** Deploy the smart contract on the INCO blockchain.
3. **Register as a Player:** Use the `registerPlayer` function to register as a player and create your first game token.
4. **Create and Join Battles:** Use the `createBattle` and `joinBattle` functions to start or join battles with other players.

## Game Mechanics

- **Mana:** Players have a mana attribute that affects their ability to make certain moves in battles.
- **Health:** Each player has a health attribute that determines their resilience in battles.
- **Battle Moves:** Players choose attack or defense moves during battles.
- **Randomized Strengths:** The attack and defense strengths of NFT cards are randomized using on-chain randomness.

## Tokenomics

The game utilizes an ERC-1155 token standard. Each token represents a unique NFT card with distinct attributes. The total supply is dynamically managed based on player interactions.

## How to Contribute

If you're interested in contributing to the Inco Gods NFT Card Game, feel free to fork the repository, make your changes, and submit a pull request. Contributions are welcome in various forms, including bug fixes, new features, and documentation improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
