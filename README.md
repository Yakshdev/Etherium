# MyToken Contract

Overview
This project implements a basic Ethereum smart contract called MyToken, which includes functionalities for token minting and burning.

## Description

**Requirement**

Public Variables:
tokenName: Stores the name of the token.
tokenAbbreviations: Stores the abbreviation for the token.
totalSupply: Tracks the total balance of the token.

Mapping:
balance: Maps addresses to their respective token balances.

Mint Function:
Increases the total supply by a specified amount (value).
Increases the balance of the sender's address (adr) by the same amount.

Burn Function:
Decreases the total supply by a specified amount (value).
Decreases the balance of the sender's address (adr) by the same amount, ensuring the sender has enough balance.

## Getting Started
The MyToken contract is implemented with the following features:

Public Variables:
tokenName: Name of the token.
tokenAbbreviations: Abbreviation for the token.
totalSupply: Total amount of tokens in circulation.

Mapping:
balance: Associates each address with its token balance.

### Installing

* Clone the repository:
https://github.com/your_username/your_repository.git
* Install necessary dependencies, if any.

### Executing program

* Deploy the MyToken contract on an Ethereum-compatible blockchain network.
* Interact with the contract using web3 libraries or Ethereum-compatible development frameworks.

## Authors
Yakshdev
GitHub: @Yakshdev
Email: yashtomar0511@gmail.com