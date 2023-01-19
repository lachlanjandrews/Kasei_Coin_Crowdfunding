# Kasei Coin Crowdfunding
Module 21 Challenge

In this challenge, we were asked to create a token for Mars called Kasei Coin (Token) and then a crowdsale for that token. Using Remix, MetaMask and Ganache, I was able to complete this, along with double checking that the contract had been successfully deployed and the transactions were completed by checking Ganache.

---

## Technologies

This repository uses the following project libraries and dependencies:
* [Remix](remix.ethereum.org) - which can be accessed online with a free account or any other programs that can run solidity.
* [Streamlit](https://streamlit.io/) - a Python library that turns Python scripts into shareable web apps.
* [MetaMask](https://metamask.io/) - a crypto wallet extension that allows transactions and the creation of smart contracts.
* [Ganache](https://trufflesuite.com/ganache/) - a program that allows for the use of test wallets and blockchain tracking.

--- 

### **Run instructions:**
To run this analysis, simply clone the repository or download the files. Open Remix and run the following files: 
```python
KaseiCoinCrowdsale.sol
```
```python
KaseiCoin.sol
```
___

## Results

After completing the code, the first step was to make sure the code compiled correctly.

![KTcompiler](/Screenshots/KTcompiler.PNG)
![KCCcompiler](/Screenshots/KCCcompiler.PNG)

Then the deployment of the crowdsale was required. The following was input into the deployment requirements:
* KaseiCoin (NAME)
* KAS (SYMBOL)
* Any valid address (WALLET)

![Contract_Deployment](/Screenshots/contract_deployment.PNG)

This was then confirmed on Ganache as well.

![Ganache_Confirmation](/Screenshots/contract_confirm.PNG)

Next, we inserted the contract addresses and loaded the Crowdsale and Token contracts.

![Token_Link](/Screenshots/token_link.PNG)
![Crowdsale_Link](/Screenshots/crowdsale_link.PNG)

The wallet address linked to my MetaMask was then put as the initial buying address, purchasing 5 Ether worth of Kasei Tokens.

![Initial_Buy](/Screenshots/initial_buy.PNG)

This was also confirmed on Ganache.

![Final_Confirmation](/Screenshots/ganache_confirmation.PNG)

To make sure that all of the contracts were working together and correctly, I double checked the Wei raised, the Kasei Token total supply and the Kasei Token balance of my MetaMask account.

![wei_generated](/Screenshots/wei_generated.PNG)
![balance_total_supply](/Screenshots/balance&totalsupply.PNG)

---

## Disclaimer

This project used test net accounts and cryptocurrency for practise purposes.

---

## Contributors

This project was created as part of the module 18 challenge in the Monash University Fintech Bootcamp 2022 Program by:

Lachlan Andrews

Email: swerdna14@gmail.com

LinkedIn: [lachlanjandrews](https://www.linkedin.com/in/lachlanjandrews/)
