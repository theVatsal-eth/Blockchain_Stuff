# Consensus
**Consensus** is a mechanism used to agree on the state of the blockchain.
Consensus protocols have roughly two categories:
- Sybil Resistance(Proof of Work)
- Chain Selection Rule

Bitcoin and Ethereum blockchains use Nakamoto Consensus which is a combination of *PoW* and *longest chain rule*.

**Block Time** is the time it takes to publish a new block. It is proportional to how hard these algorithms are.

**Block Confirmations** is number of blocks added on the chain successfully after our transaction went through. If we see that confirmation is two, it means that there are 2 blocks ahead of our block in the blockchain

**Block Reward** is given to the miner nodes by the blockchain itself. The block reward helps in circulating the cryptocurrency that the blockchain offers.

**Halving** refers to the block reward getting halved roughly every four years.

## Sybil Resistance
**Sybil Resistance** is a blockchain's ability to defend against users creating a large number of pseudo-anonymous identities to gain a disproportionately advantageous influence over said system.
Basically it resists people making fake blockchains to get more and more mining rewards.

### Proof Of Work
The mining that is done in [[Blockchain#Mining]] called Proof of Work is said to be a part of Sybil Resistance because it defines a way to figure out who is the block author of the new block who mined it so that everyone else can verify that it's accurate. PoW also determines the node that got [transaction fees](Ethereum#Gas) and block rewards.

In PoW, each node has to go through a computationally expensive process. Also, all the miner nodes are competing at a time to get the solution to the blockchain problem so as to get the transaction fees and block rewards. Thus, the PoW uses a lot of energy.

### Proof Of Stake
Proof Of Stake nodes put up collateral as a sybil resistance mechanism. If a node misbehaves it is slashed/removed out of the network. In PoS, miners are called validators. Here, the unlike miners, a random node is chosen to validate a new block.

Randomness

#### Pros:
- PoS uses much less energy

#### Cons:
- Due to the staking mechanism, some say it is slightly decentralised.


## Chain Selection Rule

In this type of consensus, we determine which blockchain is the real blockchain.

### Longest Chain Rule

The longest blockchain is considered real as for every new block it takes more and more computational.




## Attacks

### Sybil Attack

When a user creates a whole bunch of pseudo-anonymous accounts to try to influence a network.

### 51% Attack

When a single miner node attains 51% of the networks computing power, where he can then defraud the chain.