# Mood-DApp

# Overview
This repository contains the code for a decentralized application (DApp) built on the Ethereum blockchain. The DApp allows users to set and retrieve their mood using a simple frontend interface.

# How It Works
1. # Frontend Interface:
The DApp consists of a basic HTML webpage with buttons for setting and retrieving mood values.

![2024-05-03](https://github.com/JPV2207/Mood-DApp/assets/111731727/0ca37635-0cfa-4bed-bf5a-70e78c667f79)

   
2. # Smart Contract:
A Solidity smart contract named First_Dapp.sol is deployed on the Ethereum Sepolia test network. This contract includes functions for setting and getting mood values.

![2024-05-03 (1)](https://github.com/JPV2207/Mood-DApp/assets/111731727/1dbb5fe4-2140-475f-99f1-c45703d42fc3)


3. # Integration with MetaMask:
Users interact with the DApp through the MetaMask browser extension, which handles transactions and account management.

4. # Ethers.js Integration:
The frontend interface communicates with the deployed smart contract using the ethers.js library. This allows users to interact with the contract functions directly from the webpage.

![2024-05-03 (3)](https://github.com/JPV2207/Mood-DApp/assets/111731727/3f34f29d-51f8-421e-8bc0-5037dddd8a1b)


5. # Testing:
The DApp can be tested locally by running the lite-server. Users can set and retrieve mood values to simulate real-world usage.

# Usage
To use the DApp:

Ensure MetaMask is installed and connected to the Sepolia test network.
Run the lite-server to view the webpage locally.
Interact with the buttons on the webpage to set and retrieve mood values.
