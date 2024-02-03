**README**

**Solidity Smart Contracts for ERC20 Token and Vault**

This repository contains Solidity smart contracts for an ERC20 token and a vault designed to handle deposits and withdrawals of the ERC20 token.

### Contracts

1. **ERC20.sol**: This contract implements the ERC20 token standard. It provides basic functionalities such as transferring tokens, approving spender addresses to transfer tokens on behalf of token owners, and burning/minting tokens. 

2. **Vault.sol**: The vault contract serves as a secure storage facility for the ERC20 tokens. Users can deposit tokens into the vault, which will mint shares representing their ownership. These shares can later be redeemed for tokens upon withdrawal. The vault ensures that the total supply of shares accurately represents the total deposited tokens.

### Deployment

To deploy these contracts, you can follow these steps:

1. Deploy ERC20.sol by providing necessary parameters such as the token name, symbol, and initial supply.
2. Deploy Vault.sol, passing the address of the ERC20 token contract to its constructor.

### Usage

Once deployed, users can interact with the contracts as follows:

- **ERC20 Token**: Users can transfer tokens, approve spender addresses, and burn/mint tokens as needed.

- **Vault**: Users can deposit tokens into the vault, which will mint shares for them. These shares can be later redeemed for tokens upon withdrawal. The vault ensures that the total supply of shares accurately represents the total deposited tokens.

### Security Considerations

While these contracts provide basic functionalities for token management and secure storage, it's important to conduct thorough testing and auditing before deploying them in a production environment. Additionally, ensure proper access control mechanisms are in place to prevent unauthorized access to sensitive functionalities.

### License

These contracts are licensed under the MIT License. See the individual contract files for more details.

## Author

Pranav Chaitanya 

craj0314@gmail.com
