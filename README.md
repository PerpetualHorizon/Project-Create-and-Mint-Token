# Project-Create-and-Mint-Token


## Overview
'MyToken' is an ERC20 token named "Shashwat" (symbol: SP) built using the OpenZeppelin library. It includes features like minting, transferring, and burning tokens, all managed by a single owner.


## Features
-Minting: Only the contract owner can create new tokens.

-Transferring: Token holders can send their tokens to others.

-Burning: Token holders can destroy their own tokens.

-Ownership: The contract has an owner who controls the minting process.


## Prerequisites
Solidity ^0.8.20
OpenZeppelin Contracts ^5.0.0


## Installation
### Clone the repository: 
git clone https://github.com/your-repository-link
cd your-repository-directory
### Install dependencies: 
npm install @openzeppelin/contracts


## Contract Breakdown:
### 1. Constructor
![image](https://github.com/user-attachments/assets/8cd37244-655a-4b9a-a04f-fa35725d2ef8)
Purpose: Initializes the token with a name ("Shashwat") and symbol ("SP"). It also sets the initial owner of the contract.

### 2. Minting Tokens
![image](https://github.com/user-attachments/assets/caa0341d-d61c-41eb-b0f3-cd83f98e3779)
Purpose: Allows the owner to mint new tokens and assign them to a specified address.

### 3. Transferring Tokens
![image](https://github.com/user-attachments/assets/8fd8ef66-5957-42aa-9f8a-89293f56689e)
Purpose: Allows token holders to transfer their tokens to another address.

### 4.  Burning Tokens
![image](https://github.com/user-attachments/assets/ddf033ff-38d1-47d1-8cf9-59d7c9fa4335)
Purpose: Allows token holders to burn (destroy) their own tokens, reducing the total supply.


## How It Works
Deploy the Contract: Deploy with the initial owner’s address.
Minting: The owner mints tokens to a specified address.
Transferring: Token holders can transfer tokens to others.
Burning: Token holders can burn tokens to reduce the supply.


## Example Usage
### Mint Tokens: myToken.mint("0xRecipientAddress", 1000);
### Transfer Token: myToken.transfer("0xRecipientAddress", 500);
### Burn Tokens: myToken.burn(200);

## License
This project is licensed under the MIT License
