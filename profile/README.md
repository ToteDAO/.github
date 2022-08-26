![Tote DAO Logo](/images/tote-logo.jpg)

# Tote DAO

## Problem

- While the Internet has seen major innovations, e-Commerce has been one of the recent success stories creating wealth for the past few decades.

- With e-commerce, users now need to rely more on customer reviews since the purchase experience lacks “touch-and-feel”

- While reviews are generally sought after by potential customers, companies too rely on reviews to improvise products in future batches/cycles

- However today, reviews available on e-commerce platforms in general are pestered by review farms and sometimes individuals may offer incorrect review or feedback

- While some review-specific platforms like Gartner and G2 have tried to fix this, there are not enough incentives for the reviewer and decentralisation factor in the whole ecosystem.

- In summary, verifiable good quality demography-specific reviews must be a basic access right to prospective customers as well as product companies. This seems to be an open problem.

## Solution

- Build a DAO that offers genuine reviews by targeted demographic users who are verified by their KYC-Ed ZK-proofed Wallet

- The DAO is made up of guilds, each focused on a track or theme such as Web, Mobile, FMCG products, and so on.

- Further, each guild is made up of a group of many tribes, where each tribe is a group of people based on geography, age and other factors. 

- While users belong to a tribe, their original identity is hidden away by the power of ZK proofs on the KYC data. This way, companies and potential customers can source honest reviews from specific demographics they favour without invading user privacy.

- The users, who join as DAO members, make an effort to identify themselves to a demography and provide genuine reviews and will be rewarded by the DAO in the form of bounty(offered by the product company in designated tokens like BTC, ETH, USDT etc.) and grants (offered by the DAO in its own native token to recognise their commitment and offer the power to govern the DAO with voting rights) 

- To ensure that reviews are not engineered by farms or by a biased disgruntled customer, we employ AI to track common keywords and bucket them. If a review is biased or may have an uncommon key words in the experience, it will try to create a new class of keyword for the same and flag it to the community for further review.

## Tech stack

| Tech | Why is it used |
|------|----------------|
| [Matic / Polygon](https://polygon.technology/) | The easiest ledger of choice today |
| [10M3](https://iome.ai/) | Zk-proofed KYC-ed private BIP44 wallet, powered by [MOI](https://moi.technology/) |
| [Web3.Storage](https://web3.storage/) | Storing review data and related datasets |
| [Spheron Protocol](https://spheron.network/) | To access Polygon Network |
| [Covalent API](https://www.covalenthq.com/) | To query Polygon Network and apply NLP on review datasets |
| [EPNS](https://epns.io/) | To alert users on status of actions |
| [Arcana Network](https://arcana.network/) | To share product insights with companies in a permissible manner|
| [Router Protocol](https://www.routerprotocol.com/) | Cross-chain settlements of bounties |
| [React.js](https://reactjs.org/) | Front-end web app for DAO activities |
| [Node.js](https://nodejs.org/en/) | For some middleware activities |
| [Solidity](https://docs.soliditylang.org/en/v0.8.16/) | Not-so-smart contracts, duh! |

## Team

We are a team of 3:

👨‍🔧 [Ganesh Prasad Kumble](https://github.com/0zAND1z) (Ideation and full-stack),

👨‍🎨 [Pradeep Pradyumna](https://github.com/pradeepradyumna) (Front-end and presentation), and

🧑‍🔬 [Madhusudhan Kumble](https://github.com/madhukumble) (Data Science and story-boarding)
