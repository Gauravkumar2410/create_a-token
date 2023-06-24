# Custom Token Contract
The Custom Token Contract project aims to create a versatile and customizable token contract that can be deployed on the Ethereum blockchain. This contract enables users to mint and burn tokens, managing the total supply and individual balances. The contract includes public variables to store important details about the token, such as its name, abbreviation, and total supply. By implementing the mint function, users can increase the total supply and allocate tokens to specific addresses, while the burn function allows for the destruction of tokens by reducing the total supply and deducting tokens from a designated address. This project provides a solid foundation for building and managing custom tokens on the Ethereum platform.
# Description
This project aims to create a custom token contract that implements basic functionality such as minting and burning tokens. The contract will store details about the token, including its name, abbreviation, and total supply. It will also maintain a mapping of addresses to token balances. The mint function will increase the total supply and the balance of a specific address, while the burn function will decrease the total supply and the balance of an address, effectively destroying tokens.
# Getting Started
# Installing:
To use this contract, you need a development environment with a Solidity compiler. You can install the Solidity compiler by following the instructions provided on the Solidity documentation website (https://soliditylang.org/).
# Executing program
1. Download the contract file:

2. Download the "token_contract.sol" file from the repository.
Modify the contract (optional):

3. If desired, you can modify the token name, abbreviation, or total supply by editing the corresponding variables in the contract.
Compile the contract:

4. Use the Solidity compiler to compile the "token_contract.sol" file into bytecode.
Deploy the contract:

5. Deploy the compiled bytecode to your preferred Ethereum development network or testnet using a tool like Remix or Truffle.
Interact with the contract:

6. Once the contract is deployed, you can interact with it using a web3 provider or an Ethereum client library like web3.js or ethers.js.
Call the mint function to increase the total supply and balance of an address.
Call the burn function to decrease the total supply and balance of an address, effectively destroying tokens.
# Help 
If you encounter any issues or have questions, please refer to the Solidity documentation for more information on Solidity language features and smart contract development.
# Authors
Gaurav Kumar Saini
@gauravkumar2410

# License
This project is licensed under the MIT License - see the LICENSE.md file for details
