# Fintech_Finder_Platform

The Fintech Finder Platform is an application that its customers can use to find fintech professionals from
among a listof candidates,hire them and pay them with cryptocurrency.


## Installations

```python
pip install web3==5.17
pip install eth-tester==0.5.0b3
pip install mnemonic
pip install bip44
```

## Technologies

This project uses Python and was operated on VSCode in conjuction with the following add-ons.


* [streamlit](https://streamlit.io/) - build and share data apps.

* [hashlib](https://pypi.org/project/hashlib/) - secure hashes and message digests.

* [Web3.py](https://pypi.org/project/web3/) - A Python library for connecting to and performing operations on Ethereum-based blockchains.

* [ethereum-tester](https://github.com/ethereum/eth-tester) - A Python library that provides access to the tools we'll use to test
Ethereum-based applications.

* [mnemonic](https://pypi.org/project/mnemonic/#:~:text=python%2Dmnemonic&text=It%20consists%20of%20two%20parts,BIP%2D0032%20or%20similar%20methods.) -
A Python implemetation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.

* [bip44](https://pypi.org/project/bip44/) - A Python implementation for deriving hierarchial deterministic wallets from a seed phrase
based on the BIP-44 standard.

* [Ganache](https://trufflesuite.com/ganache/) - A program that allows you to quickly set up a local blockchain, which you can use to test and develop
smart contracts.

## Usage

For usage of this application `fintech_finder.py` may be cloned. With streamlit installed `pip install streamlit` the application may be launched
by typing `streamlit run fintech_finder.py` locally on terminal
or git bash.

### The following images where taken from streamlit and ganache applications in use.

Candidate selection and hours hired. Note resulting successful hash code written to streamlit application sidebar.
 
![streamlit image 1](images/mod19-1.png)

### Image of Validating chain
![streamlit image 1](images/mod19-1.png)


# License
[MIT](license)
