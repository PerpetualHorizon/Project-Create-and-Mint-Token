# Project-Create-and-Mint-Token


##Overview
'MyToken' is an ERC20 token named "Shashwat" (symbol: SP) built using the OpenZeppelin library. It includes features like minting, transferring, and burning tokens, all managed by a single owner.


##Features
-Minting: Only the contract owner can create new tokens.

-Transferring: Token holders can send their tokens to others.

-Burning: Token holders can destroy their own tokens.

-Ownership: The contract has an owner who controls the minting process.


##How It Works
Deploy the Contract: Deploy with the initial owner’s address.
Minting: The owner mints tokens to a specified address.
Transferring: Token holders can transfer tokens to others.
Burning: Token holders can burn tokens to reduce the supply.


##Example Usage
###Mint Tokens: myToken.mint("0xRecipientAddress", 1000);
###Transfer Token: myToken.transfer("0xRecipientAddress", 500);
###Burn Tokens: myToken.burn(200);

##License
This project is licensed under the MIT License
