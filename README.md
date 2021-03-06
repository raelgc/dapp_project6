# Supply Chain Smart Contracts

Udacity Blockchain Developer Nanodegree, Project 6. Read more at: https://www.udacity.com/course/blockchain-developer-nanodegree--nd1309

## Description

This project is based in the Coffee Supply Chain example provided as sample.

## UML

### Activity

![Activity Diagram](uml/0-supply_chain_activity_diagram.png)

### Sequence

![Sequence Diagram](uml/1-supply_chain_sequence_diagram.png)

### State

![State Diagram](uml/2-supply_chain_state_diagram.png)

### Class (Data Model)

![Class Diagram](uml/3-supply_chain_class_diagram.png)

## Libraries

- Truffle version: `v5.1.63`
- Truffle Wallet Prodiver: `1.0.17`

## Requirements

If not installed, install `truffle` running the below command in a terminal:

    npm install -g truffle

## Install

Then install required packages, running a terminal:

    npm install

## Compile

In a terminal, start truffle console in dev mode:

    truffle dev

Then in the truffle console run:

    compile

## Test

In a terminal, start truffle console in dev mode:

    truffle dev

Then in the truffle console run:

    test

## Run Web app with local blockchain

[Metamask](https://metamask.io/) plugin is required.

In a terminal, first start truffle in dev mode:

    truffle dev

Then, in a second terminal window, start the web server:

    npm run dev

## Deploy to Rinkeby

First, create a `.secret` file in the project root folder with your MetaMask mnemonic.

Then, run in a terminal:

    truffle migrate --network rinkeby

## Rinkeby Contract

SupplyChain:
- Transaction ID: [`0xf35311abcdea63149ac02cdbc1d8c41b5ddb24672c32f30a2d220722b0622fd6`](https://rinkeby.etherscan.io/tx/0xf35311abcdea63149ac02cdbc1d8c41b5ddb24672c32f30a2d220722b0622fd6)
- Contract Address: [`0x54bB8f4dEb72C70B8C0068e555Ce48Cc3921c02E`](https://rinkeby.etherscan.io/address/0x54bB8f4dEb72C70B8C0068e555Ce48Cc3921c02E)
