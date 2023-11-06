# SolidityBeginnerAssessment

This Solidity program is a simple program that is used to mint and burn created NFT.

## Description

This program contains simple functions that can be used to mint and burn NFTs of a user. A given number of Token {Name 'META' Abbreviated 'MTA'} can be minted for a user with a wallet address and a given number of Token can be burnt using the functions provided.

## Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension. Copy and paste the code given in file.js.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the contract from the dropdown menu, and then click on the "Deploy" button.



Once the contract is deployed, you can interact with it by calling the functions : 
mint : Required arguements: wallet address, amount of NFTs to mint
       Mints the given number of NFTs for the given wallet address

burn : Required arguements: wallet address, amount of NFTs to mint
       burns the given number of NFTs from the given wallet address


public variables :
tokenName   : shows token name
tokenAbbrv  : shows token abbreviation
totalSupply : shows the total amount of NFTs
balances    : required arguement : wallet addres
              shows the amount of NFTs in given wallet address


## Authors

Shiv  
