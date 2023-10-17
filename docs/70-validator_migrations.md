---
title: Validator Migrations Initiative
description: Node operators running 32Ξ Ethereum nodes can commit to migrate to Diva to support its launch
---

# Validator Migrations Initiative

Diva Staking is still under development, but you can already support its launch.

This initiative is aimed at Ethereum node operators running one or more 32Ξ Ethereum validators on mainnet. If you'd like to join with any amount of ETH, check the [Early Staker initiative](early_stakers) instead.

**You can now commit to an Ethereum Validator Migration** to support tha launch of Diva.

This initiative is currently [under community discussion](https://discord.com/channels/1041618287500460083/1163123300789125222), but a standard has already been proposed by The Staking Foundation to allow Operators to signal commitments. There are currently no approved reward mechanisms.


## Proposed initiative

- **What**: A mechanism for Operators to commit ETH to be used in Diva as operator collateral
- **Why**: This benefits Diva by providing active nodes and staking capacity for Liquid Stakers.
    - With more ETH from Operators, Diva can ensure a smooth launch.
    - Without this, Diva might suffer from not having enough nodes with sufficient ETH collateral. This creates a risk that ETH doesn’t get 100% staked, thus reducing Diva's APR.
- **How**: A non-custodial signaling process has been proposed to commit Operator ETH and demonstrate their ability to run nodes with high performance:
1. Operator commits an ETH amount in multiples of 32Ξ.
2. Pre-launch of Diva: Operator stake this ETH them into Ethereum validators, which they operate.
3. During Diva Testnet: Operators demonstrate their ability to validate Diva testnet.
4. Once Diva launches: Operators withdraw their ETH and deposit it into their Diva nodes as collateral.

## Motivation

This initiative aims to accelerate the launch and adoption of Diva Staking by helping to:

-   Gain confidence that the protocol and DIVA are widely adopted
-   Distribute voting power to participants according to their commitments
-   Plan node operator capacity and DeFi integrations ahead of launch

This ultimately helps balance and decentralize the Ethereum staking ecosystem by promoting diversity to its LST landscape and embracing the future of [DVT](dvt) technology.


In a scenario where the Early Staker vaults are full, Diva will have a TVL of 100k ETH to be staked.

This Validator Migration initiative could match that with a TVL from Operators of ~15-30k ETH (to be discussed) to ensure the network is balanced.

Operators could become eligible to receive DIVA incentives by completing all tests above demonstrating excellent performance in both Ethereum mainnet and Diva tesntet (pre-launch) and for a period of time in Diva mainnet (post-launch)

The design of this initiative is fully non-custodial and provides Operators APR while they wait for launch, which is also used as proof of their performance.


## How this fits into Diva Staking related iniaitives

1. [Diva Early Staker Vaults](early_stakers) allow depositing any amount of (st)ETH.
2. **This initiative** allows anyone to migrate their 32Ξ validators to Diva.

TVL commitments are important, because they attract Liquid Stakers, [Operators](participants#operators) and facilitate integrations.

Both initiatives are non-custodial, allowing participants to withdraw their funds anytime.

## Signaling mechanism

Operators would signal their commitments on-chain by posting

- an Ethereum 0 ETH transaction
- from the depositing address which made the validator 32ETH deposits
- to the address: [0x93f3d5BB7901a00c88703cf78fA27bb6647774E9](https://etherscan.io/address/0x93f3d5BB7901a00c88703cf78fA27bb6647774E9)
- with a data field containing JSON like `{ keys: [ pubkey1, pubkey2, ... ] }`

This allows queries and dashboards to verify it display commitments, like in this [sample Dune query](https://dune.com/queries/3102029).

## Incentives & Rewards

While the Early Staker Vaults have clearly outlined rewards, this initiative still needs community discussion to be finalized.