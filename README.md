## Deployed Contracts on mumbai
* Lokians (LOK) 100.000 https://mumbai.polygonscan.com/token/0x4D44e499CE3eE0C5Fb28777a1FC2266E7607b942
* Lokian Items ERC1155 https://mumbai.polygonscan.com/address/0xB72866C1CA1BB3035d02567A09C58657f73968C2
* CryptoMons https://mumbai.polygonscan.com/address/0xB7B0D4d98902a764a44DA5Ce3967499F55F7D015
* 0x4D44e499CE3eE0C5Fb28777a1FC2266E7607b942 erc20
* 0xB72866C1CA1BB3035d02567A09C58657f73968C2 items
* 0xB7B0D4d98902a764a44DA5Ce3967499F55F7D015 contract

# Lokian.eth: A trading card game dapp featuring NFT monsters (Turing Monsters), share, fight and breed in solidity blockchains (L2 Boba Network).

 <img src="./screenshots/project.eth.ss2.png" alt="" width="1000em" height="500em">

***

This project was developed as a module coursework.

Thanks to Stamatis Kourkotas from

**Imperial College London:** MSc in Computing (Software Engineering)<br />
**Module:** Principless of Distributed Ledgers<br />
**Project Description:** Found in included [report](./report.pdf)<br />

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Steps for deployment and use of our DApp

- Firstly, deploy our smart contract found in src/project.eth.sol. We tested this locally on a private blockchain using [Ganache](https://www.trufflesuite.com/ganache)
- In the main file of our user interface src/App.tsx specify the address where you deployed the contract in the constant CONTRACT_ADDRESS.
- Install the [metamask](https://metamask.io/) extension on your browser to handle your provate blockchain account. The project has been tested with the Chrome and Mozilla browsers.
- In the project directory run:

    **`npm install`** This installs all the necessary dependencies to build our application
    
    **`npm start`** This runs the app in development mode.<br />

- Open [http://localhost:3000](http://localhost:3000) to view it in the browser. You can see all the Creatures owned by the current metamask account and play the game.

## Remaining Tasks

Finished
- 

Ongoing
- Get Turing Monster nft data from rinkeby boba, (needs boba token, need to deploy tumo nft contract)
- Remove shop and marketplace contract functions coz nft would be transacted outside
- Modify fight/duel and breed
- Test and deploy
- Improve, simplify, polish graphics





