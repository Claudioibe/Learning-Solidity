

# Create Your Own ERC-20 Token


ERC-20 has emerged as technical standard used for all smart contracts on the Ethereum blockchain for token implementation.
Plenty of well-known digital currencies use the ERC-20 standard, including Maker (MKR), Augur (REP), Basic Attention Token (BAT), and OmiseGO (OMG).

### Prerequisite
To create your own ERC-20 standard token, you need to install/Access:
1. [MetaMask](https://metamask.io/)
2. ChainIDE


if you don't know how to set up development environment, you can follow our guidelines to install MetaMask and create your projects by clicking [here](https://chainide.gitbook.io/chainide-english/metamask-integration-with-different-blockchains/untitled)

### What is ERC-20?

One of the most significant Ethereum tokens is known as ERC-20. ERC-20 has emerged as the technical standard; it is used for all smart contracts on the Ethereum blockchain for token implementation and provides a list of rules that all Ethereum-based tokens must follow.
ERC-20 is similar, in some respects, to bitcoin, Litecoin, and any other cryptocurrency; ERC-20 tokens are blockchain-based assets that have value and can be sent and received. The primary difference is that instead of running on their own blockchain, ERC-20 tokens are issued on the Ethereum network. ERC stands for Ethereum Request for Comments. ERC20 defines 6 obligatory functions your smart contract should implement.
### Optional functions for ERC-20:
name

symbols

decimals



### Mandatory functions for the ERC-20 Token:
Total supply — the amount of tokens that exist at the moment

Balance of — shows the balance for the address

Transfer — sends a certain amount of tokens to the address

Transfer from — used for exchanging tokens among users who have these tokens

Approve — verifies that your the wallet address is eligible to send tokens to another user

Allowance — shows whether or not a user has a balance sufficient to send tokens to someone else

These 6 functions are recognized and identified by other smart contracts. In a nutshell, the
ERC20 token plays well with other smart contracts, and that’s why it is so popular.

![Mandatory Functions for ERC-20 Token](https://whitematrix-public-cn-north-1.s3.cn-north-1.amazonaws.com.cn/Erc20+showcase/1.png)
### Extra Function for Airdrop:
An extra function with name Airdrop has been included in the ERC-20 token that is used to get tokens every time you execute it, a specific amount of token will be added to the owner's account and to the total supply.

Regarding Interface with .html extension. Don't forget to change the ABI code of the smart contract in html file with your smart contract ABI code, and change the contract address with your contract address that you will get after deploying your smart contract on the blockchain.
The ABI code can be gotten from the compile panel, after successful compilation under the compile button you can see an option for ABI and BYTE CODE, you can copy the ABI code by clicking on the icon in front of ABI. 

![ABI](https://whitematrix-public-cn-north-1.s3.cn-north-1.amazonaws.com.cn/Erc20+showcase/2.png)

Once you have successful compiled the smart contract, now you can deploy it to a blockchain, we used Binance smart chain. After the successful deployment, a contract address will be assigned to a smart contract, by using the smart contract and ABI code, you can interact with your smart contract. Figures below show different methods to get an information about the deployed smart contract. 1st Figure shows the contract information from IDE output panel and the second figure shows the contract information from the BSC testnet. You can use get contract information by following any of these methods.

![](https://whitematrix-public-cn-north-1.s3.cn-north-1.amazonaws.com.cn/Erc20+showcase/3.png)
![](https://whitematrix-public-cn-north-1.s3.cn-north-1.amazonaws.com.cn/Erc20+showcase/4.png)

Once you have the contract address and the ABI, you can code using web3, a combination of  HTML,CSS, and JavaScript to interact with your deployed smart contract. We provide an example for you but need to change ABI and address to your own ERC20 token.

![](https://whitematrix-public-cn-north-1.s3.cn-north-1.amazonaws.com.cn/Erc20+showcase/5.png)

ChainIDE supports the HTML, .sol, .md, and all other file formats that are needed to create your dapps.

Once you click on the output view, you can see an interface according to your HTML file,
and you can interact through this with your deployed smart contract. 

![](https://whitematrix-public-cn-north-1.s3.cn-north-1.amazonaws.com.cn/Erc20+showcase/6.png)

As we can see the output of the airdrop.html file. In this file we interact with ERC-20 standard token. An extra function for getting airdrop coins is added to the ERC-20 token, and it will increase the token(you'll get tokens) each time you execute your Get Airdop function.

![](https://whitematrix-public-cn-north-1.s3.cn-north-1.amazonaws.com.cn/Erc20+showcase/7.png)

We hope this information helped you to create your own ERC-20 token. If you have any question, you can ask in our forum on the link given below.


Find us on
Forum: https://forum.chainide.com/

Twitter: https://twitter.com/MatrixDapp

Telegram: https://t.me/joinchat/Q48BNwB-f8RlZTJl

Facebook: https://www.facebook.com/tian.ling.9

Medium: https://medium.com/@matrixwhite-mgt

YouTube: click [here](https://www.youtube.com/channel/UCgvPUHayWfxAGiJCI2xOzNg)


