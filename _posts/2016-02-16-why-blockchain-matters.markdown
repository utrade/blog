---
layout: post
title:  "Why does Blockchain matter?"
date:   2016-02-17
author: "Kunal Nandwani"
categories:
---


Blockchain is likely to be the most hyped database in the current decade. It is the core technology that enabled bitcoin, which has had challenging ups and downs due to business reasons.

Blockchain has the ability to bring lot of efficiencies in how information is created, shared, accessed, secured, and relies upon crowd efforts for validating the correct information. Hence it is compared with the Internet revolution that started in late 90s. Similar to the early days of Internet revolution, Blockchain has lot of useless attempts of me-too players solving a meaningless problem. The important thing to understand is what is the core problem and can block-chain really help at all. 80% efforts should be allocated to validating the business scenario and the solution, blockchain implementation is likely to be the easier technology part (which has possibly scale challenges due to early stage nature of existing blockchain technologies available in the market, discussed further below).

## What is Blockchain

Blockchain is basically a database.
Blockchain is a distributed database.
Blockchain is (arguably) a crowd-managed distributed database.
Blockchain is a crowd-managed distributed secure database.

In a blockchain, copies of a ledger are “distributed” and validated by a consensus process, with multiple users independently verifying ledger changes.

Blockchain was invented as the technology to manage and run Bitcoin. As you may know, Bitcoin was the first digital currency, which was not governed by any Central Bank, no notes were printed, and it was largely up to the worldwide users to ensure it works, without any central authority. In Bitcoin, the most well-known blockchain application, tokenized transfers are made directly between payer and payee, effectively eliminating the credit and liquidity risk inherent in the fiat system.

## Potential Applications of Blockchain

Decentralize everything is the core theme of blockchain. Since it successfully supported Bitcoin for years, its ready for experimentation in various other industries and use cases, including:

### Digitization of Assets

A company or an authority or similar entity typically centralizes all the asset registrations. What if they could move to blockchain to make it more transparent, efficient, faster and secure. This could apply to
- Housing / Cars registration
- Luxury assets like paintings, diamonds with digital certificates

### Digital Legal system

Various legal documents are signed by different parties and stored in physical / scanned format and possibly registered with any central authorities. It could securely move to digital format with standardized / custom contract and digital secure signatures embedded within the blockchain itself. Eventually this maybe used to introduce Smart Contracts which can be actionable events based on conditions like time, etc. For example, the Will of a person maybe to enable inheritance of his wealth upon a certain time or event like his death.

### Crowd sourced platforms

Many platforms like Wikipedia could benefit dramatically from Blockchain’s information creation and management system.

### Identity

Digital id creation for every individual, combining the decentralized blockchain identity verification can create the largest unique digital ids in the world, which various Governments in different countries have failed to do yet.

### Financial Markets

Financial institutions including banks have inefficient processes, and legacy infrastructures to manage transactions. Various post trade transactions for payments (example in banks), clearing / settlement in securities world (stock markets), could be dramatically improved by using Blockchain.

But due to high overheads and delays in validating various blocks before the transaction, blockchain may not be useful in live trading processes as yet. This may change, as blockchain technology gets more mature, scalable and faster in the next few years.

### Insurance

Blockchain transforms the way people manage identities and personal information, leading that could change the way insurers review risk and price the premiums. Blockchain applications in insurance are likely to start with digital identity systems and management of personal data. Smart contracts (where the outcome is pre-determined or even based) can help end users self administer their insurance policies.

## Technical aspects of Blockchain

Blockchain is a sequential transaction database, which contains a continuously growing list of all the transactions, which have occurred in the system. All the recent valid transactions are bunched into a block (hence the name blockchain), which are then timestamped and stored using strong cryptography. Every new block added to the blockchain database, contains a hash (cryptographic hash) of the previous block, which makes it tamper-resistant. This is because changing any particular transaction in the blockchain database would change the hash of the block being tampered with, which would cascade to all the subsequent blocks added in the blockchain.

The blockchain database may be stored fully or partially by a set of nodes (and/or miners), which can verify any transaction being done on the blockchain and these act in “consensus”. Also, in a bitcoin blockchain, a miner has to solve a hard cryptographic problem to confirm/add a new block on the blockchain. This work done by miners is called proof-of-work (and the miners are adequately rewarded for this computationally expensive work being done by them). The proof-of-work makes the database resilient to attacks, as any attacker will need to have control on more than 51% of the computing power of the network to tamper with the transactional data.

A sample visual representation of blockchain is done below:

![Blockchain]({{ site.url }}/assets/blockchain.png)

## Challenges of Blockchain

*Scale*: Cost of computing, energy consumption in mining for transactions becomes very high as the blockchain increases in size. Also, the growing size of blockchain can be a problem as any need node will need to replicate the blockchain, which may take many days.

Speed Currently, maximum no. of transactions supported in public bitcoin blockchain are 7 per second, with proof of work / validations in place.

*Recourse / Modifications*: Its virtually impossible to modify a transaction once it is put in place.

*Private versus public vs mixed*: Public blockchains can scale but make process slower, Private ones can be faster but then the use case for blockchain needs to be clear (otherwise a simple shared database may work) and mixed permission based blockchains are in fairly nascent stages yet.
Adoption and integration For any disruption, the integration and replacement of current systems and workflows are the biggest challenge. It makes it harder for banks to adopt any change quickly.
Legal challenges For any disputes arising from blockchain transactions, there are various loopholes where the existing legal frameworks and courts may not be able to resolve the disputes easily.
Future of Blockchain
Its possible that blockchain may go through an internet like bubble bust and boom cycle, just compressed into lesser timeframe as shown below.




