# Intro to POLKADOT NETWORK

Polkadot is a blockchain protocol and network that connects multiple blockchains, called **parachains**, into one primary blockchain, called the **relay chain**. Polkadot's native cryptocurrency is called DOT.

Parchains are specialized for specific purposes, and each handle their own parallel stream of transactions, while at the same time exchanging data with each other and the relay chain. The relay chain provides a layer of security for itself and all its parachains. 

## Become a Polkadot Developer

Upcoming lessons will focus on teaching Polkadot Development to you and other aspiring Polkadot Developers. Not only will you learn highly in-demand skills, but you will also earn DOT for doing so! Join our community channels for notifications on new lessons.

Check out the Polkadot [Knowledge Tree](https://github.com/BlockDevsUnited/learn-and-earn/blob/master/Lessons/English/L_EARN/CryptoCurrencies/Polkadot/Polkadot_Knowledge_Tree.jpg) and [Skill Tree](https://github.com/BlockDevsUnited/learn-and-earn/blob/master/Lessons/English/L_EARN/CryptoCurrencies/Polkadot/Polkadot_Skill_Tree.jpg) to get a sense of our upcoming lessons!

![image](https://user-images.githubusercontent.com/58176712/133651482-17e1b88e-a71f-4274-adbe-1a788f439741.png)


## Theory

Polkadot is known as a "sharded multichain network", where the parachains are the shards. Parallel processing power generated by the parachains leads to higher scalability than other single chain blockchains such as Bitcoin. Different parachains make different tradeoffs and might be optimized for different use cases like identity, supply chain, or file storage. Optimizing around a certain use cases means you can leave out unnecessary code, thereby increasing efficiency and security.

Polkadot lets developers build parachains using the **substrate framework**. Substrate is a framework for building blockchains

Please read futher here: https://polkadot.network/blog/what-is-polkadot-a-brief-introduction/

### Polkadot Components:

* Relay chain

* Parachains

* Parathreads

* Bridges

![image](https://user-images.githubusercontent.com/58176712/133652249-cd4c4747-5202-42c5-b521-00d3d6a18917.png)


#### The Relay Chain

The Relay Chain is the heart of Polkadot Network, and is responsible for shared security, consensus and interoperability between all Polkadot chains! Polkadot uses the relay chain primarily to: 

* Validate transactions
* Nominate Validatators to validate transactions
* Preserve historical Data
* Monitor health of the entire Polkadot ecosystem.

Users who stake DOT can validate transactions if they are nominated by the relay chian.

#### Parachains

Most parachains take the form of blockchains but don't necessarily need to be one. A parachain is described by Polkadot in the whitepaper as "an application-specific data structure that is globally consistent and validatable." This means it must be validatable by the validators of the relay chain. Parachains can host their own applications and economies.

Polkadot only supports a limited number of parachains. Parachain builders must successfully acquire a parachain slot for their parachain to be accepted in the Polkadot network. Slots are granted via Polkadot governance and auctions. Currently there are about 100 slots available.  

Parachains are said to be on the same level as other blockchain networks like Bitcoin or Ethereum. Polkadot contains multiple parachains within itself. Hypothetically, you could include both the Bitcoin and Ethereum as parachains in the Polkadot network. 

[Read More](https://wiki.polkadot.network/docs/learn-parachains)

#### Parathreads

Parathreads are similar to Parachains in almost all ways, except that they are only granted temporary access to participate in the Polkadot network. Multiple parathreads can share the same parachain slot, and access the relay chain and share in it's security, whenever it economically makes sense.  

[Read More](https://wiki.polkadot.network/docs/learn-parathreads)

#### Bridges

Bridges are used to communicate between two sovereign blockchains. They are a relatively new and growing aspect of blockchain technology. For that reason bridges in and around the Polkadot Network are still very much a work in progress. 


Bridges should allow Parachains, which are essentially blockchains embedded within the Polkadot ecosystem, to communicate and share data. The economic sovereignty and diversity of parachains are not affected when communicating or transacting through bridges.
[More on Bridges](https://wiki.polkadot.network/docs/learn-bridges)

### DOT, The polkadot currency

DOT is the native cryptocurrency of the Polkadot Network. DOT is used for payments, paying transaction fees, governance. DOT is also used to compensate the relay chain validators, and as a general currency.

#### DOT Characteristics

DOT holders have governance rights in the Polkadot network. Holders can help determine network rates, vote on proposed network updates and allow parachains to be deployed or deleted. 

DOT can be used to bid on parachain slots, and secure a place for your parachain. 

DOT is facilitates consensus on the network through staking. Staking DOT helps to maintain the security of the network, stengthening Polkadot's consensus.

DOT also has a bonding function. Bonding DOT is necessary to add a new parachains to the Polkadot network. When a bonding period is generated, the DOT tokens that have been attached are locked until the process ends.

### Polkadot Consensus

Polkadot's consensus system is called Nominated Proof-of-Stake (NPoS). NPoS is similar to Proof-of-Stake (PoS) mechanism, with slight variations.

With NPoS, the validators must offer infrastructure for the maintenance of the network. They are tasked with running nodes, producing the new blocks, validating parachain blocks and increasing the security of the network. NPoS validators must be available at all times and have the ability to run their infrastructure safely and reliably.

### Problems Polkadot Wants To Solve:

#### Scalability.

Most of the popular blockchains are not scalable due to their structure.

For example, long ago, it cost between a few cents and a few dollars (equivalent in ETH) to transact on Ethereum, the world's current most popular blockchain. In the present time, Ethereum transactions can cost hundreds, or even thousands of dollars. 

#### No or limited data communication and exchange.

Dozens of blockchains were created in isolation, and it is very difficult if not impossible for them to communicate or exchange value with each other directly. For example, you cannot send BTC on the ETH network.

#### Lack of customization.

Until the advent of Ethereum, blockchains did not support any customization of the transfer of value from one owner to another. Bitcoin, for example, only allowed peer-to-peer transactions. Smart Contracts allowed customizing and programming what can be achieved on a blockchain, to a limited extent.

#### Low energy impact validation mechanism.

Polkadot aims to have a secure transaction validation mechanism, that at the same time does not require expensive hardware and excessive energy consumption.  

## Practice

### Set up a Polkadot Wallet

For this lesson, all you need to do is set up a Polkadot Wallet. There are many wallets available, included Atomic Wallet, IMToken, Enjin wallet, and Trust Wallet.

## Testing

After studying this lesson, let us know when you are ready to take the test. The reward for passing is 0.2 DOT. 

## Resources

* [Polkadot Whitepaper](https://polkadot.network/PolkaDotPaper.pdf)
* [What is Polkadot](https://polkadot.network/blog/what-is-polkadot-a-brief-introduction)
* [Polkadot Wiki](https://wiki.polkadot.network/)
* [Summary of Polkadot And Substrate](https://medium.com/polkadot-network/a-brief-summary-of-everything-substrate-and-polkadot-f1f21071499d)

