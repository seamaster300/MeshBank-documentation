# MeshBank Software Roadmap
This document outlines the development plan from a high level and will be updated as progress is made towards beta release. 

**Everything contained in this document is in draft form and subject to change at any time and provided for information purposes only.  MeshBank does not gaurantee the accuracy of the information contained in this roadmap and the information is provided "as is" with no representations or warranties, express or implied.**

## Phase 1 - Initiation
### Why this project?
MeshBank aims to be the most user-friendly and most on-chain-scalable cryptocurrency in the world.
Its network features instantly confirmed, double-spend-proof, optionally anonymous transactions, a self-governing & self-funding model through incentivized full nodes and a roadmap to scale to up to 400MB in blocksize
MeshBank is a true Decentralized Autonomous Organization (DAO). Our network is able to hire and pay people to improve itself.
### Is it feasible?
Yes. 
### Who are possible partners in the project?
Users, cryptocurrency enthusiasts, investors, banking institutions, credit card processors, financial companies, ecommerce platforms, transit systems.
### What should the results be? 
A better way to save, spend, and invest money. 

MeshBank value explained:
The MeshBank core development team has built a platform that allows for instant and secure peer-to-peer transactions to occur on a decentralized network. MeshBank's network utilizes high performance servers called "Masternodes" that insure stability, performance, and security of the network. 

Everything that MeshBank core development team builds is open source: [Masternodes Github](https://github.com/meshbank/meshbank)

## Phase 2 - Project Requirements
### Overview
1. [MeshBank Wallet](#meshbank-wallet-application)
2. [MeshBank Core](#meshbank-core-application-runs-on-validator-nodes)
3. [MeshBank DAO](#meshbank-dao-decentralized-autonomous-organization)
4. [MeshBank Website](#meshbank-website)


#### MeshBank Wallet Application
- Send, receive, hold, monitor masternodes
Q1 2018: Desktop gui application
Q2 2018: Beta ios application (lite client?)

#### MeshBank Core Application (runs on masternodes)
- This is the main application that runs on MeshBank masternodes. 
- Remote management of masternodes via wallet application.
Q4 2017: Release daemon, and cli

#### MeshBank DAO (Decentralized Autonomous Organization)
- Budget Proposals can be created for 5 MESH
- Masternodes can participate in MeshBank's self governance
Q1 2018: Voting enabled

#### MeshBank Website
- Pages (Get MESH, Merchants, Network, Resources, Team, Blog, Development)
- Listed Markets (Cryptopia, Bittrex, Kraken)
- SEO
Q4 2017: Build Website

## Phase 3 - Design
Products:
Dioramas, sketches, flow charts, site trees, HTML screen designs, prototypes, all user interface etc.
![DAO Voting Application](/images/dao-voting.png)

## Phase 4 - Development & Bounties
### MeshBank
- [ ] Develop MeshBank's Website
- [ ] Create pages (get-mesh, merchants, network, resources, team, blog, development, lanaguage flag)
- [ ] Link domain meshbank.com -> https://meshbank.github.io/MeshBankWeb
- [ ] Youtube videos (What is MeshBank, How to setup MeshBank Wallet, How to setup MeshBank Core (masternode), How to participate in MeshBank DAO)
- [ ] Facebook Community (Weekly MeshBank Core Development team posts)
- [ ] Twitter Community (Daily cryptocurrency posts, updates, news, ATH prices, legislature, etc.)

### MeshBank Core (masternode daemon)
- [ ] Create MeshBank Core
- [ ] Create Download installer Windows
- [ ] Create Download installer OSX
- [ ] Create Download installer Linux
- [ ] Provide hash file, and pgp for each download file and upload to website "/get-mesh"
- [ ] Implement zk-Snark update 

### MeshBank Wallet
- [ ] Create wallet
- [ ] Create Download installer Windows
- [ ] Create Download installer OSX
- [ ] Create Download installer Linux
- [ ] Provide hash file, and pgp for each download file and upload to website "/wallets"

### MeshBank DAO
- MeshBank's allows stakeholders to vote on budget allocations. Budget requests by MeshBank's dev team will have our logo. 
- [ ] Any user can create a proposal for 5 MESH
      - The community budget can be spent on said proposals. Voting occurs every month at a set block.
- [ ] Approval system:
      - Net Votes: TotalVoteYes minus TotalVoteNo 
        - must be greater than CountActiveMasternodes/10 --10% active masternodes
      - Monthly Amount: Budget priority order by net votes. 
      - proposal must be over 24 hours old
      - proposal must be submitted 3 days before budget allocated
- [ ] Budgets Proposals
      - Datatable (title, owner, payment, yes, no, abstain, net votes, % of vote, monthly amount, total budget requested, actual budget allocated)


### MeshBank Products
- [ ] Hardware wallet
- [ ] ATM Machines
- [ ] Merchant POS

