AstanaITUniversityNursultan Token

Overview

The AstanaITUniversityNursultan Token is an ERC-20 token implemented on the Ethereum blockchain. It provides basic ERC-20 functionality, allowing users to create and manage custom tokens with a specified name, symbol, and decimal places. Additionally, the contract includes features to retrieve information about transactions, such as the timestamp of the latest transaction and the addresses of the transaction sender and receiver.

Contract Details

- Name: AstanaITUniversityNursultan
- Symbol: MTN
- Decimals: 18
- Total Supply: 10,000 MTN tokens

Features

ERC-20 Standard Functionalities

Balance Inquiry

- Function: `balanceOf(address tokenOwner)`
- Purpose: Retrieve the token balance of a specific address.

 Allowance Inquiry

- Function: `allowance(address tokenOwner, address spender)`
- Purpose: Retrieve the remaining allowance that the owner has granted to a specific spender.

Approval

- Function: `approve(address spender, uint256 tokens) returns (bool success)`
- Purpose: Aprove a specific amount of tokens to be spent by another address.

Token Transfer

- Function: `transfer(address to, uint256 tokens) returns (bool success)`
- Purpose: Transfer tokens from the sender's address to the specified recipient.

Transfer with Approval

- Function: `transferFrom(address from, address to, uint256 tokens) returns (bool success)`
- Purpose: Transfer tokens from one address to another, using prior approval.

 Additional Features

Latest Transaction Timestamp

- Function: `getLastTransactionTimestamp() returns (string memory)`
- Purpose: Retrieve the timestamp of the latest transaction in a human-readable format.

Transaction Sender

- Function: `getTransactionSender() returns (address)`
- Purpose: Retrieve the address of the sender of the current transaction.

Transaction Receiver

- Function: `getTransactionReceiver() returns (address)`
- Purpose: Retrieve the contract's address as the receiver of the current transaction.
![Снимок экрана (148)](https://github.com/Moldakhmetov21/AstanaITUniversityNursultan/assets/156776337/c84e748e-fcf3-4a5d-a364-8f5554d66d94)

