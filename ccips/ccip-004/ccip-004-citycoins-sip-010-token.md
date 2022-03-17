# CCIP-004

## Preamble

| CCIP Number   | 004                                   |
| ------------- | ------------------------------------- |
| Title         | CityCoins SIP-010 Token               |
| Author(s)     | Jason Schrader jason@joinfreehold.com |
| Consideration | Technical, Economic                   |
| Type          | Standard                              |
| Status        | Draft                                 |
| Created       | 2022-03-16                            |
| License       | BSD-2-Clause                          |

## Introduction

## Specification

### Token Configuration

CityCoins are fungible tokens on the Stacks blockchain with no ICO, no pre-sale, and no pre-mine.

Once a CityCoin is deployed and activated, the emission schedule begins and winning miners mint the CityCoin into existence.

CityCoins can be sent and received using a STX address, used for payment in smart contracts, and more.

### Emissions Schedule

Miners receive coinbase rewards for mining the CityCoin outlined in the table below. The "halvings" occur at intervals similar to Bitcoin and Stacks, every 210,000 blocks, and there is a 10,000 block bonus reward for early miners.

The issuance schedule does not begin until mining is activated, and once it begins, the current block height of the Stacks blockchain is recorded in the contract. From there, the issuance continues as follows:

| Time Period                   | Reward            | Notes                               |
| ----------------------------- | ----------------- | ----------------------------------- |
| First 10,000 Stacks Blocks    | 250,000 CityCoins | approx. 3 months                    |
| Next 200,000 Stacks Blocks    | 100,000 CityCoins | approx. 4 years, minus bonus period |
| Next 210,000 Stacks Blocks    | 50,000 CityCoins  | approx. 4 years                     |
| Next 210,000 Stacks Blocks    | 25,000 CityCoins  | approx. 4 years                     |
| Next 210,000 Stacks Blocks    | 12,500 CityCoins  | approx. 4 years                     |
| Next 210,000 Stacks Blocks    | 6,250 CityCoins   | approx. 4 years                     |
| After 1,050,000 Stacks Blocks | 3,125 CityCoins   | continues indefinitely              |

After the final halving at 1,050,000 Stacks blocks past the Stacks block height recorded at activation, the total supply is estimated to be `42,187,500,000` and will increase indefinitely by `164,062,500` per year.

## Related Work

## Backwards Compatibility

## Activation

## Reference Implementations