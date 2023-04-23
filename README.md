# Fintech Finder Application

# Overview

Fintech Finder is a Streamlit-based web application that helps customers find, hire, and pay fintech professionals using Ethereum. The application allows users to view a list of fintech professionals, their ratings, and hourly rates. Users can select a professional, input the number of hours they'd like to hire them for, and send a payment transaction through the Ethereum blockchain.
￼
# Features
* Generate a new Ethereum account instance using a mnemonic seed phrase
* Display the Ethereum account balance associated with a user's Ethereum account address
* Calculate the total value of an Ethereum transaction, including the gas estimate, to pay a Fintech Finder candidate for their work
* Digitally sign a transaction that pays a Fintech Finder candidate and send it to the Ganache blockchain
* Review the transaction hash code associated with the validated blockchain transaction

# Installation and Setup

1. Clone this repository to your local machine.

https://github.com/Mansa6k/Stream-.git

2. Create a Python virtual environment and install dependencies.

python -m venv venv source venv/bin/activate 

pip install web3

pip install ipfshttpclient

pip install multiaddr

pip install varint

pip install python-dotenv

pip install bip44

pip install mnemonic

3. Add your Ethereum mnemonic seed phrase to the .env.example file and rename it to .env.

4. Start the Streamlit application.

streamlit run fintech_finder.py

5. Open the Streamlit application in your browser using the link provided in the terminal.

# Usage

1. On the Fintech Finder web interface, select a fintech professional from the drop-down menu.
2. Enter the number of hours you'd like to hire the fintech professional for.
3. Click the "Send Transaction" button to sign and send the Ethereum transaction.
4. The validated transaction hash will be displayed in the sidebar once the transaction is processed.
5. Review the transaction details on the Ganache blockchain.

# Screenshots

User's Ethereum Account Details

<img width="1195" alt="Address_balance" src="https://user-images.githubusercontent.com/118853744/233856914-751b0ee2-f66f-4e29-8d70-1d82468888d3.png">

Transaction Details

<img width="1193" alt="Transaction_details" src="https://user-images.githubusercontent.com/118853744/233856948-2af3c74c-ad31-4d59-b347-c21b99f2fcc6.png">


