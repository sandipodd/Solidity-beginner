# Token Creation Smart Contract
This is a simple Ethereum smart contract written in Solidity that allows you to create and manage a basic token. The contract includes functionalities for minting and burning tokens, while maintaining balances and the total supply.

# Getting Started
To deploy and interact with this contract, follow the steps below:

# Prerequisites:
Make sure you have the necessary environment set up:

.Ethereum wallet (like MetaMask)
.Solidity development environment
.Deployment:

Deploy the smart contract on an Ethereum testnet or mainnet using a tool like Remix or Truffle.
Interacting with the Contract:

After deploying the contract, you can use Ethereum wallets or DApps to interact with the contract's functions.
Smart Contract Overview
Public Variables
tokenName: A string representing the name of the token.
tokenAbbrv: A string representing the abbreviation of the token.
totalSupply: A uint representing the total supply of the token.
Mapping Variable
balances: A mapping that associates Ethereum addresses with their token balances.
Functions
mint(address _address, uint _value): Mints new tokens and assigns them to the specified address.

Increases the total supply by _value.
Increases the balance of the specified _address by _value.
burn(address _address, uint _value): Burns tokens from the specified address.

Requires that the balance of _address is greater than or equal to _value.
Decreases the total supply by _value.
Decreases the balance of the specified _address by _value.
Usage Examples
Minting Tokens
To mint tokens and assign them to an address, call the mint function:

contractInstance.mint(recipientAddress, amountToMint);
## Author
 ### Sandip Thakur
## License
This project is licensed under the MIT License

 
