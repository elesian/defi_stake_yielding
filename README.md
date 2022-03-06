## Description

This is a basic stake-yielding app where one token (mock DAI token) is staked for another token (ficticious DApp token) in exchange for yield rewards (DApp token). This demo was written using modifiication to the source code provided by DApp university.

## Technologies

![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)


### Prerequisites

- Node 14.x (Node v14 Fermium LTS).
- Metamask https://metamask.io/
- Ganache https://trufflesuite.com/ganache/index.html
- Solidity Compiler (`npm install -g solc`).

### Instructions

1. Clone the repository locally using `git clone https://github.com/elesian/defi_stake_yielding.git`.
2. Run `npm install` to install dependencies.
3. Ensure your Solidity version is set to >=0.4.21. 
4. Ensure that Ganache is running locally on HTTP://127.0.0.1:7545.
5. Compile (`truffle compile`) and migrate (`truffle migrate --reset`) the smart contracts to the local Ganache blockchain.
6. Configure Metamask to use your local Ganache network: New RPC URL :HTTP://127.0.0.1:7545. Chain ID: 1337.
7. The test suit can be ran using `solidity tests`.
8. Run `npm run build` to start a local react app on port 3000.
9. Experiment with staking and withdrawing; you will need to approve/reject incoming requests to Metamask - refesh the page to see updated balances.


## Features
 
 - Stake tokens.
 - Issue tokens.
 - Unstake tokens.
 - Reward tokens.
 - Connects to local blockchain using Ganache.
 - Connects to Metamask.

## Project status

The core functionality of the project has been implemented. Future features would include:

- Extend the range of cryptocurrencies that could be used for staking.
- Increase yield returns proportional to stake investment.
- Set proportional yield rewards based on staking time.

## Licensing

The software is released under the terms of the ISC license. Further information is available <a href="https://opensource.org/licenses/ISC">here.</a>
