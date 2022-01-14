# Smart Contracts
A "smart contract" is simply a program that runs on the [[Ethereum]] blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain.

The Smart Contracts which can interact with off-chain data with the help of Oracles are called Hybrid Smart Contracts.

## Limitations
Smart contracts alone cannot get information about "real-world" events because they can't send HTTP requests. This is by design. Relying on external information could jeopardise consensus, which is important for security and decentralization.

An oracle is a bridge between the blockchain and the real world. They act as on-chain APIs you can query to get information into your smart contracts. This could be anything from price information to weather reports. Oracles can also be bi-directional, used to "send" data out to the real world.

Oracles are used to extract off-chain data in a decentralised manner.

## Chainlink
Chainlink is a decentralised oracle that allows to bring data into smart contracts and do external computations.

### Related
- [Smart Contracts](https://ethereum.org/en/developers/docs/smart-contracts/)
- [Oracle](https://ethereum.org/en/developers/docs/oracles/)

