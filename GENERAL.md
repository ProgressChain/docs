# Stobox Progress Chain
> The system is aimed to optimize the expenses during operations with digitalised securities, reduction of ERC-20 tokens transfer fee, reduction of fees for other operations, with the possibility to confirm the operation in the Ethereum mainnet.

![This is an image](https://i.ibb.co/jT0ZKYR/4e09a460-9b3e-47b0-a1e3-7a84efac055b.png)
## Benefits

- Low transfer fee ($0.01)
- High transaction speed (3 seconds per confirmation)
- Enhanced security for operations with security tokens
- Possibility to publish transactions to L1
- Enterprise validators
- Automatic bridge

## System will include:

- Bridge between the Ethereum mainnet and our L2 system
- Decentralized applications for trading with usual tokens and securities
- Smart contract-based security system for management of smart contract deployers and operations with tokens
- Blockchain based KYC and AML system
- The possibility to publish transactions to the Ethereum mainnet with the 100x reduction of transaction fee. The fee will be paid with our network Ethereum tokens (L2ETH) and STBU
- Smart contracts in L1 network for publishing of transactions from L2 network

## Technically:

- Connector between L1 and L2 integrated directly into the blockchain node and the mining process
- In the node, in addition to the main transaction pool, there will be a pool including transactions to be published to the Ethereum mainnet
- Miner will receive rewards both in L2ETH and STBU, and will be able to transfer them to his wallet via the bridge
- Changed block structure to support the payments in 2 tokens in parallel, with specification of an average value of transaction publication to L1
- Proof of Stake 
## Network structure

![This is an image](https://stobox-images-chain.s3.eu-north-1.amazonaws.com/Network+structure.jpg)

## Block structure:

![This is an image](https://stobox-images-chain.s3.eu-north-1.amazonaws.com/Network+auto+bridge+ETH+to+STBU-1.jpg)

# L1 - L2 communication schemes
## General communication model:
![This is an image](https://stobox-images-chain.s3.eu-north-1.amazonaws.com/User+flow.jpg)

## Block confirmation on mainnet
![This is an image](https://stobox-images-chain.s3.eu-north-1.amazonaws.com/Block+confirmation+on+Mainnet.jpg)

## Tokenomics

- Blocks per day - 28800
- Block time - 3 seconds
- Average mining per day - 4200 STBU
- Initial supply - 50 million STBU
- Average L2 network fee 
  - For STBU transfer - 0.0001 STBU
  - For SRC20 (ERC20 analogue) - 0.0005 STBU
- Average price for publication of transaction to L1 - 0.000025 L2ETH
- L2 Gas price - 5 gwei

## User flow
![This is an image](https://stobox-images-chain.s3.eu-north-1.amazonaws.com/2.jpg)

## Network autobridge

![This is an image](https://stobox-images-chain.s3.eu-north-1.amazonaws.com/Network+auto+bridge+ETH+to+STBU.jpg)
![This is an image](https://stobox-images-chain.s3.eu-north-1.amazonaws.com/Network+auto+bridge+STBU+to+ETH.jpg)

## Permissions, access and control

- KYC contracts
  - User
  - Company
  - Nodes whitelist

![This is an image](https://stobox-images-chain.s3.eu-north-1.amazonaws.com/4.jpg)
  
- Roles
  - Auditor
  - Manager
  - User
  - Company

- Permissions
  - ERC20 transfers
  - Value based transfers
  - Contract deployment
  - View public info
  - View private info

- Auditors' contracts
  - Access to private data
  - Access to KYC info
  - De-anonimising of transactions

- Customer contracts
  - Tracking and de-anonimising of own company
  - Tracking and de-anonimising of companies he has permission for

- Black box and cloud version node configuration
  - Local node setup and its verification, with the possibility of all dApps connection to local network
  - Connection to whitelisted addresses, one-step setup from Stobox’s side


## Rules

- Smart contract deployment is available only to authorized accounts who passed KYC
- To confirm a transaction in L1, additionally, the fee in L2ETH will be paid, in addition to the L1 network fee
- To be a miner, account must have ETH in L1
- Every Stobox’s customer will have to deploy and own a node to ensure good level of decentralization
- Minimal stake for becoming a stake holder and miner - 100k STBU



