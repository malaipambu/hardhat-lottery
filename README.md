# hardhat-lottery
Smart contract for Decentralised lottery where the winner is picked from a Oracle (ChainLink)  
Hardhat Lottery
License

A decentralized lottery game built using Hardhat and Solidity.

Table of Contents
About the Project
Built With
Getting Started
Prerequisites
Installation
Usage
License
Contact
About the Project
This project implements a decentralized lottery game using Hardhat and Solidity. Players can buy tickets for the lottery and at the end of the lottery period, a winner is randomly selected. The project uses Chainlink's VRF to ensure that the winner is selected fairly and at random.

Built With
Hardhat
Solidity
Chainlink VRF
OpenZeppelin Contracts
Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
Node.js
Hardhat (npm install --save-dev hardhat)
Hardhat Network (npm install --save-dev @nomiclabs/hardhat-network)
Hardhat Ethers (npm install --save-dev @nomiclabs/hardhat-ethers)
Metamask or another Ethereum wallet
Installation
Clone the repo

sh
Copy code
git clone https://github.com/malaipambu/hardhat-lottery.git
Install NPM packages

sh
Copy code
npm install
Create a .env file in the root directory and set the following environment variables:

sh
Copy code
INFURA_PROJECT_ID=<your Infura project ID>
PRIVATE_KEY=<your private key>
Usage
Deploying the smart contract
To deploy the smart contract, run the following command:

sh
Copy code
npx hardhat run --network <network-name> scripts/deploy.js
Replace <network-name> with the name of the network you want to deploy to (e.g. rinkeby, mainnet, etc.).

Running the tests
To run the tests, run the following command:

sh
Copy code
npx hardhat test
Starting the frontend
To start the frontend, run the following command:

sh
Copy code
npm run start
This will start the frontend on http://localhost:3000.

License
Distributed under the MIT License. See LICENSE for more information.

Contact
Malaipambu - malaipambu@example.com

Project Link: https://github.com/malaipambu/hardhat-lottery
