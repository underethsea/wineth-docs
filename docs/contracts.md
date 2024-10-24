---
sidebar_position: 6
---


# Smart Contracts
winETH.org uses the PoolTogether V5 smart contracts. The winETH prize vault was deployed from the original [PoolTogether PrizeVault factory](https://optimistic.etherscan.io/address/0xec9f59bd06465b105e719c0b0483a4ed6a656775). 
 
## Contract Addresses (OPTIMISM MAINNET)
Contract | Address
--- | ---
RngWitnet | [0x3d2Ef6C091f7CB69f06Ec3117F36A28BC596aa7B](https://optimistic.etherscan.io/address/0x3d2Ef6C091f7CB69f06Ec3117F36A28BC596aa7B)
TwabController | [0xCB0672dE558Ad8F122C0E081f0D35480aB3be167](https://optimistic.etherscan.io/address/0xCB0672dE558Ad8F122C0E081f0D35480aB3be167)
TwabRewards | [0x90D383dEA4dcE52D3e5D3C93dE75eF36da3Ea9Ea](https://optimistic.etherscan.io/address/0x90D383dEA4dcE52D3e5D3C93dE75eF36da3Ea9Ea)
TpdaLiquidationRouter | [0x7766b5E6839a1a218Fc861b0810C504490876136](https://optimistic.etherscan.io/address/0x7766b5E6839a1a218Fc861b0810C504490876136)
PrizePool | [0xF35fE10ffd0a9672d0095c435fd8767A7fe29B55](https://optimistic.etherscan.io/address/0xF35fE10ffd0a9672d0095c435fd8767A7fe29B55)
Claimer | [0x220C9398b0Ee07472bF8906e44574Cb9FE3B8D90](https://optimistic.etherscan.io/address/0x220C9398b0Ee07472bF8906e44574Cb9FE3B8D90)
DrawManager | [0x7eED7444dE862c4F79c5820ff867FA3A82641857](https://optimistic.etherscan.io/address/0x7eED7444dE862c4F79c5820ff867FA3A82641857)

Learn more about the PoolTogether smart contracts: [PoolTogether V5 Contract Reference](https://dev.pooltogether.com/protocol/reference/)

# Randomness
The prize strategy uses Witnet as a provably fair onchain way to get a random number. 

* [Learn more about the Witnet RNG](https://docs.witnet.io/smart-contracts/witnet-randomness-oracle) 
* [Learn more about the Draw Auction on PoolTogether](https://dev.pooltogether.com/protocol/design/draw-auction)

## Security
All contracts are audited and verified. You can view all audit reports [here](https://docs.pooltogether.com/security/audits).
