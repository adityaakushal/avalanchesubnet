# Avalanche Subnet

In this project , I have used Avalanche's subnet to create and deploy smart contract to the local subnet with remix IDE.

## Description

In my project, I have deployed the smart contract which is a game - 'DF Game' and symbol as 'DFG' , we have two contracts here- ERC20 and Vault . In ERC20 contract , we have added two custom functions - 'startgame' and 'gameover' which when called returns if game has started or ended . The other functions follows the ERC20 standard which includes mint, burn, approve, allowance, transfer, etc. This contract is deployed to the local subnet that I created using Avalanche CLI and connected it to my metamask so i can deploy easily using remix .
## Getting Started

### Executing program

Firstly, you need to install and export the Avalanche CLI path , follow the instructions in the readme file to install, export, create a subnet and deploy it:

```
https://github.com/ava-labs/avalanche-cli
```
After you deploy , you get the metamask configurations that you entered while subnet creation -

* Network name: net
* ChainID: 999
* Token Symbol: ADK
* RPC URL
* Private Key ( to import account with test tokens)

Then you can change environment to 'Injected Provider' and connect your metamask to deploy the contract.

## Authors

Aditya K

@adityaaakushal@gmail.com

## License

This project is licensed under the MIT License
