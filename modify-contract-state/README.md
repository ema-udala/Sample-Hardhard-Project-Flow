# This is a Suggested Hardhat Flow structure.

The structure includes the following important `files/folders`:

1. `/contracts`: All of your .sol files
2. `/scripts.js` files for running scripts
3. `/artifacts`: artifacts produced out of the contract compilation
4. `/test:.js` files for using testing libraries
5. `hardhat.config.js:` file with project configurations (very important!!!!)

## Want to get up and running with a Hardhat project? 🏇 Just follow this flow:

1. Open a terminal
2. Run cd Desktop, then create a new folder via `mkdir au-hardhat-practice`, then move into that newly-created folder by running `cd au-hardhat-practice`
3. Once you are in the `au-hardhat-practice folder`, in your terminal run `npm init -y` to initialize a `package.json`
4. Run `npm i hardhat`
5. Run `npm i dotenv`
6. Run `touch .env` in order to create a `.env` file at the root-level of your project, then populate it with important data and save
7. Run `npx hardhat` which will initialize a brand new Hardhat project
8. We recommend the following flow: Choose the current root `> YES to the .gitignore > YES` to install the sample project's dependencies
9. Add `require(‘dotenv’).config()` at the top of your `hardhat.config.js` file
10. Add networks flag to `hardhat.config.js`, add your Alchemy RPC URL under url and your testnet private key under accounts
11. Set up your scripts and contracts, then deploy in a flash! ⚡️
