# KaseiCoin Martian Token Crowdsale

![alt=""](Images/application-image.png)

***Module 21 Challenge - Using Solidity smart contracts to create a crowdsale to fund the Martian Token ~ KaseiCoin***

## Table of Contents
* [Background](#background)
* [Requirements](#requirements)
* [Smart Contracts](#smart_contracts)
* [Evidence](#evidence)
* [Source Code](#source_code)


## Background

We are thrilled to present to you a groundbreaking innovation in interplanetary finance: KaseiCoin. Our journey to Mars represents not just a leap for mankind but also a giant stride for financial systems. As we establish the first human colony on the Red Planet, we bring forth KaseiCoin – a currency designed to thrive in the Martian economy.

KaseiCoin, deriving its name from the Japanese word for Mars, is a testament to our global collaboration. It is a fungible token, fully compliant with the ERC-20 standard, ensuring seamless integration with the existing blockchain infrastructure.

We are initiating a crowdsale, a unique opportunity for future Martians to be part of this historic venture by converting their Earth currencies into KaseiCoin. This isn’t just a new cryptocurrency; it’s the dawn of a new era for commerce across planets. Join us as we make history.

## Requirements
* Solidity ~ version ^0.5.0
* Remix IDE
* MetaMask
* Ganache
* OpenZepplin

## Smart Contracts
Using the Remix IDE and Solidity we wrote 3 smart contracts to create and run not only the KaseiCoin Token but also the Crowdsale to fund the new venture


- ### KaseiCoin Token Creation Smart Contract
    
![KaseiCoin Token Contract](/Evaluation_Evidence/Kai_token_contract.png)

- ### KaseiCoin Crowdsale Contract

![KaseiCoin Crowdsale Contract](/Evaluation_Evidence/Crowdsale_contract.png)

- ### KaseiCoin Crowdsale Deployer Contract

![KaseiCoin Crowdsale Deployer Contract](/Evaluation_Evidence/KaseiCoinCrowdsaleDeployer.png)

## Evidence
- Proof in Ganache that the Crowdsale Contract was Deployed
![Ganache transaction contract creation](/Evaluation_Evidence/ganache_contract_deployed.png)

- Proof in Ganache of the buy of 1111 tokens
![Ganache transaction buy](/Evaluation_Evidence/ganache_buy.png)

- Demo with deploying and interacting with the crowdsale contract. Creating the contract and a couple different purchases of KaseiCoin from different wallets. All Videos and screenshots of operational dApp in the folder labeled Evaluation Evidence. There is also a short video titled DEMO2 with more proof of deployment. 

[Video of deploy and buying of assests](/Evaluation_Evidence/Deployed_contract_and_buys.mp4)

[video](/Evaluation_Evidence/DEMO2.mp4)

## Source Code

- [KaseiCoin Token Contract](KaseiCoin.sol)
- [KaseiCoin Crowdsale Contract](KaseiCoinCrowdsaleOptional.sol)

