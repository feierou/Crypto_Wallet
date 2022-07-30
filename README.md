# Crypto_Wallet

I work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, I have been tasked with integrating the Ethereum blockchain network into the application in order to enable my customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

---

## Technologies

This project leverages Python and its libraries for coding, VS Code as writing tool, and streamlit for user interaction.

---

## Open Guide

By running the streamlit, run `fintech_finder.py` in terminal:

```
  1. Activate dev environment by: "conda activate dev"
  2. Run `pychain.py` by: "stremalit run fintech_finder.py
```
---
## Usage

*Import the following libraries and dependencies:*

``` python
from os import access
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
```
---
## Steps

* Import Ethereum Transaction Functions into the Fintech Finder Application
```python
from crypto_wallet import generate_account, get_balance, send_transaction
```
* Sign and Execute a Payment Transaction
```python
transaction_hash = send_transaction(w3,account,candidate_address,wage)
```

* Inspect the Transaction on Ganache
```python
streamlit run fintech_finder.py
```
---
## Result

*I selected Ash for 1.3 hours of work.*

![<streamlit>](<Screenshot/Streamlit.png>)


![<transaction>](<Screenshot/Transaction.png>)

![<details>](<Screenshot/details.png>)

---
## Contributors

Feier Ou

ffeierou1003@gmail.com