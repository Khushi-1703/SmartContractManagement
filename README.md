# Smart Contract Management

# Respected Metacrafters team, I've made changes in the format of the frontend of the project...

For this project, we needed to create a simple contract with 2-3 functions. Then show the values of those functions in frontend of the application(Ethereum Smart Contract and React DApp)

This repository contains two main code snippets:

1. Solidity Smart Contract - Assessment.sol
2. React DApp - index.js

## Solidity Smart Contract - Assessment.sol
This Solidity smart contract is designed to manage a simple assessment system with deposit and withdrawal functionalities. The contract keeps track of the owner's balance and allows the owner to deposit and withdraw funds. It includes events for deposit and withdrawal, as well as custom error handling for insufficient balance during withdrawals.

### Contract Functions
1. constructor(uint initBalance): Initializes the contract with an initial balance provided during deployment.
2. getBalance(): Retrieves the current balance of the contract.
3. deposit(uint256 _amount): Allows the contract owner to deposit funds.
4. withdraw(uint256 _withdrawAmount): Allows the contract owner to withdraw funds, with custom error handling for insufficient balance.

## React DApp - index.js
This React DApp interacts with the deployed Assessment contract. It connects to the user's MetaMask wallet to provide a user-friendly interface for interacting with the contract.

### Features
1. Connection to MetaMask wallet.
2. Display of user account and balance.
3. Deposit and withdrawal buttons with corresponding functions.
4. Utilizes ethers.js library for contract interaction.

## Setup and Usage
1. Clone the repository and navigate to the src directory.
2. Install the required packages using npm install.
3. Start the React app with npm start.

Make sure you have MetaMask installed in your browser and are connected to the appropriate Ethereum network. The app will display your account information and balance if you are connected. You can then deposit and withdraw funds using the provided buttons.

## Credits
This project is created by ***[Khushi Gupta](https://github.com/Khushi-1703)***.

## License
This project is licensed under the ***[MIT License](https://github.com/Khushi-1703/SmartContractManagement/blob/main/LICENSE)***.
