# DEGEN TOKEN

This is a smart contract in the form of Token for Degen Gaming where several functionalities can be performed.

## Description

With the help of Smart Contract we can mint tokens, transfer from one address to another , burn them and also buy certian merchandise of the Degen Gaming over the Decentralised Network. The working of the contract is verified over the Avalanche Fuji Test Network. The verification is done on Snowtrace Testnet.

## Getting Started

### Installing

You can download the DegenToken.sol file and then compile it in Remix and then choose Environment as Injected Provider - Metamask and after that deploy the contract.

### Executing program

Steps to be followed inorder to run the contract seamlessly:

1. First we have to take test credit in the form of AVAX tokens in the Avalanche Fuji C-Chain.

   *Following steps are to be followed to create a Test Network in Metamask:*
   *Network Name*: Avalanche Fuji C-Chain
   *New RPC URL*: https://api.avax-test.network/ext/bc/C/rpc
   *ChainID*: 43113
   *Symbol*: AVAX
   *Explorer*: https://testnet.snowtrace.io/

2. Now we will go to core web app to request for Tokens and there we have to enter the coupon code that we will get after we join the Get Avax for free guild.
   
3. Now we can generate the secret code and the enter it in the coupon code address and after that we will enter the address of the Account in the Test net of Avalanche.
   
4. We will get 0.5 AVAX per day and after that we can use those to test our contract.

5. Now we will go back to Remix and then choose Environment as Injected Provider - Metamask and after that deploy the contract.

6. After that we will flatten the solidity file and then download the new file that is generated.

7. Now we wil copy the address of the deployed contract and then paste it in Snowtrace Testnet and then click on verify and publish contracts.

8. Then we will click on verify and then select chain as Fuji, enter the address of the new contract and then select the compiler version mentioned in the solidity file. Then, we will upload the flattened solidity file in it and click on verify.

9. After all is done we will now perform transaction in the contract and those will be logged in the Snowtrace.


## Working

After the Contract is deployed we can perform the following operations in it:

1. Minting Tokens: Creating new Tokens (can only be done by the ownwer).
2. Burning Tokens: Burn the Tokens from the whole Smart Contract.
3. RedeemTokens: Buy different merchandise by using Tokens.
4. Transfer Tokens: Transfer Token from a particular address to another address.
5. GetBalance: Check the balance of a particular address at a particular time.
6. StoreItems: Displays the list of all merchandise present in the Inventory having attributes: (Name, Cost, Stock).
7. Approve: Approve a certain address to be able to transact in the Smart Contract Environment.
8. GetUserInventory: Check the items purchased by a particular user based on their address.

## Help

Certain errors may occur while verification of the contract for taht we have to keep in mind that the solidity version specified in the contract, the version in the solidity compiler and one chosen while verifying should be same.

Apart from it we also have to flatten the file because the JSON format has to be adaptible as normal import statements are not compatible in the verification portal.

## Authors

Contributors names and contact info

Utkarsh Vinayak
[@Utkarsh]((https://www.linkedin.com/in/utkarsh-vinayak-304239212/))


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
