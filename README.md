# Globe Token

The Globe Token is a Solidity smart contract written for the Ethereum blockchain. It enables users to mint, transfer, burn tokens, and redeem them for different types of virtual globe items.

## Features

- **Minting Tokens**: The contract allows the owner to mint new tokens and distribute them to specified addresses.

- **Burning Tokens**: Users can burn their tokens, removing them from circulation permanently.

- **Transferring Tokens**: Users can transfer tokens to other addresses.

- **Redeeming Tokens for Globe Items**: Users can redeem their tokens for virtual globe items categorized as Earth, Mars, or Jupiter.

## How to Use

1. **Minting Tokens**: The owner of the contract can mint new tokens by calling the `mintTokens` function and specifying the beneficiary address and the amount of tokens to mint.

2. **Burning Tokens**: Users can burn their tokens by calling the `burnTokens` function and specifying the amount of tokens they want to burn. This action cannot be undone.

3. **Transferring Tokens**: Users can transfer their tokens to other addresses by calling the `transferTokens` function and specifying the recipient address and the amount of tokens to transfer.

4. **Redeeming Tokens for Globe Items**: Users can redeem their tokens for virtual globe items by calling the `redeemForGlobe` function and specifying the amount of tokens they want to redeem. Depending on the amount of tokens, the user will receive a virtual globe item categorized as Earth, Mars, or Jupiter.

## Requirements

- This contract requires the OpenZeppelin library for ERC20 and Ownable functionalities. Ensure you have the necessary dependencies installed to deploy and interact with the contract.

## License

This smart contract is released under the MIT License. You can find the license details in the SPDX-License-Identifier at the top of the contract file.

## Author Name 

Pramod

pramodmech9148@gmail.com
