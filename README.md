# Module-21
Tokenomics

## Overview
In this module we set up a crowd sale of a new token. 

To implement this crowdsale, we use Solidity, through the Remix platform and Ganache, for a local blockchain. On our Ganache blockchain, we deploy three contracts in the two files :

1. KaseiCoin.sol - The mintable coin contract: This uses the ERC20, ERC20Detailed, ERC20Mintable standards from OpenZepplin
2. KaseiCoinCrowdsale.sol - This has the crowdsale contract and the Deployment contract. 


## Compile files 

### We start by compiling the contracts on the remix platform. Starting with the Coin: 

![compile_coin](./Evaluation%20Evidence/compile%20coin.png)

### Then we compile the KaseiCoin crowdsale contract. This is part of the larger KaseiCoinCrowdsale.sol file 

![compile_crowdsale](./Evaluation%20Evidence/compile%20crowd%20sale%20contract.png)

### Finally we compile the full KaseiCoinCrowdsale.sol file with deployment contract

![compile_crowdsale](./Evaluation%20Evidence/compile%20crowd%20sale%20deployer.png)


## Deployment 

### Once all the files have been compiled we start to deploy the contracts 

![deployment](./Evaluation%20Evidence/crowdsaleDeployer%20on%20test%20chain.png)

### This deployer gives us the location of the crowdsale


![buy](./Evaluation%20Evidence/token%20deployment.png)


## Buying Tokens

### once we have the crowdsale created, we can start buying tokens

![deployment](./Evaluation%20Evidence/crowdsale%20contract%20deployment.png)



### we can purchase tokens and approve the purchase using MetaMask



![buy](./Evaluation%20Evidence/token%20buy.png)