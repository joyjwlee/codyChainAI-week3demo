<h1 align="center">
  bearchainAI
</h1>
<h4 align="center">Week 3, intro to blockchain demo. <br/> Made for <a href="https://codeology.club" target="_blank">Berkeley Codeology</a> Spring 2023 by Trevor Trinh and Anna Chung.</h4>

Demo for a smart contract written in Solidity, deployed to the Goerli testnet using Hardhat.

## Installation

Install required packages with yarn

```bash
yarn install
```

Create .env file with API keys

```bash
ALCHEMY_GOERLI_API_KEY=<your api key>
ALCHEMY_GOERLI_URL=<your api url>
PRIVATE_KEY=<your metamask private key>
```

## Usage

```bash
npx hardhat run scripts/deploy.ts --network goerli
npx hardhat verify --network goerli <contract address>
```
