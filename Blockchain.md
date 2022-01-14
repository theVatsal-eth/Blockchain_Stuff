# Blockchain
The core concept of blockchain is crytographic representation of data. Each block may have a data that is then encrypted into a string by SHA256 encryption method.(The [[Ethereum]] Blockchain uses Keccak256)

For any unique data the encrypted string is different.

![[Pasted image 20211017232637.png]]

A Blockchain looks like:
![[Pasted image 20211017233238.png]]

**Hash Algorithm** is a function that computes data into a unique hash.

## Block
Each block in a blockchain contains a **Block no., Nonce, Transaction List, Previous hash, Hash**.
![[Pasted image 20211017232832.png]]

**Nonce**: is a "number used once" to find the "solution" to the blockchain problem. It is also used to define the transaction number for an account/address.

After clicking mine button:
![[Pasted image 20211017232921.png]]

As we can see the Nonce changes. What mine button does is it checks for each nonce number by brute hit and trial such that it results in a hash that starts with 4 zeroes.

The Nodes that perform mining are called miners. They are incentivized for mining as it is computationally intensive process.

**Genesis Block**: The first block in the blockchain.

## Distributed Blockchain
In peer-to-peer connection in a blockchain network each individual has the equivalent no. of blocks or has equivalent weightage of blockchain.

This protect the data being breached or manipulated.

What the algorithms might do is that they check the last block in the blockchain for its hash and compare them to the others which will help determining the manipulated blockchain.

When a blockchain is found manipulated, then the person owning it will be exempted from mining rewards.

### Mining
**The process of finding the "solution" to the blockchain problem.**

![[Pasted image 20211017234843.png]]

## Tokens
A token is block that contains transaction ledger as data. 

![[Pasted image 20211017235116.png]]

## [[Consensus]]
**Consensus** is a mechanism used to agree on the state of the blockchain.
Consensus protocol can be br
## Benefits
- Decentralised
- Node run
- Anyone can join
- Blockchains are resilient, it never shuts down even if one node shuts down.
- Each blockchain nodes keep lists of the transactions that occur

**Node**: A single instance in a decentralised network.

## Layers
### Layer 1
It refers to any base layer blockchain implementation. Bitcoin, ethereum, avalanche are some **layer 1** blockchain implementations.

### Layer 2
Any application built on top of a layer 1 is called layer 2. for example, chainlink, optimism.

### Related:
- [andersbrownworth.com](https://andersbrownworth.com/blockchain)