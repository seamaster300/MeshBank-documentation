# MeshBank Software Roadmap
This document outlines the development plan from a high level and will be updated as progress is made towards beta release. It should be noted that this roadmap applies only to the blockchain related software, after phase 4 is complete, a dedicated team will build on other tools and utilities such as wallets, and block explorers.

**Everything contained in this document is in draft form and subject to change at any time and provided for information purposes only. MeshBank does not gaurantee the accuracy of the information contained in this roadmap and the information is provided "as is" with no representations or warranties, express or implied.**

## Phase 1 - Initiation
### Why this project?
MeshBank aims to create the most powerful infrastructure for decentralized banking applications. Publically auditable contracts create a self-regulating, decentralized network of interconnected nodes. The infrastructure provides a scaleable, reliable, decentralized network with unrivaled transaction speed and security.

### Is it feasible?
Yes. Utilizing Ethereum Virtual Machine (EVM) we can run applications on the gigantic distributed computer. 

### Who are possible partners in the project?
Banking institutions, credit card processors, financial companies, ecommerce platforms

### What should the results be?
1. MeshBank is a decentralized autonomous organization that has real world employees that power the business. 
2. Nodes can vote on monthly budget allocations through community self governance.
3. Desktop application that allows users to send, receive, and invest in MeshBank's infrastructure (instant transactions, private "zk-snarks protocol", secure)
4. P2P Exchange built into desktop application (See bisq fork)
   - Support various easily accessible payment methods: Cash deposits, Zelle (Bank transfers with supported banks)
   - Exchange various currencies (MESH/BTC, MESH/ETH, MESH/LTC, MESH/USD)


## Phase 2 - Project Requirements
  
   ### Functional requirements
         Digital currency
         What the system is supposed to do, process orders, send bills, regulate the temperature etc. etc.

      #### MeshBank Wallet Application
      - send, receive, transactions, manage validators

      #### MeshBank Core Application
      - This is the main application that runs on the network masternodes. Masternode uptime, connection, and payouts can be monitored from any wallet. 

#### Decentralized Autonomous Organization 

#### Decentralized Exchange
**Due to the irreversable design of MESH transactions we need to only accept payments that have low risk for the vendors. Below are the payment methods we will launch the decentralized exchange with. Once you own MESH, you will have uncensored privacy over your digital identity, instant and secure transactions, and you reserve your share in an incredibly powerful decentralized autonomous organization that is focused on becoming the best global banking institution.**

Example: Buyer reviews vendor sell offer at price $10.00 per token, and they want 5 tokens. Total price is $50. They proceed according to their payment method.

Cash Deposit: 
The buyer receives deposit account to make the cash deposit. At any local bank branch they take $50 CASH and have the teller deposit into that account. Once the vendor receives funds, the transaction is complete and MESH is released to the buyers wallet. Research if we can hook into any bank accounts to help automate the release process for vendors. (Verify it was indeed cash deposit and that funds are in the account maybe use transaction description field. have them put unique code with "CASH DEPOSIT". This way the vendor can verify their unique transaction id via the transaction description field.)

Zelle: If buyers bank account supports zelle transactions they are in luck. This is likely the easiest way to buy MESH, sending directly from their bank to a vendor, releasing MESH can take minutes. Buyer receives zelle vendor account information, they login to their zelle supported bank account and initiate a transfer to the vendor. Once the vendor receives payment the MESH is released.
      -Zelle Supported Banks: Ally Bank, Bank of America, Bank of Hawaii, Bank of the West, BB&T, BECU, Capital One, Citi, Citizens Bank, Comerica Bank, ConnectOne Bank, Dollar Bank, Fifth Third Bank, FirstBank, First Tech Federal Credit Union, First Tennessee Bank, First National Bank, Frederick County Bank, Frost Bank, HomeStreet Bank, JP Morgan Chase, KeyBank, M&T Bank, MB Financial Bank, Morgan Stanley, PNC Bank, SchoolsFirst Federal Credit Union, Star One Credit Union, SunTrust Bank, TD Bank, USAA, U.S. Bank, and Wells Fargo.

### Operational requirements
These are about how to run the system. Logging, startup/shutdown controls, monitoring, resource consumption, back up, availability etc.etc.

### Technical requirements
These are about how the system is built. Which language, which OS, standards to be adhered to etc.

### Design limitations
User interface

## Phase 3 - Design
Products:
Dioramas, sketches, flow charts, site trees, HTML screen designs, prototypes, all user interface etc.

# Founders
### developers
-Summary
  -Total development team: $ 1280K/year
  -Managers

- Senior Decentralized Application (DApp) Developer $110k/year
  - Junior DApp Developer $70k/year
  - Junior DApp Developer $70k/year
  - Junior DApp Developer $70k/year
  
- Senior Blockchain Engineer $110k/year
  - Junior Blockchain Engineer $70k/year
  - Junior Blockchain Engineer $70k/year
  - Junior Blockchain Engineer $70k/year
  
- Ethereum (Solidity) Developer $110k/year
  - Junior Ethereum Developer $70k/year
  - Junior Ethereum Developer $70k/year
  - Junior Ethereum Developer $70k/year
 
- JavaScript Developer $110k/year
  - Junior JavaScript Developer $70k/year
  - Junior JavaScript Developer $70k/year
  - Junior JavaScript Developer $70k/year
### managers
- 
### founders
- Me
- CFO
- CTO


## Phase 4 - Development
- [x] Hire staff
- [ ] Genesis of MeshBank token
- [ ] Develop MeshBank's self regulating contracts
- [ ] Develop Meshbank's solidity


## Phase 5 - Implementation

## Phase 6 - MeshBank DAO Bounties
### MeshBank Website
- [ ] Github Website
- [ ] Create pages (get-mesh, merchants, network, resources, team, blog, evolution, lanaguage flag)
- [ ] Link domain meshbank.com -> https://meshbank.github.io/MeshBankWeb

### MeshBank Core
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
- [ ] Any user can create a proposal for 1000 USD
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

