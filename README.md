# Mood-DApp

# Overview
This repository contains the code for a decentralized application (DApp) built on the Ethereum blockchain. The DApp allows users to set and retrieve their mood using a simple frontend interface.

# How It Works
1. # Frontend Interface:
The DApp consists of a basic HTML webpage with buttons for setting and retrieving mood values.
   
3. # Smart Contract:
A Solidity smart contract named MoodDiary.sol is deployed on the Ethereum Sepolia test network. This contract includes functions for setting and getting mood values.

3. # Integration with MetaMask:
Users interact with the DApp through the MetaMask browser extension, which handles transactions and account management.

4. # Ethers.js Integration:
The frontend interface communicates with the deployed smart contract using the ethers.js library. This allows users to interact with the contract functions directly from the webpage.

5. # Testing:
The DApp can be tested locally by running the lite-server. Users can set and retrieve mood values to simulate real-world usage.

# Usage
To use the DApp:

Ensure MetaMask is installed and connected to the Sepolia test network.
Run the lite-server to view the webpage locally.
Interact with the buttons on the webpage to set and retrieve mood values.
