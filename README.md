# Getting Started with Gelato Public Testnets

Internal Testing Contracts used for relay services.



## Funding
You would need Sepolia test Eth. Please go to one of these faucets and grab some eth:

- [Alchemy Faucet](https://sepoliafaucet.com/)
- [Infura Faucet](https://www.infura.io/faucet/sepolia)
- [pow Faucet](https://sepolia-faucet.pk910.de/)

Once you have Sepolia Eth you will have to [bridge](https://bridge.zkatana.gelato.digital/) to zKatana eth. Please login in on Sepolia chain and brigde the required amount, it will take 8-10 minuts to confirm.
 
1) Verify contracts


yarn add --dev @nomiclabs/hardhat-etherscan

import "@nomiclabs/hardhat-etherscan";