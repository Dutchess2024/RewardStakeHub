# RewardStakeHub

## Overview

RewardStakeHub is a Clarity smart contract for a staking pool with reward compounding. Users can deposit tokens, earn rewards over time, and withdraw their funds along with accumulated rewards. The contract ensures fair reward distribution based on the staking duration and pool share.

## Features

- **Deposit & Stake**: Users can deposit tokens into the pool.
- **Reward Compounding**: The pool owner can trigger periodic reward distributions.
- **Withdraw & Earn**: Users can withdraw both their stake and earned rewards.
- **Access Control**: Only the pool owner can manage compounding actions.

## Functions

### `initialize(owner)`

Initializes the contract and sets the pool owner.

### `deposit(amount)`

Allows users to stake tokens in the pool.

### `compound-rewards()`

Enables the pool owner to distribute rewards proportionally.

### `withdraw()`

Allows users to withdraw their deposit along with accrued rewards.

## Future Improvements

- Integration with a fungible token contract for actual token transfers.
- Dynamic reward adjustment based on staking weight.
- Enhanced security checks.
