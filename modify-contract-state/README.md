# This is a Suggested Hardhat Flow structure.

The structure includes the following important files/folders:

/contracts: All of your .sol files
/scripts: .js files for running scripts
/artifacts: artifacts produced out of the contract compilation
/test: .js files for using testing libraries
hardhat.config.js: file with project configurations (very important!!!!)

## Want to get up and running with a Hardhat project? 🏇 Just follow this flow:

Open a terminal
Run cd Desktop, then create a new folder via mkdir au-hardhat-practice, then move into that newly-created folder by running cd au-hardhat-practice
Once you are in the au-hardhat-practice folder, in your terminal run npm init -y to initialize a package.json
Run npm i hardhat
Run npm i dotenv
Run touch .env in order to create a .env file at the root-level of your project, then populate it with important data and save
Run npx hardhat which will initialize a brand new Hardhat project
We recommend the following flow: Choose the current root > YES to the .gitignore > YES to install the sample project's dependencies
Add require(‘dotenv’).config() at the top of your hardhat.config.js file
Add networks flag to hardhat.config.js, add your Alchemy RPC URL under url and your testnet private key under accounts
Set up your scripts and contracts, then deploy in a flash! ⚡️
