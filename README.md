# NFT Fair Mint template

[blog post: `Create a fair NFT mint on Ethereum with Solidity and NextJS`](https://blog.azerpas.com/posts/fair-mint-1)

Nowadays, gas war and bots makes minting a lot harder and expensive.

This project aims to solve theses problematics by adding a few extra step to the minting:
- avoid direct interaction with the smart contract by forcing the user to make a request to our backend
- reCaptcha solving on the web app backend
- whitelisting system

## Deploy the smart-contract
- Rename .env.example to .env `mv .env.example .env`
- Fill the variables with your data
- Deploy to ropsten network `npx hardhat run scripts/deploy.js --network ropsten --verbose`
- [*Optional*]: Verify the smart-contract `npx hardhat verify --network ropsten CONTRACT_ADDRESS`


⚠ NextJS side is still WIP
