# Challenge19


##Goal

Integrate the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.


## Overview of the project 

Complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, I will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.


This Challenge contains two Python files:
1. Fintech_finder.py  contains the code associated with the web interface of the application. The code included in this file is compatible with the Streamlit library. 

2. Crypto_wallet.py contains the Ethereum transaction functions. By using import statements, I integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file. 


Integrating these two files allow the user to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via Ganache Application.

## Task

Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

Fetch and display the account balance associated with your Ethereum account address.

Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

Review the transaction hash code associated with the validated blockchain transaction.

##Breakdown

Download Ganache & copy the mnemonic phrase into your .env file.

Follow instructions and update code accordingly. 

Streamlit run fintech_finder.py (Be sure to have ganache open)

Choose a potential professional and pay them to work for you.

Go to Ganache and screenshoot the increase of transactions.

Click the transaction tab and screenshot the address and new balan<img width="1440" alt="Screen Shot 2022-11-23 at 11 17 25 PM" src="https://user-images.githubusercontent.com/107821891/203715938-2967b625-94bd-40ac-9116-86e8aea07efa.png">
ce of the account.
<img width="1440" alt="Screen Shot 2022-11-23 at 11 16 32 PM" src="https://user-images.githubusercontent.com/107821891/203715923-683e7482-0a24-4a87-9834-8cc612556f1c.png">


##Libraries Used

streamlit
dataclasses
typing
web3
os
requests
dotenv
bip44

