# DegenToken

DegenToken (`DGN`) is an ERC20 token smart contract built on the Ethereum blockchain. This contract allows users to mint, burn, and transfer tokens, and introduces a unique feature where tokens can be redeemed for in-game items called "swords."

## Contract Overview

- **Name**: DegenToken
- **Symbol**: DGN
- **Decimals**: 18
- **Redemption Rate**: 100 DGN per sword

## Features

1. **Minting Tokens**
   - The contract owner can mint new tokens to any address using the `mintTokens` function.

2. **Burning Tokens**
   - Token holders can burn their tokens using the `burnTokens` function.

3. **Transferring Tokens**
   - Users can transfer tokens to other addresses with the `transferTokens` function.

4. **Redeeming Swords**
   - Users can redeem tokens for swords using the `redeemSword` function. Each sword costs 100 DGN.

5. **Checking Balances and Swords Owned**
   - Users can check their token balance and the number of swords they own using `checkBalance` and `checkSwordsOwned` functions.

## Contract Deployment

The contract is deployed with an initial supply of 10 DGN tokens minted to the contract deployer's address.

## Functions

- `mintTokens(address to, uint256 amount)`: Mints `amount` of tokens to the `to` address. Only callable by the contract owner.
- `burnTokens(uint256 amount)`: Burns `amount` of tokens from the caller's balance.
- `transferTokens(address to, uint256 amount)`: Transfers `amount` of tokens to the `to` address.
- `redeemSword(uint256 quantity)`: Redeems `quantity` of swords by burning tokens at a rate of 100 DGN per sword.
- `checkBalance(address account)`: Returns the token balance of the specified account.
- `checkSwordsOwned(address user)`: Returns the number of swords owned by the specified user.

## Getting Started

To interact with the contract, you'll need an Ethereum wallet and some ETH to cover gas fees.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/DegenToken.git

2. Deploy the code and experiment with it.
