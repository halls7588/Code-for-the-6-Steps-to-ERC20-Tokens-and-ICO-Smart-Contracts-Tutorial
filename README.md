# 6 Steps to ERC20 Tokens and ICO Smart Contracts Tutorial Code

The following Code if for the tutorial: 
## 6 Steps to ERC20 Tokens and ICO Smart Contracts: In depth step by step
The is a simple ERC20 token with ICO functionality built into the contract. Once deployed, to begin the ICO the owner of the contract has to call the `startICO()` function. The contract will not automatically end the ICO, This must also be done by the owner of the contract by calling the `finalizeIco()` function. If all the Tokens that are part of the sale have been sold or if someone sends more Ether then remaining tokens, the contract will send any remaining tokens to the sender, calculate the difference in Ether and return the remaining balance. The rest will be sent to the contract owners address just like a regular token purchase. 

This code does not allow for discounts or bonuses, but any half competent developer should be able to quickly and easily add them in or any other functionality if desired. The contract will continue to function as a Simple ERC20 Token even during the ICO.

### NOTE: There is nothing built into this contract to prevent someone from buying tokens and listing them directly onto an exchange. If you would like to prevent this feel free to combine the token with the pauseable token code which can be found here:

[Pauseable Modifier](https://github.com/halls7588/ERC20_Token_Types/blob/master/Helpers/Modifiers/Pausable.sol)

[Pauseable Token code](https://github.com/halls7588/ERC20_Token_Types/blob/master/Tokens/PausableToken/pausableToken.sol)


### Prerequisites

Understanding of Solidity or proficient with a language like JavaScript, Swift, Java etc. Or just follow along with my tutoral at:

[6 Steps to ERC20 Tokens and ICO Smart Contracts Tutorial Code](https://medium.com/@halls7588/6-steps-to-erc20-tokens-and-ico-smart-contracts-e90523afafa1)

## Deployment

* Make sure that you have an ERC20 compatible Ethereum wallet. 

* To execute the token code: 
   - For MyEtherWallet; 
     1. Copy the token code and its dependencies. 
     2. Paste the token code into the remix online compiler. 
     3. Copy the EVM code and past into the MyEtherWallet execute smart contract. 
     4. Pay the gas price, enjoy your tokens.

## Contributing
Nothing in place. Feel free to message me if you want to contribute. [email](mailto:halls7588@gmail.com)

## Issues
If you find a bug or issue in the code, Please feel free to raise an Issue and i will get to it in a timely manner. No spacific template is required, please be as detailed as possible as it will make tracking the issue down that much easier. [Raise an Issue](https://github.com/halls7588/Code-for-the-6-Steps-to-ERC20-Tokens-and-ICO-Smart-Contracts-Tutorial/issues)

## Additional Help or General Quiestions
Feel free to message me for questions or help with the token or develoment of a new one. Thouhgh I prefer you message me on [Linkedin](https://www.linkedin.com/in/stephen-hall-3749b062/)

## Authors

* **Stephen Hall** - *Initial work* - [halls7588](https://github.com/halls7588)

See also the list of [contributors](https://github.com/halls7588/Code-for-the-6-Steps-to-ERC20-Tokens-and-ICO-Smart-Contracts-Tutorial/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


### Donations Excepted
Send to:

**Bitcoin:** 3FjpxkdTSrPz6KYk1oWf3yTFiZgei8eQ3X

**Ethereum:** 0xa961d6886359df290B49d752405CbB7ac0adB123

**Monero:** 43gnpSr6mruj2yxQuQaM4J8xWqcy3ogGN2YPzSZQry8EcZEjpkCE1ioTePGmaJRXBaVZetTegMNL22riuHFmcTcNJCZ3v88
