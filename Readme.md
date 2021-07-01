# Multi-Blockchain Wallet in Python
![](https://github.com/kap108/19HW/blob/main/images/bitcoin.PNG)

## Background

Your new startup is focusing on building a portfolio management system that supports not only traditional assets
like gold, silver, stocks, etc, but crypto-assets as well! The problem is, there are so many coins out there! It's
a good thing you understand how HD wallets work, since you'll need to build out a system that can create them.

You're in a race to get to the market. There aren't as many tools available in Python for this sort of thing, yet.
Thankfully, you've found a command line tool, `hd-wallet-derive` that supports not only BIP32, BIP39, and BIP44, but
also supports non-standard derivation paths for the most popular wallets out there today! However, you need to integrate
the script into your backend with your dear old friend, Python.

Once you've integrated this "universal" wallet, you can begin to manage billions of addresses across 300+ coins, giving
you a serious edge against the competition.

In this assignment, however, you will only need to get 2 coins working: Ethereum and Bitcoin Testnet.
Ethereum keys are the same format on any network, so the Ethereum keys should work with your custom networks or testnets.




## Instructions

### Project setup

  ![Setup](https://github.com/kap108/19HW/blob/main/images/19HW.PNG)

### My directory tree:

  ![BTC](https://github.com/kap108/19HW/blob/main/images/btc.PNG)
  ![ETH](https://github.com/kap108/19HW/blob/main/images/eth.PNG)

### Setup constants

![Constants](https://github.com/kap108/19HW/blob/main/images/constants.PNG)

### Generate a Mnemonic
![Mnemonic](https://github.com/kap108/19HW/blob/main/images/mnemonic.PNG)


### Derive the wallet keys

![Wallet](https://github.com/kap108/19HW/blob/main/images/wallet.PNG)

### Linking the transaction signing libraries
![Code Screenshot](https://github.com/kap108/19HW/blob/main/images/code.PNG)



### Transactions

  - **Bitcoin Testnet transaction**

      ![BTC TestNet](Images/test-btc.png)

  - **Local PoA Ethereum transaction**

       ![ETH PoA](Images/test-eth.png)


