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

#### EIP 1559 model
 
#### Miners

#### Wallets

#### Gas fees