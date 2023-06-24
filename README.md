# creatingNewToken
**MyToken Contract**
This Solidity contract implements a basic token functionality,
allowing minting and burning of tokens. It provides a starting 
point for building token-based systems on the Ethereum blockchain.

**Description**
This contract, called MyToken, is written in Solidity, a programming 
language used for developing smart contracts on the Ethereum blockchain. 
The contract includes functions to mint and burn tokens, as well as mappings 
to store token balances and a struct to store token details. This contract 
can be used as a foundation for creating custom tokens with specific features and functionalities.

**Requirements**

The contract fulfills the following requirements:

1. The contract has public variables to store details about the token, such as the token name, abbreviation, and total supply.
2. It includes a mapping that associates addresses with their token balances, allowing querying of balances using the `balances[address]` syntax.
3. The `mint` function increases the total supply of tokens by a specified amount and increases the balance of the receiver address by that value.
4. The `burn` function decreases the total supply of tokens by a specified amount and deducts the burned amount from the sender's balance, provided the sender has sufficient tokens.
5. The `burn` function includes conditionals to ensure the sender's balance is greater than or equal to the amount to be burned.

**Getting Started**

To deploy and interact with the MyToken contract, follow these steps:

1. Open the Remix website at https://remix.ethereum.org/.
2. Create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol).
3. Copy and paste the provided code into the file.
4. Compile the code by clicking on the "Solidity Compiler" tab in the left-hand sidebar. Set the "Compiler" option to "0.8.18" (or another compatible version) and click on the "Compile MyToken.sol" button.
5. Deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu and click on the "Deploy" button.
6. Once the contract is deployed, you can interact with it by calling the `mint` and `burn` functions, providing the required parameters. You can also access the balances of different addresses using the `balances` mapping.

**Author**
Navdeep Singh

**License**

This project is licensed under the MIT License - see the LICENSE.md file for details.

