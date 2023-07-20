# MyToken

## Description

MyToken is a simple ERC20 token contract implemented in Solidity. This contract allows users to create and manage their token, complete with minting and burning functionalities. The contract adheres to the ERC20 standard, ensuring compatibility with various decentralized applications (dApps) and exchanges.

## Features 
1. Token Name: The contract allows you to set the name of your custom token. The default name is "TARUN."
2. Token Abbreviation: You can specify the abbreviation of your token. The default abbreviation is "TJ."
3. Total Supply: The total supply of the token is tracked and managed within the contract.
4. Mint Function: The contract includes a mint function that allows users to mint new tokens. The function increases the total supply and adds the minted tokens to the specified address.
5. Burn Function: A burn function is implemented to burn tokens. The function deducts the burned tokens from the total supply and the specified address. It includes an if-else condition to ensure that the address has enough balance for burning.



## Getting Started


1. Clone the repository: git clone https://github.com/Tarunz2002/MyToken.git
2. Navigate to the contract directory: cd MyToken
3. Compile the contract using Solidity compiler: Compiler version - 0.8.7+commit.e28d00a7
4. Deploy the contract on your Ethereum development environment or testnet of choice.
5. Interact with the contract using your preferred Ethereum wallet or web3 provider.
