# Blockchain_Education
Notes for everything connect to blockchain

# Table of Contents

<details>
<summary><a href="#the-purpose-of-smart-contracts">The purpose of Smart Contracts</a></summary>
<ol>
<li><a href="#what-is-the-value-of-smart-contracts">What is the value of smart contracts?</a></li>
<li><a href="#what-is-smart-contracts">What is Smart Contracts?</a></li>
<li><a href="#why-we-should-trust-smart-contracts">WHY we should trust smart contracts?</a></li>
</ol>
</details>

<details>
<summary><a href="#blockchain-benefits">Blockchain Benefits</a></summary>
<ol>
<li><a href="#decentralized">Decentralized</a></li>
<li><a href="#transparency-and-flexibility">Transparency and Flexibility</a></li>
<li><a href="#speed-and-efficiency">Speed and Efficiency</a></li>
<li><a href="#security-and-immutability">Security and Immutability</a></li>
<li><a href="#counterparty-risk-removal">Counterparty Risk Removal</a></li>
<li><a href="#trust-minimized-agreements">Trust Minimized Agreements</a></li>
</ol>
</details>

<summary><a href="#what-have-smart-contracts-done-so-far">What have smart contracts done so far</a></summary>

<summary><a href="#gas-1-introduction-to-gas">Gas 1: Introduction to Gas</a></summary>

<details>
<summary><a href="#how-blockchains-work">How blockchains work?</a></summary>
<ol>
<li><a href="#hash">Hash</a></li>
<li><a href="#block">Block</a></li>
<li><a href="#blockchain">Blockchain</a></li>
<li><a href="#distributed">Distributed</a></li>
</ol>
</details>

<details>
<summary><a href="#signing-transactions">Signing Transactions</a></summary>
<ol>
<li><a href="#private-key">Private Key</a></li>
<li><a href="#public-key">Public Key</a></li>
<li><a href="#ecdsa">ECDSA</a></li>
</ol>
</details>

<details>
<summary><a href="#gas-2-block-rewards-and-eip-1559">Gas 2: Block Rewards and EIP 1559</a></summary>
<ol>
<li><a href="#what-is-a-block-reward">What is a block reward?</a></li>
<li><a href="#what-is-eip">What is EIP?</a></li>
<li><a href="#current-eth-fee-model">Current ETH fee model</a></li>
<li><a href="#eip-1559-goals">EIP 1559 Goals</a></li>
<li><a href="#what-is-eip-1559">What is EIP 1559?</a></li>
<li><a href="#current-fee-model">Current fee model</a></li>
<li><a href="#eip-1559-model">EIP 1559 model</a></li>
<li><a href="#miners">Miners</a></li>
<li><a href="#wallets">Wallets</a></li>
<li><a href="#gas-fees">Gas fees</a></li>

</ol>
</details>

# The purpose of Smart Contracts

### **What is the value of smart contracts?** 

(Trust minimized agreements) Basically Agreements and Promises, but unbreakable promises !

####  _Live Example of Aggreements_ : 
> - The lights in your house are powered by electricity which is a agreement from you and the electic company. 
You agree to pay them in return they’ll keep the lights on.
> - The electricity that they generate is agreement between them and engineers who build turbines to generate the electricity.
> - Almost everything you do and everything you interact with is the result of some form of agreement or contract in some aspect 
Always when give money for example to the bank to keep them safe. We thing inside ourself. How can I trust this person/bank? Will  they break their promise?

#### _Live Example of Broken Promise_ :

> - The Great Depression with the run of the banks. Banks promised to keep our money safe and that when we went back to go get it they would actually have the money there. And there were times that they didn’t have the money they’re. 
> - HiperInflation inside different countries
> - History is a lesson of reliable subjects who are notorious promise breakers

### **What is Smart Contracts**

- Cannot be altered(immutable)
- Automatically executes
- Everyone sees the term of the agreement 

