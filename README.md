# MyToken Smart Contract


This is a simple Solidity smart contract that creates a token called "WATER" with the abbreviation "H20". It has a total supply that starts at 0, and uses a mapping of addresses to balances to keep track of how many tokens each address holds.

The contract includes two functions: mint and burn.


## Description

This program is a simple contract written in remix. The contract allows you to add and sub values to the account address.
 

## Requirements

1)The contract has public variables to store the details about the coin: tokenName, tokenAbbrv, and totalSupply.

2)The contract uses a mapping of addresses to balances: mapping(address => uint) public balances.

3)The mint function increases the total supply by the given amount and increases the balance of the given address by that amount.

4)The burn function deducts the given amount from the total supply and from the balance of the given address.

5)The burn function includes conditionals to make sure the balance of the given address is greater than or equal to the amount that is supposed to be burned.
## Usage

To use this contract, you can deploy it to a Ethereum network (such as the mainnet, Ropsten, or a local testnet) using a Solidity compiler and an Ethereum client (such as Remix or Truffle). Then you can interact with the contract using a web3 provider (such as MetaMask) or a smart contract wallet (such as Gnosis Safe).
## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.


## Acknowledgements

I would like to acknowledge the Remix Tutorials and the Remix website for providing helpful resources and tools for learning and developing smart contracts on the Ethereum network. Their tutorials and user-friendly interface have been instrumental in my understanding and development of Solidity smart contracts. Thank you for your valuable contributions to the blockchain community!
