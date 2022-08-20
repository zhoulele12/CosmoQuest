# Web 3.0
## Key Concepts
1. Decentralization
2. Blockchain
3. Tokenization

## Opportunities 
1. Be the company that builds the **infrastructure** of the new Internet. Basically the next Google.

## Challenges
1. Centralized databases are faster, more power-efficient.
2. **Scalability** of decentralized databases seems to be a perpetual issue.
3. Decentralized currency seems to be the only application of the blockchain.
4. 投机>投资>使用.

## Evolution of The Web
1.0 static, read only, like reading magazines, but on a screen 
2.0 read-and-write, interactive, rely on user-generated contents (this era)

## How does blockchain work? 
- Basically a **decentralized database** implemented as a **linked-list of blocks**.
- Each block contain 1. prev hash 2. data 3. nonce. 
- With these things together, we calculate a new hash as the identity of this block. Hash changes when anything inside a block changes.
- Every node(computer) in the network has the same copy of the blockchain (a user might not be a node).

## What is and why proof-of-work?
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
- - If two miners mined a block at the same time(unlikely) -> both broadcast their chains and keep working on the next block -> other people accepts the longest of all chains-> however, both get rewarded 
- Key principles: **1. Longest chain wins 2. Majority wins**

## Say I'm a hacker...
- If I change a block in the middle -> all calculated hash change-> had to recalculate nonce for all subsequent blocks to make your version of the chain valid
- AND since people accept the longest chain, so you must be faster than everyone else!
- If I change the most recent block -> the nonce you calculated is different from others -> majority rejects you

## Fungibility and NFTs
- Fungible -> something thats equal to one of itself. Your dollar bill equals to my dollar bill.
- NFTs, non-fungible. Your house is not the same as my house. Each token represents sth different. 

## Useful Links
https://andersbrownworth.com/blockchain/hash 

https://calpaterson.com/blockchain.html 

https://web3isgoinggreat.com/ 

https://www.gemini.com/cryptopedia/the-dao-hack-makerdao#section-the-dao-hack-remedy-forks-ethereum 

https://www.stephendiehl.com/blog/web3-bullshit.html 


怎么赚钱？

怎么管理？

tokenization -> digitized ownership -> intermediaries eliminated -> efficiency  

Token -> digital asset 

Contribute computing power, get tokens 

Perform actions -> need to pay -> crypto 

Can choose to sell data -> tech giants have already completed their initial capital accumulation process 

Smart contracts 

Stored on blockchains


共产主义理想 - 生产资料公有化？ 

not really 

digital assets are not the entirety of someone’s assets?

servers are owned and operated by a third party still 

Is data a means of production?  

Ponzi scheme? 

Blockchain and space 