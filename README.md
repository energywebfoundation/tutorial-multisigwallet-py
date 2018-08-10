# Gnosis Mutlisig Wallet tutorial and playground with Python and web3.py

For educational purposes.

Used with a local [Parity client](https://github.com/paritytech/parity-ethereum) version 1.11.8

### Dependencies

- Connection to Tobalaba test network. For a tutorial on how to set up a local [Parity client](https://github.com/paritytech/parity-ethereum) and connect to the network, check [here](https://energyweb.atlassian.net/wiki/spaces/EWF/pages/72974337/Install+the+Energy-Web+Client)
- [Parity UI](https://github.com/parity-js/shell) (Helps a lot)
- 3 accounts with some test Ethers in it. You can use the Parity UI for this purpose, then navigate to the [faucet](http://tobalaba.slock.it/faucet/) to get some ethers
- Python 3.6 with pip, and Jupyter notebook

### Setup
You need a [Jupyter notebook](http://jupyter.org/install):
```
pip install jupyter
(or pip3 install jupyter)
```
Then

```
git clone https://github.com/ngyam/tutorial-multisigwallet-py.git
cd tutorial-multisigwallet-py
pip install -r requirements.txt
(or pip3 install -r requirements.txt)
```

### How to use
 1. Make sure your Parity client is running and configured to connect to Tobalaba
 2. Open the [Jupyter notebook file](./MultisigWalletTutorialPy.ipynb) and play around.

```
cd tutorial-multisigwallet-py
jupyter notebook
```

### Resources

[Energy Web Foundation](http://www.energyweb.org/)

[Parity client](https://github.com/paritytech/parity-ethereum)

[Gnosis Multisig Wallet UI](https://wallet.gnosis.pm/#/wallets)

[Gnosis Multisig Wallet repo](https://github.com/gnosis/MultiSigWallet)

[web3.py documentation](https://web3py.readthedocs.io/en/stable/)  