# blockChian-transaction

Here’s a short README for your assignment:

---

# Simple Blockchain Assignment

This project simulates a basic blockchain network with a focus on block creation, mining, and transactions. The code provided allows users to interact with a blockchain-like structure where they can create transactions, mine blocks, and monitor the network's status.

## Features

- **Block Creation**: Each block contains data such as block number, timestamp, user data, and previous hash.
- **Genesis Block**: The initial block of the chain, created when the blockchain is initialized.
- **Transaction Requests**: Users can send transaction requests, which are temporarily stored in a mining pool.
- **Mining**: Miners validate and add pending blocks from the mining pool to the blockchain, receiving a reward for each mined block.
- **Network Status Check**: View the current state of the blockchain, users, and miners.

## How to Run

1. Install necessary packages:
   ```bash
   npm i
   ```

2. Run the code:
   ```bash
   node task.js
   ```

## Key Functions

- **createNewBlock**: Creates a new block with a unique hash.
- **createGenesisBlock**: Initializes the blockchain with the first block.
- **sendReqToPool**: Adds new transaction requests to the mining pool.
- **mine**: Processes and adds pending blocks to the blockchain, rewarding miners.
- **checkNetWorkStatus**: Prints the current status of the blockchain, user accounts, and miner balance.

## Project Flow

1. **Create User Accounts**: Both users and miners have accounts with unique addresses and initial balances.
2. **Send Transaction Requests**: Users send data to be added to the blockchain.
3. **Mining Blocks**: Miners process pending blocks and receive a reward for each mined block.
4. **Checkpoints**: Verify the blockchain state and miner/user balances after each mining operation.

---

This README provides a concise overview for setting up and using the blockchain simulation program.