
# Enchanted Labyrinth Game Token 

## Overview

The Enchanted Labyrinth Game Token (ELGT) contract is designed to manage a token that can be used for gaming subscriptions within the Enchanted Labyrinth game ecosystem. Users can acquire tokens, redeem them for different subscription levels, and transfer tokens to others.

## Features

1. **Token Name and Symbol**: ERC20 compliant token named "Enchanted Labyrinth Game Token" with symbol "ELGT".
   
2. **Subscription Levels**: Users can redeem tokens for three subscription levels:
   - **Novice**: Costs 100 ELGT tokens.
   - **Explorer**: Costs 200 ELGT tokens.
   - **Master**: Costs 500 ELGT tokens.

3. **SubscriptionRedeemed Event**: Emits an event when a user redeems tokens for a subscription, indicating the user, subscription level, and tokens spent.

4. **Ownership and Permissions**: The contract includes ownership functionalities using the OpenZeppelin `Ownable` contract, allowing specific functions (like minting tokens) to be accessible only by the contract owner.

## Functions

- **mintTokens**: Allows the owner to mint new ELGT tokens and assign them to a specified address.
  
- **destroyTokens**: Allows any user to destroy a specific amount of their own ELGT tokens, reducing their balance permanently.

- **redeemSubscription**: Allows users to redeem tokens for a subscription level. It checks if the user has enough tokens and burns the tokens upon redemption.

- **transferSubscriptionTokens**: Allows users to transfer ELGT tokens to another address, useful for trading or gifting tokens.


## License

This contract is licensed under the MIT License. See `LICENSE` for more details.
