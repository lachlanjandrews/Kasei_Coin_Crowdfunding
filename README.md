# Kasei Coin Crowdfunding
Module 21 Challenge

In this challenge, we were asked to create a joint savings account for two accounts. We then had to deposit ETHER into the contract and then withdraw it back out to the respective wallets.

---

## Technologies

This repository uses the following project libraries and dependencies:
* [Remix](remix.ethereum.org), which can be accessed online with a free account or any other programs that can run solidity.
* [Streamlit](https://streamlit.io/) - a Python library that turns Python scripts into shareable web apps

--- 

### **Run instructions:**
To run this analysis, simply clone the repository or download the files. Open Remix and run the following file: 
```python
KaseiCoinCrowdsale.sol
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

The second deposit was 10 ether as wei.

![Transaction2](/Screenshots/transaction2.PNG)

The third deposit was 5 ether.

![Transaction3](/Screenshots/transaction3.PNG)

We were then asked to make some withdrawals, one into each of the 2 selected accounts. The first withdrawal was 5 ether into accountOne.

![Withdrawal1](/Screenshots/withdraw1.PNG)

The second withdrawal was 10 ether into accountTwo.

![Withdrawal2](/Screenshots/withdraw2.PNG)

---

## Disclaimer

This project used test net accounts and cryptocurrency for practise purposes.

---

## Contributors

This project was created as part of the module 18 challenge in the Monash University Fintech Bootcamp 2022 Program by:

Lachlan Andrews

Email: swerdna14@gmail.com

LinkedIn: [lachlanjandrews](https://www.linkedin.com/in/lachlanjandrews/)
