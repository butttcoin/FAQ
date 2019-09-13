# ButtCoin Version 2 FAQ (Constantly under construction)

## VERSION QUESTIONS:
### Why are there so many different BUTT coins on Etherscan ?

There are two possibilities. One is that 0xBUTT has not created them. Other possibility is that you are looking at very old contracts that 0xBUTT team was test-launching and learning about the Ethereum network and Solidity. These are the old contracts that were generated, while any other contract (other than version 1 and 2) were not created by 0xBUTT:

- 0x3324f4af7eE967bFA35A5AcCba7Df13e7C932397
- 0xbF633d148a67B551bD643783d2dC3cEAEae31a62
- 0x54CCf0c46D45b85A37f960cBe1ECAfAe5844252b
- 0x972bd5c035ebba067489863158ec8556852bad42

ButtCoin is a concept that existed a few years before the 0xBUTT, so it is possible that people are creating the contracts without even knowing about 0xBUTT !

### I can't get rid of the tokens since I am getting 1% from the next person's transactions. How do I get rid of it ?
Make a new Ethereum account, send all tokens to that account, then send the minumum amount (0.0000001) to some third account. That way, you will get 0 tokens from the next transaction and you will get rid of the tokens.


## SNAPSHOT QUESTIONS:
### Where can I get my Version 2 tokens ?
1. If you held less than 100, go to https://multisender.app/merkle?ipfs=QmR6X4D1Dod9pmUwCTrmudoobayoWV1nhuA3Bzg2fxF7BG

2. If you held more than 25K, please send a personal message using Twitter (https://twitter.com/0xbutt), Telegram (https://t.me/BUTT_Coin), or email info@0xbutt.com, or email 0xbutt@protonmail.com YOU MUST INCLUDE YOUR ETHEREUM ADDRESS!

3. If you held more than 100 and less than 25K, please follow the steps under #2.

### Why the second version ?
1. There was a bug and the token can be hacked. Nobody hacked it, and nobody knows how, but it does have a big hole in it !

2. It was the opportunity to improve the token and make it the best mine-able and the self-destructing token on a market !

### What was the bug about and how can I reproduce it ?
Lets just say that if you had the right skills, you could produce as many tokens as you like. here is the proof!
https://etherscan.io/tx/0x44931b20203b2c40224b676067a41333be3d3497f3dbbef0b6500add33ca8db8

### What can I do with the old version, and is it safe ?
It is safe, the bug has been locked, and there is no guarantee that someone else will not be able to hack it. You can still trade it on a token.store https://token.store/eth/trade/0xBUTT

## EXCHANGES QUESTIONS
### Where is it listed ?
Currently, it is not listed anywhere. We are working on getting it listed on DDEX again. It will be on DDEX for a while.

### How many exchanges are you planning and why ?
For now, just DDEX (with BambooRelay and Uniswap). The reason is because more exchanges means lower trading volume per exchange. New exchanges are to be considered when safe to split the trading volume.

### Can I list the coin on other exchanges ?
No, and don't try, their addresses will be blacklisted and all of the tokens burned.

## MINING QUESTIONS:
### Is there a mining pool ?
1. Not yet.

### Can I mine the token ?
2. Yes, but please see the reward and include the 8 decimals. https://etherscan.io/token/0x5556d6a283fd18d71fd0c8b50d1211c5f842dbbc#readContract

### I want to solo-mine, what should I do ?
Take this tutorial for the version 1, and make sure that the contract address is 0x5556d6a283fD18d71FD0c8b50D1211C5F842dBBc
https://github.com/butttcoin/tutorials/tree/master/mining/solo

### You mentioned multiple mining algorithms, how does that work ?

Simply, using the power of Solidity, we can create another contract that makes a call to original contract. This means that we can mine the second contract and get the rewards using the first contract. This also means that we can have as many mining algorithms working together as we want. We can also mine to burn!

## DESIGN QUESTIONS:
### What is the blacklist and why is it necessary ?
It is a security feature to prevent the scammers getting the unfair advantage from the token. Should any account become blacklisted, their tokens will burn as soon as they try to make a transaction.

### What is the rootAccess list and why is it necessary ?
This is to enable multiple contracts to "talk to each-other" and to give some privileges.

### What is the whitelist ?
Currently it doesn't have any value but it can be used in the future connecting the multiple contracts together.

### What is the lock ?
We can lock and unlock any function we want. If we had this feature with the version 1, there wouldn't be any need for the version 2. Also, we can override and lock the functions with other contracts. This is our solution to Ethereum's immutability!


## ROADMAP QUESTIONS:
### What is next for the ButtCoin ?
- Update the BitCoinTalk
- Update the WhitePaper
- Request the Etherscan to approve it
- Update the Webpage
- Request the DDEX re-listing
- Redo all the steps as listed on a /r/0xBUTT Reddit page
- Do a collaboration with SHUFF token to for a self-drop distribution
- Do a collaboration with Brapper token, so you can tip people the 0xBUTTs
- Make the mining pools for distributing the minted tokens
- Make the mining pools for mining the burned tokens

## AIRDROP QUESTIONS
### Will there be any airdops ?
No, HOWEVER, this is the last airdrop that will happen : reddit.com/r/0xBUTT/comments/cs31qe/buttcoin_fancy_airdrop_read_here/

### Why ?
Because the airdrop model does not work. It can do a lot of damage to a token.


## BLOCKING ACCOUNTS
### I was blocked on Twitter, Telegram, ... why ?
If you think there was a mistake, please message us via e-mail and everything will be explained to you nicely.


## SOCIAL PAGES AND NETWORKS
### Are there any rules and regulations to follow on the social media?

Yes, and they are universal for each social media such as Reddit, Twitter, Telegram, and others.

1. Bots
ButtCoin is strongly against any bot activities and gaining the unfair advantages. Any bot activity will result in banning, immediately. This also includes advertisements and spammers.

2. NSFW, violence and abuse
ButtCoin takes no responsibility for any material posted. Any controversial posts that might be considered NSFW will not be deleted. Anything distasteful, hardcore, violence (toward animals and/or humans), gore,... will result in banning, immediately. This also includes the material wrapped up with a humour, which is actually act of aggression.

3. Respect, or the lack of thereof...
Any disrespectful posts will be removed, and if the behaviour continues, it will result in a banning. How do we define respect? It is very simple: as long as there is no complaint, it is considered respectful. ButtCoin has no right to consider any content disrespectful, unless reported by someone.

4. Trolling
This behaviour is expected to happen at any point. We will not ban any trolls, and they should have the freedom of expressing themselves, as long as it respects all other rules.
