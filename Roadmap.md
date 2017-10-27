# MeshBank Software Roadmap
This document outlines the development plan from a high level and will be updated as progress is made towards beta release. 

**Everything contained in this document is in draft form and subject to change at any time and provided for information purposes only.  MeshBank does not gaurantee the accuracy of the information contained in this roadmap and the information is provided "as is" with no representations or warranties, express or implied.**

## Phase 1 - Initiation
### Why this project?
MeshBank aims to create the most powerful infrastructure for decentralized banking applications.  We are a blockchain based community that is self governed by MeshDAO, the decentralized autonomous banking organization. Anyone can create proposals that get reviewed by investors monthly, investors vote on if MeshDAO should, or should not fund the proposal.  Investors have weighted votes based on the number of eligible validators. 
### Is it feasible?
Yes. 
### Who are possible partners in the project?
Banking institutions, credit card processors, financial companies, ecommerce platforms
### What should the results be?
0. MeshBank is the most powerful infrastructure in the world.
1. MeshDAO is a group of investors that fairly control shares of the company. Those shares can be used to vote on decisions that MeshDAO makes.  that that power the business. 
2. MeshWallet allows transacting instantly, privately, and securely
3. MeshCore can be installed with one command on a clean server. MeshBank has staff and developers that are specifically trained to help customers setup MeshCore properly. If we setup the account, we manage that server indefinately for the client. 
3. Desktop application that allows users to send, receive, and invest in MeshBank's infrastructure (instant transactions, private "zk-snarks protocol", secure)
4. MeshDEX (Late 2018)
   - Support various easily accessible payment methods: Cash deposits, Zelle (Bank transfers with supported banks)
   - Exchange various currencies (MESH/BTC, MESH/ETH, MESH/LTC, MESH/USD)

## Phase 2 - Project Requirements
### Functional requirements
1. [MeshWallet](#meshwallet-application)
2. [MeshCore](#meshcore-application-runs-on-validator-nodes)
3. [MeshDAO](#meshdao-decentralized-autonomous-organization)
4. [MeshDEX](#meshdex-decentralized-exchange) 

#### MeshWallet Application
- create account, import account
- send, receive, transactions (history), validators (add, delete, monitor)

#### MeshCore Application (runs on validator nodes)
- This is the main application that runs on MeshBank validators. Validator uptime, connection, and payouts can be monitored from any wallet. 

#### MeshDAO (Decentralized Autonomous Organization)
- To run a validator, you must hold a preset stake of tokens. Each validator that is online is allowed to vote on various items proposed to the DAO. Every block produces 12.5 new mesh tokens. 90% of the Tokens are dispursed to all qualified validators (Online > 24 hours, transacting fairly), the other 10% is awarded to the DAO. Validator owners are able to create and vote on proposals made in the DAO. A cost of 5 MESH has been assigned to assure meaningful quality proposals are presented to the DAO. Since all validator owners have significant stake held in MeshBank, it is in their best interest to vote for proposals that insure the success of the organization. 

#### MeshDEX (Decentralized Exchange)
- MeshDEX can be used by anyone in the world to buy or sell MESH easily and safetly. 

Buy MESH: Buyer enters MeshDEX and selects "Buy MESH". Buyer then can browse current exchange rates, and proceed with purchasing MESH. After accepting the sellers offer they need to proceed with one of the payment methods below.

Sell MESH: Seller enters MeshDEX and selects "Sell MESH". Seller sets a sell price and selects the payment method(s) they will accept. (Offer a floating sell price off a few exchanges.) Once a buyer takes the offer, they will need to complete the payment and signal that this is complete, seller verifies payment, they release MESH to the buyer.

**Due to the irreversable design of MESH transactions we need to only accept payments that have low risk for the vendors. Below are the payment methods we will launch the decentralized exchange with. Once you own MESH, you will have uncensored privacy over your digital identity, instant and secure transactions, and you reserve your share in the incredibly powerful MeshDAO community that is focused on becoming the best global banking institution.**

Example: Buyer reviews vendor sell offer at price $10.00 per token, and they want 5 tokens.  Total price is $50.  They proceed according to their payment method.

Cash Deposit: 
The buyer receives deposit account to make the cash deposit.  At any local bank branch they take $50 CASH and have the teller deposit into that account.  Once the vendor receives funds, the transaction is complete and MESH is released to the buyers wallet. Research if we can hook into any bank accounts to help automate the release process for vendors.  (Verify it was indeed cash deposit and that funds are in the account maybe use transaction description field. have them put unique code with "CASH DEPOSIT".  This way the vendor can verify their unique transaction id via the transaction description field.)

Zelle: If buyers bank account supports zelle transactions they are in luck. This is likely the easiest way to buy MESH, sending directly from their bank to a vendor, releasing MESH can take minutes.  Buyer receives zelle vendor account information, they login to their zelle supported bank account and initiate a transfer to the vendor. Once the vendor receives payment the MESH is released.
      -Zelle Supported Banks: Ally Bank, Bank of America, Bank of Hawaii, Bank of the West, BB&T, BECU, Capital One, Citi, Citizens Bank, Comerica Bank, ConnectOne Bank, Dollar Bank, Fifth Third Bank, FirstBank, First Tech Federal Credit Union, First Tennessee Bank, First National Bank, Frederick County Bank, Frost Bank, HomeStreet Bank, JP Morgan Chase, KeyBank, M&T Bank, MB Financial Bank, Morgan Stanley, PNC Bank, SchoolsFirst Federal Credit Union, Star One Credit Union, SunTrust Bank, TD Bank, USAA, U.S. Bank, and Wells Fargo.

### Operational requirements
These are about how to run the system. Logging, startup/shutdown controls, monitoring, resource consumption, back up, availability etc.etc.

  1. [MeshWallet](#)
   - Application run on Mac, Linux, and Windows (Late 2017)
     - download instructions (hash verification)
     - install instructions (all platforms)
     - 
   - IOS application (Late 2018)
  2. [MeshCore](#)
   - Application runs on fresh Ubuntu X install (Late 2017)
  3. [MeshDAO](#)
   - Dapp (Early 2018)
  4. [MeshDEX](#)
   - Application run on Mac, Linux, and Windows (Late 2018)
   - IOS application (Late 2018)

### Technical requirements
These are about how the system is built. Which language, which OS, standards to be adhered to etc.

### Design limitations
User interface

## Phase 3 - Design
Products:
Dioramas, sketches, flow charts, site trees, HTML screen designs, prototypes, all user interface etc.

![DAO Voting Application](/images/dao-voting.png)
Format: ![Alt Text](url)

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

