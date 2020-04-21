# UYT NETWORK

A heterogeneous blockchain architecture for asset
> interworking between parallel chains

## Abstract
>In the barbaric growth of the cryptographic world, we already have a large number of open-source ecosystems, robust and ever- improving underlying facilities, decentralized filesharing,andfree-flowing cryptocurrencies, but it's clear that the inability to commercialize on a large scale means that there are still many problems with blockchain structure today.

At the current stage, the biggest problem that people realize is the hard-to-reach extensibility and scalability between independent blockchain and other blockchains. According to the data disclosed by CoinMarketCap, there are at least over thousands of public blockchains running today, each blockchain with hundreds of millions of nodes on average pending all day for consensus to maintain the canonicality and validity of the ledger. Blockchain systems that cannot be extended and linked horizontally are like isolated islands and castles in the air. Therefore, there is no doubt that Cross-Chain technology is the focus of today's encryption field. We are pleased to see that some highquality open-source developers have built small and successful projects in this field, such as Polkadot, Cosmos, lris, Chainx, etc. However, due to the fundamentality and complexity of cross-chain technology, there are still a lot of weaknesses in the process need to be improved.

### UYT network is a heterogeneous multi-chain structure blockchain.
Based on the nature of the heterogeneous structure UYT can support backward compatibility with one or more existing blockchain systems, such as EOS, Ethereum, Binance Chain, etc. The system can provide a sort of useful underlying components, and support information transmission of the global business grade blockchain. It supports many highly differentiated consensus systems to interact within a trustless, fully decentralized federal system, allows trustless mutual access of blockchains.

UYT, as a brand new Relay-Chain, apart from providing data interconnection solution betweenPara-Chains,it’s irreplaceable innovation is: UYT enables every node within the system with the power of benefiting from “mining” by its unique innovated economic model to build a powerful value net rapidly. It solves effectively the problem between the high threshold of benefit obtaining by crypto assets participating consensus nodes in the past and nodes consensus in the Cross-Chain system in the future. To describe in a common way is that the UYT will achieve relatively fair, secure,uncoupledcross-blockchain "mining".

## Industry background
According to Satoshi Nakamoto's definition of a blockchain system, we can abstract the system role of any blockchain into User and Miner. Users use the advanced features on the network through wallets that contain keys or tokens. Miners, on the other hand, produce consensus blockchain, the public authoritative ledger of all transactions, through competitive computing.

## Cross-Chain
The development of blockchain technology up to today has shown its great significance. Public, alliance and private chains are also emerging, demonstrating the potential of expansion in multiple horizontal fields such as finance, traceability, identity management, social networking, IoT, artificial intelligence, and so on and huge bubbles of DLT (Distributed Ledger Technology). We have not seen significant real-world application deployments under existing technology.

Fundamentally, each chain has a separate system, which is highly heterogeneous between the chains and exists alone as an isolated value system. Nevertheless, in the application practice of blockchain technology, scalability and isolation are balanced against its ability to integrate with out-of-island systems. For example, it may require the geometric grade of computation, storage, memory, and other resources between heterogeneous systems when connecting to external systems, how to ensure processing capacity. On the other hand, the differential demand of multi- participant for applications is often difficult to meet within the same framework to the optimum degree. Evidently, the interoperability of chains is increasingly important; the demand of cross-chain also comes from this.

## Ecnomic models and Token

### Token
As all Para-Chain networks connected to UYT, UYT ParaChain has its own original token to indicate rights and interests. The token is named UYT and has a total release of 210 million (210,000,000 UYT).

UYT is derived from the spirit of open-source software and is fully compliant with the GPL (General Public License protocol). Therefore, there is no fund-raising behavior, the same, there is no pre-mining, no preset genesis node (the first 500 nodes established after obtaining 1,000 UYT through user’s stake automatically become genesis nodes) and other developer revenue behavior, all chain behaviors will be recorded by the blockchain.

### UYT output
The only way to obtain UYT is through mining behavior output. Nevertheless, the distribution after UYT "mining" is distinctive.

In the early stage of blockchain operation, the daily constant output of UYT was set at 144,000 UYT. To achieve high extensibility and scalability of the Para-Chain, UYT sets the block output time to be 10 second per block, i.e. 1.6666 UYT per second, (not excluding the appropriate reduction of output distribution by inflation indicator regulation, as described in Fig. 4.3), real-time settlement per 30 Minutes.

### Inflation model control

UYT adopting inflation model control to solve the "scissors-like gap" spell of increasing mining assets and declining mining revenue continually in other mining models, to openly operate market by setting threshold value range of inflation rate CPI [ CPI= real-time dug out asset market value (A) /mining asset market value (B)] and to control the number of mining assets entering and the amount of UYT to be allocated according to the market capitalization of the dug out asset.

### Hashrate
In UYT, hashrate is an indicator measuring asset mining capacity. Hashrate of mining assets are calculated based on the market price (benchmark USDT) at the time of transfering to the UYT network, obtained from weighted calculation (initially 4:3:3) with reference to the data provided by using the real-time market API of the three trading platforms Binance, Coinbase and Bitfinex, the conversion ratio of hashrate is:

1USDT=1HASHRATE (hashrate of each type of coin will be allocated with respective weights based on the market )

Hashrate is a key resource for mining. UYT network adopts the practice of "asset mining" and "voting mining", the ordinary user input obtained hashrate to the node user, then share the revenue with the node user (see Chapter 5 for details)

## Asset mining

As mentioned in previous paragraphs, UYT outputs through mining, but the distribution pattern is unique. UYT will provide a solid underlying network to build the next generation of consensus systems on top of it. Even if UYT maintains as little functionality and maximum versatility as possible in the underlying design pattern, in addition to its own Para-Chain needs network nodes to participate in the consensus, each Para-Chain links to UYT requires robust nodes to handle a variety of special cases on the Para- Chain, such as updating the status of the transaction queue ( that is, from one Para-Chain's exit queue to another Para-Chain’s entrance queue), processing the transaction collection of the approved Para-Chains, approving final blocks, receiving the final state change of Para-Chain, and so on. The network pressure brought about by these sudden states requires the consensus node within the network to have a strong resistance to risk.



