# Web 3.0
## Key Concepts
1. Decentralization
2. Blockchain
3. Tokenization

## Opportunities and Interesting Ideas
1. Be the company that builds the **infrastructure** of the new Internet. Basically the next Google.
2. Attention tokens -> new way of advertizing (users now get a choice to sell their data and attention)
3. Blockchain in space

## Challenges
1. Centralized databases are faster, more power-efficient.
2. **Scalability** of decentralized databases seems to be a perpetual issue.
3. Decentralized currency seems to be the only application of the blockchain.
4. 投机>投资>使用.

## Evolution of The Web
1.0 static, read only, like reading magazines, but on a screen 
2.0 read-and-write, interactive, rely on user-generated contents (this era)
3.0 decentralized, users are owners

## Blockchain
### How does blockchain work? 
- Basically a **decentralized database** implemented as a **linked-list of blocks**.
- Each block contain 1. prev hash 2. data 3. nonce. 
- With these things together, we calculate a new hash as the identity of this block. Hash changes when anything inside a block changes.
- Every node(computer) in the network has the same copy of the blockchain (a user might not be a node).

### What is and why proof-of-work?
- Blockchain documents transactions-> Transactions happen at different times -> conflicts -> To reach agreements -> need a **consensus mechanism** 
- Adding a block should be made harder -> people adding the block needs to "prove" that they've done significant "work".
- The act of adding blocks to the chain is called **mining** -> there are people (**miners**) who compete for the right to add a block
- Miners calculate hashes for each block through trial-and-error
- Hashes are hard to calculate, but easy to verify.
- Miners are rewarded with coins (cuz they keep the network secure) 
- added blocks are broadcasted to the entire network and verified by others -> different nodes do a vote 
- If majority votes "valid", the state of the chain is updated. If the majority thinks your solution is invalid-> rejected 
- Also, if different copies of valid chains exist -> majority wins (Only need to check the hash of the last block to verify equality of the entire chain)
- That's why 51% attacks are possible. -> If I control 51% of the network, I can alter it at my will. 
- If two miners mined a block at the same time(unlikely) -> both broadcast their chains and keep working on the next block -> other people accepts the longest of all chains-> however, both get rewarded .
- Key principles: **1. Longest chain wins 2. Majority wins**

### Say I'm a hacker...
- If I change a block in the middle -> all calculated hash change-> had to recalculate nonce for all subsequent blocks to make your version of the chain valid
- AND since people accept the longest chain, so you must be faster than everyone else!
- If I change the most recent block -> the nonce you calculated is different from others -> majority rejects you

## Web 3.0 and Tokenization
- digitized ownership of properties, not just houses, cars, but also data, attention, computing power
- exchange through token swaps -> intermediaries eliminated -> efficiency
- Network runs on user-contributed computing power. Users get tokens. 
- When users perform actions, they incentivize other users by paying tokens.

### Fungibility and NFTs
- Fungible -> something thats equal to one of itself. Your dollar bill equals to my dollar bill.
- NFTs, non-fungible. Your house is not the same as my house. Each token represents sth different. 

## General Comments
The Internet "of the people, by the people, and for the people" is an unrealistic catchphrase. As long as governments and central banks exist, they would never allow a financial system that operates independently from the current one. Taking crypto as an example: it has lost the anonymity which crypto-enthusiasts fervently touted. (major crypto-trading websites now require identity verification before one can buy and sell coins). 
Moreover, notice how web3 startups sell their ideas by portraying web 2.0 tech giants as the bad guys, and claim to "give data and freedom back to THE PEOPLE". However, eventually someone has to write up the web3 softwares, someone has to set up servers and pay for the bandwidths. A profit-seeking third party will always be involved; it's just a matter of who. 
This is also where the opportunities lie, whoever gets to build the infrastructure on which web3 runs will become the next generation of tech giants, until being taken over by web 4.0 and 5.0. 
Web 3.0 may not be a leveled playing field considering the web 2 giants have already hoarded a ginormous amount of data without paying a dime, much like how Western countries completed their initial capital accumulation process through colonization and expropriation. Based on the fundamental principle of exchanging data for tokens, web2 giants will still own a large stake in the new Internet and thus creating a monopoly or oligopoly market structure.

communism and 
The logic of capitalism remains

## Useful Links
https://andersbrownworth.com/blockchain/hash

https://calpaterson.com/blockchain.html

https://web3isgoinggreat.com/

https://www.gemini.com/cryptopedia/the-dao-hack-makerdao#section-the-dao-hack-remedy-forks-ethereum

https://www.stephendiehl.com/blog/web3-bullshit.html

共产主义理想 - 生产资料公有化？ not really 

digital assets are not the entirety of someone’s assets?

Is data a means of production?  