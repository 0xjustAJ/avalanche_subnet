# avalanche_subnet

# ERC20 and Vault Smart Contracts

Simple overview of use:
This project contains two Solidity smart contracts which are an ERC20 token contract and a Vault contract. The ERC20 token follows the standard ERC20 functionality, and the Vault contract allows users to make deposit tokens in exchange for shares, which can be redeemed for withdrawals.

### Description

This project implements an ERC20 token named "Solidity by Example" with symbol "SOLBYEX" and a Vault contract that allows users to make deposit and withdraw ERC20 tokens. The ERC20 contract supports minting, burning, transfers, and approvals. The Vault contract mints shares on deposits and burns shares on withdrawals, providing a share-based interaction model for the deposited tokens.

### Getting Started

#### Installation Process

- Clone this repository to your local machine:
  ```
      git clone https://github.com/0xjustAJ/avalanche_subnet.git 
  ```
- Ensure you have a development environment like Hardhat or Truffle installed:
  ```
      npm install --save-dev hardhat
  ```
- Compile the smart contracts:
  ```
      npx hardhat compile
  ```

#### Executing the program

- To deploy the ERC20 and Vault contracts:
  ```
      npx hardhat run scripts/deploy.js --network [network-name]
  ```
- After deploying, interact with the contracts using a frontend interface, or through Hardhat/Truffle console commands.
  Example steps:

1. Deploy ERC20 contract:
   ```
       npx hardhat run scripts/deployERC20.js
   ```
2. Deploy Vault contract with the deployed ERC20 contract address:
   ```
       npx hardhat run scripts/deployVault.js
   ```

### Help

Common issues might include network connection problems or incorrect configurations. Ensure the Ethereum network settings are correctly configured in hardhat.config.js or truffle-config.js.

`     npx hardhat help
`

### Authors

Contributor name and contact info:

- Ajayi Damola
- X (@justtA7J)

### License

This project is licensed under the MIT License - see the LICENSE.md file for details.
