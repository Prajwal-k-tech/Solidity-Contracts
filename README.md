# Solidity Contract Exercises

A personal Solidity learning repository. The current exercise is `counter.sol`, a minimal counter with `get`, `inc` and `dec` functions.

## Explore

Open the source in [Remix](https://remix.ethereum.org/) and select a compiler compatible with `pragma solidity ^0.8.26`. Use the Remix local VM for experimentation. No mainnet deployment is required.

The counter starts at zero. Calling `dec` at zero reverts under Solidity's checked arithmetic. Anyone may call increment or decrement; there is no ownership or access-control mechanism.

This is an educational exercise, with no production use or independent security audit claimed. See `LICENSE` for the MIT license.
