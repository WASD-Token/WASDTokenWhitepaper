
# WASD Token

(Whitepaper version 1.3)
### WASD Token: Offering a unifying in-game payment currency.
---

### Abstract
This document describes the ERC20 token 'WASD Token' (WASD). The cryptocurrency was deployed to the Ethereum Blockchain and has been developed using the Solidity programming language. For creating this document we borrowed ideas from the official Bitcoin (BTC) whitepaper as well as the whitepaper of 0xBitcoin (0xBTC). 'WASD Token' is a native ERC20 compliant cryptocurrency as it's written following the official standard and has no reliance on third parties.

### Background
The Ethereum Network has withstood the test of time and proven itself as a blockchain and furthermore as a platform for immutable software applications, so called DApps. By offering this platform, many protocols have been developed and standardized for it, with ERC20 being one of the more prominent ones. The ERC20 standard has gained a lot of traction and is increasingly getting more popular as time passes.

ERC20 has opened the door for smart contracts to be developed and deployed on the Ethereum blockchain, thus gaining all the benefits of the underlying network itself. Smart contracts are distributed in a way that is generally known as 'security' in form of a so called token. This tokens are then sold to investors under the premise of the project vision, which will fuel the value of the token itself. In comparsion, Bitcoin is a currency that is distributed by 'mining bitcoins', which makes them a more of a 'commody' rather than a 'security' in a traditional way of thinking.

This whitepaper will describe what makes 'WASD Token' a security in the first place, while still being a commodity and how it tries achieves that.

### Origin of the name WASD Token
The name 'WASD Token' is derieved from the W, A, S, D keys found on a keyboard. Especially in FPS and MMORPG games they are usually the main keys that are being used, since they are often assigned to movement which is constant in such games. Therefore in communities with an interest in gaming those letters are often associated with gaming when combined as a sort of pseudo word. WASD! It stand for gaming.

### Network Security
'WASD Token' comes with all the securities of the Ethereum blockchain, since it operates as a smart contract on top of it. 'WASD Token' does not operate it's own network and oblieges therefore to the same rules as Ethereum operates under. The current danger from double-spending by a 51% attack are still present, allthough very unlikely taken the current difficulty level an processing power needed for it. Nonetheless, they are a base problem of the Ethereum Blockchain itself and affects 'WASD Token' as well. 'WASD Token' will be released on the Ethereum Blockchain which is based on Proof-on-Work (PoW) at time of writing.

### Account Security
'WASD Token' is an ERC20 Smart Contract that operates on the Ethereum Blockchain, the risk of loosing an account by an attacker are highly unlikely as long as the private key hasn't been exposed or saved in an online accessible storage. Since ERC20 operates on the Ethereum mainnet, it follows the same risk and rules for creating and owning an account. Creation of an Ethereum account is free of charge at time of writing.

### Proposed Use Case
By combining the ERC20 smart contract standard and adding the Bitcoin PoW reward mechanism, it unifies the advantages of both creating a highly versatile and unique currency on the current market. The result is an easy to use currency that can be mined and incetivizes user to take part in what 'WASD Token' is trying to achieve. With the addition of compatibility with other ERC20 tokens it lays the foundation to be future proof. With the rising acceptance of E-Sports and gaming in general by modern society, the need for having a unified and streamlined payment solution for in-game purchases has gotten bigger over time.

'WASD Token' aims to solve this problem by offering a common currency, game developers can adapt directly into their products withouth the need of third parties. As an ERC20 smart contract on the Ethereum blockchain it offers multiple benefits for all parties involved, since it offers the possibiliry to interact directly with eachother bypassing the need for an external payment proceessors.

### Mining
'WASD Token' implements the same PoW method that was itself created and implemented by Satoshi Nakamoto into Bitcoin. It follows the same rules and type of work that has to be done. A 'nonce' number has to be found, which when hashed correctly with other data, such as challenge number and Ethereum address, creates an output called 'digest' that is lower than the current difficulty of the coin. As with Bitcoin, the difficulty of finding said nonce will adjust automatically after a certain amount of time and aims for a median time of 10 minutes per granted reward.

The algorithm used for the mining process is a SHA3-256 (Keccak) function, which the output of it will be compared to the difficulty target. The user has to input the 'nonce', his Ethereum address and the the challenge number the 'nonce' is for. The address will be used as part of the hashed solution, which itself enables the possibility for mining pools and mitigation of man-in-the-middle attacks. The challenge number will always be the hash of the most recent Ethereum block to prevent pre mining.

### Smart Contract
The ERC20 tokens will initially be offered to investors through an Initial Coin Offering (ICO), which will grant an additional 1% tokens on top of the amount for each purcha through a buyer. After the ICO the token will be transfered to the owner adress, which will then offer the tokens as liquidity on decentralized exchanges. 40% of the the total supply amount will be locked inside the contract and has to be mined through PoW.

The tokens will be rewarded 100 at a time during the first reward stage, and will then be halved each time a new reward era is entered. The first era includes a total of minable tokens equal to the half of all the tokens available for mining (200'000'000). Each time that amount is exceeded, the amount will be halved again for the next era. Analog to Bitcoin, the difficulty will be adjusted after 1024 rewards (blocks) have been payed out. Since there are no real blocks being mined, the number will be compared to the average amount of Ethereum blocks that can be mined in 10 minutes, which would translate roughly to 45 block per 10 minutes.

The Ethereum blockchain adjusts the difficulty to be between 10 and 19 seconds per block, which translates to a maximum of 60 and minimum of 31 blocks per 10 minutes. As the average blocks per day has been between 5.8k and 6.5k, we chose a number based on that range.
