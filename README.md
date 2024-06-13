# Solidity Token Contract

This is a simple Solidity smart contract implementing a token with basic functionalities such as minting and burning tokens.

## Requirements

1. The contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. The contract will have a mapping of addresses to balances (address => uint)
3.It will have a mint function that takes two parameters: an address and a value. 
   The function then increases the total supply by that number and increases the balance 
   of the “sender” address by that amount
4.  The contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
   It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
   and from the balance of the “sender”.
5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
   to the amount that is supposed to be burned.

## Usage

1. Deploy the `MyToken` contract to the Ethereum blockchain.
2. Interact with the contract by calling the `mint` and `burn` functions to create and destroy tokens, respectively.
3. Use the public variables `tokenName`, `tokenAbbrev`, `totalSupply`, and the mapping `balances` to retrieve information about the token and account balances.

## Contract Details

- `tokenName`: The name of the token (e.g., "Solidity").
- `tokenAbbrev`: The abbreviation or symbol of the token (e.g., "SOL").
- `totalSupply`: The total supply of the token.
- `balances`: A mapping of addresses to token balances.

## License

This project is licensed under the MIT License. See the LICENSE.md file for details.
