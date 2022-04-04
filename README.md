# 🪂 DAO Drops 

## 🎯 Airdrop tool for DAOs
*Airdrops to verified unqiue & enriched user accounts*    

This tool is a subset of the amaDAO platform which enriches wallet account data with users' onchain and offchain activities. Where through onboarding on the amaDAO app, a users' skills and interests are stored onchain against their wallet address in our smart contract. 
\
DAO Drops has been developed in parallel with the (currently) closed source amaDAO.io platform.\
\
This repository contains simplified & refactored code for demonstration purposes:
- Subset of DAO Dashboard dApp [https://github.com/oespn/daodrops-dash-telos-sub (Repo here)]
- Smart Contracts 
- POC User facing mobile dApp (iOS) [https://github.com/oespn/daodrops (Repo here)].

### Functionality

The Mobile dApp demonstrates the use-case of a user who has accepted and completed a whitelist step.  Their wallet address and UUID pair is stored to the Smart Contract for the Whitelist related to the Offer from the DAO.  NOTE: Attepting to register additional wallets for the same user/device will be rejected.
DAOs will use the full amaDAO dApp to notity the community of bounties, offers and record their completion onchain. 

### DAO Dashboard

The DAO Dashboard accepts CSV files of account addresses (from whitelist export eg: ethersan)  
Target Lists can be built upon to create an Airdrop for a new Token issuance.    
We've included a demo account with sample data linked to amaDAO (50 top contributors in over 100 DAOs)
Performing an Airdrop will generate an ERC-20 token on the Telos EVM.
\
  

*Submission for Telos Spark hackathon April 3rd 2022.*
Note: repos separated (see links) to fix issue with Vercel handling multiple projects.
