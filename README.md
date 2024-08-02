# Project-Create-Degen

# Prerequisites

1. Ensure you have Node.js and npm installed on your local device.
2. Install MetaMask extension on your web browser and set it up to connect to the Avalanche Fuji Testnet.
3. Install Remix IDE or use the online version.

# Project Set Up

- Clone this repository to your local device using software tools such as GitHub Desktop or your terminal.
- Open a terminal in the project's root directory.
- Execute npm install in the terminal and wait until the installation is complete.
- In the same terminal, run remixd.
- Open your web browser and navigate to Remix IDE.
- In Remix, select the File Explorer Tab.
- Under Workspaces, select "connect to localhost" and click "Connect."
  
# Project Deployment

- Navigate to Remix IDE.
- Go to the Solidity Compiler tab and select "Compile DegenToken.sol."
- Go to the Deploy and Run Transactions tab.
- Under "Environment," choose "Injected Provider - MetaMask."
- Verify that MetaMask is connected to the Avalanche Fuji Testnet.
- Deploy the contract by clicking the "Deploy" button.

# Functions

This project involves a smart contract that creates an ERC20 token called Degen (DGN) for Degen Gaming. Deployed on the Avalanche network, it offers the following functionalities:

- createTokens(): Enables the owner to mint tokens into their wallet, accepting the owner's address and the amount to be minted.
- transferTokens(): Allows users to transfer tokens to a specified address. It requires the recipient's address and the amount to be transferred, ensuring the amount is less than or equal to the user's balance.
- redeemItem(): Lets users redeem items from the in-game store using the item ID as input. The user's balance must be sufficient to cover the item's cost.
- verifyBalance(): Allows users to check their current balance by inputting their account's address.
- destroyTokens(): Enables users to burn tokens from their account, requiring the amount to be burned and ensuring it is less than or equal to the user's balance.
- getItem(): Allows users to view the details of an item using the item's ID as input.
- displayItems(): Lets users view all items available in the in-game store.

# Author

Jill Alday
  
