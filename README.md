
# NFT Minting

This code provides a basic example of how to mint non-fungible tokens (NFTs) in Candence on the Flow blockchain. This code can be used as a starting point for creating your own NFTs on the Flow network.


## Description

This program is a simple contract written in Cadence. The contract allows you to mint NFTs.First it creates a collection in the account address given by the owner.Then it takes the input from the user like address,user name,lucky number,fav food etc. and it mints an NFT.
 

## Requirements

To run this code, you will need the following:

1)A Flow account with sufficient FLOW tokens to pay for         the              transaction fees

2)The Flow CLI tool installed on your machine

3)A code editor or IDE for modifying the code
## Usage

To use this code to mint your own NFTs on the Flow blockchain, follow these steps:

1)Clone this repository to your local machine.

2)Open the nft-mint.cdc file in your code editor or IDE.

3)Modify the metadata dictionary to include the metadata for your NFTs, such as the name, description, and image URL.

4)Modify the mintNFT function to specify the total number of NFTs you want to mint and the price of each NFT.

5)Save the nft-mint.cdc file.

6)Open a terminal window and navigate to the directory where you cloned this repository.

7)Run the following command to deploy the contract to the Flow blockchain:
flow project deploy

8)Once the contract is deployed, run the following command to mint your NFTs:
flow transactions send ./transactions/mintNFT.cdc

9)Enter your Flow account credentials when prompted.

10)Wait for the transaction to be confirmed on the Flow blockchain.
## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.


## Acknowledgements

This code was inspired by the Flow NFT Tutorial on the Flow documentation website. Special thanks to the Flow team for creating such a powerful and developer-friendly blockchain platform!
