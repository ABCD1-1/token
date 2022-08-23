# This is a small project that deploys a token ERC20 on your local machine

A React (draft) application is included in this project to observe the amount of cryptos in the local network (localhost 8545)

Steps:

0.a In the CLI, run the following command to start a local node:
npx hardhat compile

0.b In the CLI, run the following command to start a local node:
npx hardhat node

0.c Copy the private key of the Account 0

0.d Get connected on MetaMask, select the localhost 8545 network

0.e Click on import an account and paste the private key copied previously


1. In a new CLI, run the following command:
npx hardhat run .\scripts\deploy.js --network localhost

2. Copy the deployed address

3. Get connected on MetaMask, select the localhost 8545 network

4. Click on 'Import tokens'

5. Paste the tokan deployed address copied previously, and import the tokens

6. In the file App.js, at line 6, assign the address where your Token is deployed the const tokenAddress

7. In a new CLI, run the following command:
npm start

