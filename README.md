
# Decentralized Star Notary

Udacity Blockchain Developer Nanodegree Program - Project 2 - Decentralized Star Notary Project

Build CryptoStar Dapp on Ethereum


# Write Up

1) ERC-721 Token Name: StarNotary
2) ERC-721 Token Symbol: TWD
3) Version of the Truffle used: v5.1.61
4) Version of OpenZeppelin used: v3.3.0
5) Version of Node.js used: v14.15.1


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Install Node.js

Install truffle: ```$ npm install -g truffle```

Install web3: ```$ npm install web3```

Install OpenZeppelin: ```$ npm install @openzeppelin/contracts```

Install MataMask

### Installing

A step by step series of examples that tell you how to get a development env running

1. Clone this project
2. Move to project directory, open terminal run ```$ npm install```

## Deployment

Using Truffle to deploy Smart Contract on local:
1. Start Truffle development: ```$ truffle develop```
2. Compile: ```$ truffle(develop)> compile```
3. Deploy: ```$ truffle(develop)> migrate```

Run DApp on local:
```$ npm run dev```


## Running the tests

Run the automated tests for Smart Contract:
1. Start Truffle development: ```$ truffle develop```
2. Compile: ```$ truffle(develop)> compile```
3. Deploy: ```$ truffle(develop)> migrate``` (default network) or ```$ truffle(develop)> migrate --network {{specific_network_in_truffle_config_network}}```
4. Test: ```$ truffle(develop)> test```

