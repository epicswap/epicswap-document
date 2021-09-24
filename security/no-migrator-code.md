# No Migrator Code

**Security**

Because of what has been happening recently on the BSC, we took the following steps to ensure everyone’s safety. Deploy a 24 hour time lock contract.

Any changes made to the smart contract will be delayed by 24 hours.

We will implement this after we have introduced all our pools and we confirm the rewards are working as expected. This is 5x longer than all the other protocols. Any changes to the contracts such as adding a new pool will be communicated to the community.

We have removed the Migrator function from the Masterchef contract, now you won’t have to worry about your funds when farming.One of the key problems for DeFi projects based on the Binance Smart Chain has long been the so-called migrator code - a fragment of the smart contract code that allows the owner of the Masterchief contract to withdraw all funds from the contract at any time to any other address in the Binance Smart Chain, simply stealing all user funds.

Removing the Migrator function and implementing a Timelock of 24 hours removes entirely the risk of a rug pull as we want Fenix farmers to farm without risks.

Link: [https://github.com/pancakeswap/pancake-farm/blob/master/contracts/MasterChef.sol](https://github.com/pancakeswap/pancake-farm/blob/master/contracts/MasterChef.sol)​

![Migrator Code in Pancake Swap](https://gblobscdn.gitbook.com/assets%2F-MT5Nug3dG0o_JI3n0I1%2F-MT5NwcCl7o6fJMnYOAA%2F-MT5RDVsuHU_QnNz6fsT%2Fpancake%20code.png?alt=media&token=b7d5c1fc-9d44-423e-8a36-cb78460d4ed7)

