# MoodTracker dApp

## Overview

MoodTracker dApp is a decentralized application that allows users to set and get mood data using a smart contract on the Ethereum Sepolia test network. The dApp is built with Solidity for the smart contract and HTML/JavaScript for the frontend.

## Project Structure

- **`solidity.txt`**: Contains the Solidity smart contract code.
- **`index.txt`**: Contains the HTML and JavaScript code for the frontend.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MetaMask or another Ethereum wallet extension installed and configured.

### Solidity Smart Contract

1. **Smart Contract Code**

   The smart contract code is located in `solidity.txt`. This code defines the contract for setting and getting mood data.

2. **Deploy the Smart Contract**

   To deploy the smart contract, follow these steps:

   - Copy the Solidity code from `solidity.txt`.
   - Use Remix IDE, Hardhat, or Truffle to deploy the smart contract on the Ethereum Sepolia test network.
   - Note the contract address provided after deployment.

### Frontend (Website)

1. **Frontend Code**

   The frontend code is located in `index.txt`. It includes HTML and JavaScript for interacting with the smart contract.

2. **Update the Frontend Code**

   - Replace `MoodContractAddress` in the JavaScript section with the contract address obtained from the deployment.
   - Ensure the ABI (Application Binary Interface) in the JavaScript code matches the smart contract functions.

3. **Setup and Test**

   - Save the contents of `index.txt` as `index.html`.
   - Open `index.html` in a web browser.
   - Connect your MetaMask wallet to the Ethereum Sepolia network.
   - Interact with the dApp by setting and getting mood data.
