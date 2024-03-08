# MyToken
This Solidity program is a simple program that demonstrates how to create your own token (like an NFT token).

## Description
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract contains various variables such as token name, its abbreviation and the current supply of tokens. It also contains a mapping of address to balances for each user that mint this token for their own use. It contains functions to mint and burn tokens for each user at their own address.

## Getting Started
### Executing program
Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Now copy the contents of MyToken.sol (from this repository) to the file opened in the Remix editor.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.7" (or another compatible version), and then click on the "Compile HelloWorld.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "HelloWorld" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the mint() and burn() functions, and also see the name, abbreviation and total supply of the tokens using the buttons provided in the sidebar.

> Note: You will have to enter values in the mint() and burn() functions in order for it to work. First argument needed is the sender's address and the second argument is the value you want to mint or burn

## Authors
Paras Shah\
[@Paras-Shah-sudo](https://github.com/Paras-Shah-sudo)

## License
This project is licensed under the MIT License - see the LICENSE.md file for details
