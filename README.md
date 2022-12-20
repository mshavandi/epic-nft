# Epic NFT contract

This project demonstrates a basic NFT contract for creating epic NFTs on Ethereum blockchain.

This contract will create 3 different SVG shapes with various random colors.
Every address will have the chance to mint their own NFTs but it will have a maximum amount that will be specified by the web3 app that calls the `makeAnEpicNFT` function.
A cooldown timer of 1 minute is set after each minting process.

## How to run

To run the following scripts, you will need to create two files:

- `hardhat.config.js`: For specifying the hardhat config
- `.env`: For specifying the environmental variables needed

Try running some of the following tasks:

```shell
# to get test accounts
npx hardhat accounts

# to run and test locally:
node scripts/run.js

# to deploy on the blockchain
node scripts/deploy.js
```
