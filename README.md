# ETH+Avax Assessment 1

This code is a smart contract name 'myTransactions' which is made as an assessment for Metacrafter's ETH+Avax Assessment 1.

## Features

- **Deposit Function:**
  - Allows users to deposit funds into their account.
  - Ensures the deposited amount is greater than zero.

- **Transfer Function:**
  - Enables users to transfer funds from their account to another account.
  - Verifies that the sender has a sufficient balance for the transfer.
  - Updates the balances accordingly.
  - Includes an `assert` statement to ensure the recipient's balance is correctly updated.

- **Withdraw Function:**
  - Permits users to withdraw funds from their account.
  - Checks if the withdrawal amount is less than the account balance.
  - Reverts the transaction with an error message if the balance is insufficient.
    
## Getting Started

1. Run the code using [Remix](https://remix.ethereum.org/)

2. In the Remix website, create a new file by clicking on the "+" icon on the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy the source code from the myTransactions.sol file in this repository, and paste it in the file you created.

3. In order to compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" or any compatible version. You should then see a blue button with a "Compile (Your File Name).sol". Click that button to compile the code.

4. Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the the contract with your file name from the dropdown menu, and then click on the "Deploy" button.

5. Once the contract is deployed, you may now start interacting with the contract by using the Deposit, Transfer, and Withdraw functions.
   
## Authors

Zedric James Ramoso
[@r0guePH](https://github.com/r0gueph)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