> - The term **smart contract** was first used by Nick Szabo _(Computer scientist, Law scholar & cryptographer)_ in 1997, long before Bitcoin.
<br/>Nick Szabo wanted to use a distributed ledger to store contracts.
> - The smart contract are just like contract in real world . The only difference is that they are completely digital.
<br/> _In fact a smart contract is actually a tiny computer program that is stored inside a blockchain._

#### _Live example of what smart contract could fix:_ 
> There is a site which name is Kickstarter(the large fundraising platform)
Product teams can go to Kickstarter, create a project, set a funding goal and start collecting money from other who believe in the idea.
<br />Kickstarter is eesentially a third party that sits between product teams and supporters(the pople who funding).
<br/> **This means that both of them need to trust Kickstarter to handle their money correctly**.
If the project gets successfully funded, the project team expects Kickstarter to give them the money. 

![image](https://user-images.githubusercontent.com/57910640/201517783-7d9da7fb-5aae-4bb2-843d-f777d57e1680.png)

> On the other hand, supporters want theiy money to go to the project if it was funded or to get a refund when it hasn’t reached it’s goals.
Both the product team and it’s supports have to trust Kickstarter.
<br/> **But with smart contract we can build a similar system that doesn’t requre a third-party**
<br/>We can program the smart contract so that it holds all the received funds unit a certain goal is reached.

![image](https://user-images.githubusercontent.com/57910640/201517844-a66124ea-4fbe-4cac-8fc6-f797316de027.png)

> The supporters of a project can now transfer their money to the smart contract.

![image](https://user-images.githubusercontent.com/57910640/201517872-a9a78922-351a-48bf-b5ba-48569952171d.png)

> If the project gets fully funded, the contract automatically passes the money to the creator.

![image](https://user-images.githubusercontent.com/57910640/201517885-47e56c3a-1904-4b54-87f4-5de576e34c95.png)

> And if the project fails to meet the goal, the money automatically goes back to the supporters.
And because smart contracts are stored on a blockchain, everything is completely distributed. **With this technique, no one is in control of the money**


### **WHY we should trust smart contracts?**

> Because the smart contracts are stored on a blockchain, they inherit some interesting properties.
<br/> - They are immutable - means that once a smart contract is created, it can never be changed again 
<br/> - They are distributed - means that  the output of your contract is validated by everyone on the network
<br/>So a single person cannot force the contract to release the funds because other people on the network will spot this attempt and mark it as invalid.


# Blockchain Benefits 

Decentralized, Transparency & Flexibility, Speed & Efficiency, Security & Immutability, Counterparty Risk Removal, Trust Minimized Agreements

### Decentralized

> Means that the contracts don’t have centralized intermediary , the different individuals that run one of thse blockchains are know as node operators. And it’s combination of all these 1000s.
<br/> Of node operators running the same software, running these algorithms, running these smart contracts that make the network  decentralized. 

### Transparency and Flexibility

> Since all these individual node operators run the software, everybody can see everything that’s happening on chain. **Anything that’s going to be unfair, people will be able to see it and just not use.**
<br/>Everybody has perfect information and has to play by the the same rules.
<br/>That doesn’t mean that thre’s no privacy, the blockchain is pseudo anonymous meaning that you aren’t necessarily tied to an identity in real life.

### Speed and Efficiency

> Let say we want to transfer money from one bank to another bank which is in other Country. The bank just make basic math. 
<br/>Substract my money and added to the other account. But this can take weeks or mounths? 
<br/>Blockchain fix the problem, all these transaction happen instantly


### Security and Immutability

>One smart contract is deployed, that’s it, whatever is in the code is going to be in he code forever, they cannot be altered with in any way. That means the sucurity is much easier.
<br/>Whereas in a centralized world, somebody can hack into the server, jump into the database and  change some numbers, you can’t do that in the blockchain world.
<br/>And since it’s decentralized, in order to hack the blockchain, you’d have to take over half of the nodes as opposed to in the centralized world, where you only have to take over one in the regular world. If your computer and your backup computer go down, all of your data is gone. 
<br/>In the blockchain word, if your computer and your backup computer go down, all your data is safe, because it’s beign run on all these other decentralized nodes. And event if a few 100 nodes or a few 1000 nodes go down. It’s doesn’t matter because as long as one node has a copy of the blockchain, you’re good to go. 
<br/>Hacking a blockchain is nerly impossible, and leaps and bound more difficult than hacking a centralized server. 
<br/>Not only that, but this is safer in the asset sense as well. All you need to access your credentials and your information in your assets is your private key. Which is basically your password for all of this.

### Counterparty Risk Removal

> We remove this centralized intermediary, remove these trust gateways that we have to do in web two.

### Trust minimized agreements

> The smart contract. We move away from brand based agreements to math base agreements


# What have Smart Contracts done so far?

- [DeFi](https://www.investopedia.com/decentralized-finance-defi-5113835#:~:text=Decentralized%20finance%20(DeFi)%20is%20an%20emerging%20financial%20technology%20that%20challenges,peer%2C%20or%20P2P%2C%20transactions.) - Decentralized Finance
- [DOAs](https://ethereum.org/en/dao/) - Decentralized Autonomous Organizations
- [NFTs](https://www.investopedia.com/non-fungible-tokens-nft-5115211) - Not fungible tokens

# Gas 1: Introduction to Gas
> So before that we undestand that the blockchain is run by all the different nodes.Well all those different nodes are running this blockchain because they actually get paid for all the transactions that happen on these blockchains. 
<br/> Whenever you make a transaction there’s a node or a miner or a validator somebody running the blockchain software is gonna get paid a tiny bit of Etherium or Polygon or whatever blockchain that you’re running on, they’re gonna get paid a tiny bit of that native blockchain currency.
<br/>This payments is obviously to incentivize people to continue to run nodes and they calculate how much you pay and how much the node operators get paid based of how much gas you use.

**So there’s this concept of gas:
	_Gas: A unit of computational measurement.
	The more complex your transaction is the more gas you have to pay._**

For every transaction there is a gas limit & usage by the transaction

![image](https://user-images.githubusercontent.com/57910640/201519522-72f000f7-2ed6-4521-aff6-a4a3724c7b34.png)

Soo basically this transaction used 21 thousand units of gas.

In [metamask](https://metamask.io/) we can use different type of gas fees that you can actually pay. 
The reason that gas fees might change, depending on how busy the blockchain is, you have to pay more gas. 

![image](https://user-images.githubusercontent.com/57910640/201519549-75d05ed9-cc05-4030-b58e-26a85e55da36.png) 

If a lot of people are sending transactions, that means there’s not going to be eneough space for everyone’s transaction to get through

# How do Blockchains work?

#### Hash

#### Block

#### Blockchain

#### Distributed

# Signing Transactions

#### Private Key
Only know to the key holder, it’s used to sign transactions. 
You need to keep this private key secret, because you kind of using this as your secret password for all your transactions

#### Public Key
The public key is something that everybody can see.

#### ECDSA
ECDSA(Elliptic Curve Digital Signature Algorithm)
<br/>For ethereum and bitcoin the algorithm for converting the private key to signature is ECDSA

# Gas 2: Block Rewards and EIP 1559

#### What is a block reward?
 
> Bitcoin block rewards are new bitcoins awarded to cryptocurrency miners for being the first to solve a complex math problem and creating a new block of verified bitcoin transactions. 
<br/>The miners use networks of computers to do this, and every time a new block is created it is verified by all the other competing miners. Then a new math problem is introduced and the miners start over.

#### What is EIP?

> EIP stands for **Ethereum Improvement Proposal**.
<br/>And is a common way of requesting changes to the ethereum network inspired by bitcoin improvement proposals(BIPS)
<br/>EIP is a design document covering technical specifications of the proposed change 


#### Current ETH fee model

> The current fee model is based on a simple auction mechanism also known as a first price autcion.
<br/> The users who want to have their transaction picked up by a miner have to essentially bid for their space in a block. This is done by submitting a gas price. That they are willing to pay for a particular transaction. The miners are incentivized to pick up transaction by sorting them by  the highest gas prize and including the most profitable ones first.
<br/> This can be quite inefficient and usually reasults in users overpaying for their transactions.
<br/> **This model is also quite problematic when it comes to the wallets.**
<br/> Metamask for example allows the suers to adjust their fee, by choosing between, slow ,averageand fast confirmation time or by specifying a gas price manually.
<br/>Less sophisticated user were unlucky enough to submit their transaction with a default fee. Just before a spike in a gas fees may end up waiting for the transaction to be confirmed for a long period of time.

#### EIP 1559 Goals
> - Making transaction fees more predictable
> - Reducing delays in transaction confirmation
> - Improving user expreience by automating the fee bidding system
> - Creating a positive feedback loop between network activity and the eat supply
#### What is EIP 1559?

> EIP 1559 introduce new concept of a base fee. The base fee represents the minimum fee that has to be paid by a transaction to be included in a block.
<br/> The base fee is set per block and it can be adjusted up or down depending on how congested the ethereum network is.
<br/> The next big part EIP 1559 is an increase in the network capacity achieved by changing the max gas limit per block from 12.5 milion to 25 million gas, _basically doubling the block size_.

> With the base fee and increased network capacity EIP 1559 can build the following logic.
<br/> When the network is at more than 50 percent utilization the base fee is incremented. 
<br/> When the network is at lower than 50 percent utilization the base fee is decremented.
<br/> This basically means that the network aims at achieving equilibrium at 50 capacity by adjusting fees accordingly to the network utilization.

> EIP 1559 also introduce a miner tip, a separete fee that can be paid directly to the miner, to incentivize them to prioritize a transaction.
<br/> This is very similar to the current mechanism, where the miners can be incentivized by higher gas fees. This feature is really important for transactions taht take advantage of quick confirmation such as arbitrage transactions.

#### Current fee model

> Imagin the minimum gas fee to be included in the previous block was 50 GWEI the network activity seems to remain the same so users start submitting thei transactions with 50 GWEI to be included in the next block.
<br/>At the same time a new higly anticipated token is launched causing users who want to buy it to dramatically increase their bids.
<br/> Now to be included in the next block the minimum required fee is 100 GWEI if the network activity remains high for multiple subsequent blocks the users who already submitted their transaction with 50 GWEI may wait for their confirmations for a very long period of time. 
<br/> In this case the block size is capped at 12.5 million gas and the only way to get into a block is to bid higher than the other users.

#### EIP 1559 model

> The same example from Current fee model. 
<br/> The 50 GWEI was the base fee and the network utilization was at 50 percent with most blocks using 12.5 million gas half of the gas limit.
<br/> The spike caused by the release of the new token results in users submitting their transations with a higher minor tip, seeing the high demand for the block space and a lot of transactions with high minor tips.
<br/> The miners produce a block that is at the max cap limit of of 25 million gas 
<br/> This results in more transactions included in a block but it also causes the base fee increased in the following blok as the current block is 100% full. If the network activity and the block space remain high
the miners would keep producing full blocks increasing the base fee with each subsequent block.
<br/> At some point the fee would become high enough to drive off some of the users causing the network to start coming back to below 50 network utilization and lowering the fees in the subsequent blocks.
<br/> The base fee can increase or decrease by a maximum of 12.5% per block so it would take roughly **20 blocks around 5 mins for gas prices to 10x** and 40 blocks to 100x.

> In our example the second block would have a base fee of 56.25 GWEI
<br/> This example demonstrates how spikes in network fees can be smoothed out when EIP 1559 is implemented, another way of thinking about this model is to imagine that it basically swaps high volatility in the fee prices for volatility in the block size, because the increments and decrements are constrained the difference in the base fee from block block to block can be easily calculated.
<br/> This allows wallets to automatically set the base fee based on the information from the previous block
 <br/> To avoid the situation where miners can collude and artificially inflate the base fee for their own enefit the entire base fee is burned let's repeat this **the base fee is always entirely burned, the minor tip is always entirely received by the miner.**
 <br/> There is also one more important new concept known as a **fee cap**. 
 <br/> This can be said by users who would like to limit how much they want to pay for a particular transaction instead of just paying the current base fee.
 <br/> Transaction with a fee cap that is lower than the current base fee, would have to wait until the base fee is lower than the max fee set in feecap to be included in a block.
 <br/> The fee changes are also backward compatible. The legacy ethereum transactions will still work under the new fee system although they would not benefit directly from the new pricing model.

#### Miners

 > Changes proposed in EIP 1559 have a lot of implications some of them quite severe.
 <br/> Less profit for the miners. The miners in the current fee system receive both the block subsidy reward adn the entire gas fee.
 <br/> With the recent high gas prices caused by DeFi miners were abble to collect more money from the fees. Than the actual block rewards even though historically block rewards were always much bigger than the extra fees collected from transactions.
 <br/> After the changes in EIP 1559 are implemented the miners would only receive the block reward plus the miner tip.
 <br/> This is also why most miners are quite reluctant when it comes to implementing the proposal suggesting to push the change to ETH 2.0.

#### Wallets

>With EIP 1559 wallet don't have to estimate the gas fee anymore. They can jsut set the base fee automatically based of the information available in the previous block
<br/> This should simplify wallet's user interfaces.
<br/> The base fee burning also has major implications when it comes to the eth supply
<br/> This is also why EIP 1559 is very often deiscussed by eth investors.
<br/> Burning the base fee creates an interesting feedback loop between the netwrok usage and the eth supply.
<br/> More network activity equals more eth burned equal less eth avaiable to be sold on the market by miners.
<br/> Making the already existing eth more valuable.
<br/> Burning the base fee basically rewards the users of the network by making their ether more scarce instead of overpaying miners
<br/> The fee burning mechanism also sparked a few discussions about it becoming deflationary 
<br/> This would be possible if the block reward plus minor tip is lower than the base fee burned. That would be the case for example during the recent DeFi gas feed craze where the network was constanly under heavy utilization. 
<br/> One potential drawback when it comes to burning the base fee is the fact of losing control over the long-term monetary policy of eth. With this change it would end up beign sometimes inflationary and sometimes deflationary. This doesn't look like a major problem as the max inflation would be capped at around 0.5 - 2 percent per year.


#### Gas fees

> Will EIP 1559 make gas fee lower? 
<br/> Not really 
<br/> It will clearly optimize the fee model by smoothing these spikes and limiting the numer of overpaid transactions, but the main ways of lowering gas fees are still eth 2.0 and layer 2 scaling solutions.
<br/> It looks like EIP1559 would be a great change to the ethereum fee system
<br/> This also seems to be the consensus within the ethereum community. With the mojority of people rooting for the change to be implemented, there are still few challenges to overcome. Especially when it comes to making sure that miner can safely process bigger blocks without making the whole network more prone to denial of service attack.
All the clients should update at the same time

# High-Level Blockchain Fundamentals

> Now traditionally, when you run an application, you will be website or something that connects to some server, you are interacting with a centralized entity. And unlike how we saw with the blockchain with multiple different peers.
<br/>it's going to be run by a single centralized group. Now, it still could be run on many different servers, but all those servers are still going to be controlled by the same centralized group blockchains, as we saw run on a network of different independent nodes

<br/> When we saw a peer, a peer, B Piercey. Those were different examples of different independent users running the blockchain technology on their own node. 

>Now, when I use the term **node**, I'm usually referring to a single instance of a decentralized system. So when I say a single node, when I'm talking about a blockchain, I'm talking about one of those pure A's pure BS pure C's running that blockchain software, I'm talking about one server running this technology. And again, it's this network. It's this combination of these nodes interacting with each other, that creates this entire blockchain.

<br/>What makes these so potent too, is that anybody can join the network. And that's why there's decentralized the barrier <br/>
To entry is a little bit of hardware requirements for getting the correct materials to run the software. And then you running the software, anybody can join these networks and participate.
<br/>And that's what makes it truly decentralized.
<br/>Now in the traditional world, applications are run by centralized entities. And if that entity goes down, or is maliciously bribed, or decides that they want to shut off, they just can't, because they are the ones that control everything. 
<br/> Blockchains, by contrast, don't have this problem. If one node or one entity that runs several nodes goes down, since there are so many other independent nodes running that it doesn't matter, the blockchain and the system will persist so long as there is at least one node always running. 
<br/>And luckily for us, most of the most popular chains like Bitcoin and Aetherium, have 1000s and 1000s of nodes. 
<br/>And as we showed in our demo, if one node acts maliciously, all the other nodes will ignore that node and kick that out or even punish it in some systems, because they can easily check everybody else's node and see, okay, this one is out of sync with the majority. And yes, majority rules when it comes to the blockchain. Each blockchain keeps a full list of every transaction and interaction that's happened on that blockchain and we saw if a node tries to act maliciously, then all their hashes are going to be way out of whack and they're not going to match everybody else.
<br/> This gives blockchains this incredibly potent immutability trait where nothing can be changed or corrupted. So in essence, we can think of a blockchain as a decentralized database. And with Etherium, it has an extra additional feature where it also can do computation in a decentralized manner.

#### Consensus

> **Proof of work** and **Proof of stake** fall under this umbrella of consensus.
<br/> And Consensus is a really important topic when it comes to blockchains. Consensus is defined ** as the mechanism used to reach an agreement on the state or a single value on the blockchain. Especially in decentralized system.**
<br/> The example with the mojority nodes is part of these consensus mechanism.
<br/> Consensus protocal can be broken down into two pieces
<br/> - Chain Selection algorithm,
<br/> - A Civil Resistance mechanism
<br/> That mining piece that we were doing, or where the proof of work algorith is what's known as a **civil resistance mechanism**.
<br/>Now proof of work is known as a civil resistance mechanism, because it defines a way to figure out who is the block author. Which node is going to be the node who did the work to find that mine and be the author of that block so all the other nodes can verify that it's accurate.
<br>Civil resistance mechanism is a blockchain ability to defend agains users creating a large number of pseudo anonymous identities to gain advantageous influence over the system.

#### PoW and PoS

- PoW: Let's talk about proof of work a little bit more in depth first, in proof of work. This is civil resistant, because a single node has to go through a very computationally expensive process called mining, which we demonstrated earlier to figure out the answer to the blockchains Riddle of finding that correct nonce, or whatever the blockchain system has in place.  
<br/> This works, because no matter how many pseudo anonymous accounts you make, each one still has to under go this very computationally expensive activity of finding the answer to the proof of work problem, or the proof of work riddle, which again, in our demonstration, it was finding a nonce with that first four zeros. But again, each blockchain might change the riddle work or change the problem to be a little bit different. In fact, some of these blockchains make this riddle intentionally hard or intentionally easy to change what's called the block time.
<br/>The block time is how long it takes between blocks being published. And it's proportional to how hard these algorithms are. So these problems actually can change. Depending on how long they want the blockchain to
be. If a system wants to block time to be very, very long, they just make the problem very, very hard. If they wanted to be very short, they make the problem a lot easier. We'll talk about civil attacks in a little bit and how they can affect the system.But with proof of work, it's a verifiable way to figure out who the block author is and be civil resistant. <br/>Now, you
need to combine this with a chain selection rule create this consensus. Now, there's some consensus protocols that have more features, but very, very roughly, these are the two pieces that we're going to look at. The second piece is going to be a **chain selection rule.**

> How do we know which blockchain is actually the real blockchain and the true blockchain now on?
<br/> Bitcoin and Etherium, they both use a form of consensus called Nakamoto consensus. And this is a combination of proof of work and longest chain rule, the decentralized network side that whichever blockchain has the longest chain, or the most
 number of blocks on it is going to be the chain that they use.
 <br/> This makes a lot of sense, because every additional block that a chain is behind, it's going to take more and more computation for it to come up. That's why when we saw in our transaction, we actually saw confirmations. The number of confirmations is the number of additional blocks added on after our transaction went through in a block. So if we see confirmations as to it means that the block that our transaction was in has two blocks ahead of it in the longest chain. 
 
 > Now, I do want to point out that a lot of people use proof of work as a consensus protocol. And I do want to say that this is a little bit inaccurate, but sometimes people use it interchangeably..
 <br/>Proof of Work is a piece of the overall consensus protocol, which in Bitcoin and Etherium. One current case is Nakamoto consensus, Nakamoto consensus is a combination of proof of work, and this longest chain rule, both equally and very, very important.

 <br/>Now, proof of work also tells us where these transaction fees and these block rewards go to. Remember how when we made this transaction, we had to talk about gas and a transaction fee. So who's getting paid who was getting this transaction, and this transaction fee is going to the miners or the validators in a proof of work network? They're called miners and in the proof of stake network, they're called validators.

  > But all the nodes are trying as many as possible to try to get this answer first. Why? Because the first node to figure out the answer to the blockchain real is gonna get that transaction fee, they're gonna get paid from that. 
  <br/> Now, when a node gets paid, they actually get paid in two different ways. 
  <br/>One is going to be with a transaction fee. 
  <br/>And another piece is going to be the block reward. 
  <br/>Remember how we talked about alternating the gas price or the gray on our transaction? Well, that's the transaction fee that we're going to pay to these blockchain nodes for including our transaction, the block reward is given to these nodes from the protocol from the blockchain itself. 
  
  <br/>You've probably heard of the Bitcoin halving before the halving is referring to this block reward getting cut in half and it's supposed to be cut in half, roughly every four years. This block reward increases the circulating amount of whatever cryptocurrency that is being rewarded. For example, on Etherium the block reward is giving out Etherium and a Bitcoin the block reward is giving out Bitcoin. So these nodes are competing against each other to be the first one to find this transaction to be the first one to find the answer to this problem, so that they can be the ones to win both this block reward and your transaction fee. Some block chains like Bitcoin, for example, have a set time when they're no longer going to give out block rewards and the miners or the nodes are only going to get paid from trends. Action fees.
  <br/> Now this gas fee, again is paid by whoever initialize the transaction. When we got our funds from the faucet, there was some server and somebody else was paying the transaction fee for us. However, when we sent ether from one account to another, our first account actually paid some transaction fee to send that ether. In proof of steak. There's also a gas fee, but it's paid out to
  validators instead of miners. And we'll talk about that in a little bit.

  #### Type of attacks 1:50:20

 -  1. Sybil Attacks :
In Sybil attacks, the attacker attempts to fill the network with the clients under its control. When this thing happens the attacker can actually control or get a monopoly over the network and these clients can do different kinds of actions based on the instruction from the attacker. They can refuse to relay the valid blocks or they can only relay the blocks which are generated by the attackers and those blocks can lead to double-spending.
<br/>In Simple language, The attacker can include multiple nodes in the network who can collectively compromise the Proof of Work mechanism.
<br/>Solution –
To prevent Sybil attacks we have to diversify the connections i.e allowing outbound connection to one IP per / 16 IP address. So by diversifying the network it is expected that if the attacker generates multiple false miners the attacker will generate them within the same clustered network or subnet.
<br/>Note :
Although this solution makes hard to launch sybil attacks but it doesn’t make it impossible.

- 2. What Is a 51% Attack?
A 51% attack is an attack on a cryptocurrency blockchain by a group of miners who control more than 50% of the network's mining hash rate. Owning 51% of the nodes on the network gives the controlling parties the power to alter the blockchain.
<br/>The attackers would be able to prevent new transactions from gaining confirmations, allowing them to halt payments between some or all users. They would also be able to reverse transactions that were completed while they were in control. Reversing transactions could allow them to double-spend coins, one of the issues consensus mechanisms like proof-of-work were created to prevent.





 