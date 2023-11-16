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

## Authors

Zedric James Ramoso
[@r0guePH](https://github.com/r0gueph)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
