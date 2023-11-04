## Solidity by Example
This repository provides two Solidity files implementing ERC20 and Vault contracts as examples.

# ERC20.sol
## Overview
The ERC20 contract is a standard implementation of the ERC20 token standard. It includes functionalities such as transferring tokens, approving spending, and minting/burning tokens.
# Functions
**transfer**: Transfer tokens from the sender to a specified recipient.

**approve**: Approve a spender to spend a specified amount of tokens on behalf of the owner.

**transferFrom**: Transfer tokens from one address to another, with the approval of the sender.

**mint**: Mint new tokens and assign them to the sender.

**burn**: Burn a specified amount of tokens from the sender's balance.

## Variables
**totalSupply**: Total supply of the ERC20 token.

**balanceOf**: Mapping of addresses to their token balances.

**allowance**: Mapping of owner to spender and the approved spending amount.

**name**, **symbol**, **decimals**: Token metadata.

# Vault.sol
## Overview
The Vault contract is a simple implementation that interacts with an ERC20 token (assumed to be compliant with the IERC20 interface). It allows users to deposit and withdraw tokens, minting and burning shares accordingly.

## Functions
**deposit**: Deposit tokens into the Vault, minting new shares for the depositor.

**withdraw**: Withdraw tokens from the Vault, burning shares proportionally.

## Variables
**token**: The ERC20 token interface.

**totalSupply**: Total supply of shares in the Vault.

**balanceOf**: Mapping of addresses to their share balances.

## License
This code is licensed under the MIT License. See the LICENSE file for details.

Feel free to explore and use these Solidity examples as a reference for your projects!
