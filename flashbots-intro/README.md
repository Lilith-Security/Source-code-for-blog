## A simple Flashbots bundle

<br>

### This directory contains the source code for [👾 MEV Wednesdays: Intro to Flashbots Auction](https://lilithsecurity.substack.com/p/-mev-wednesdays-intro-to-flashbots).

<br>

Install the requirements:

```
virtualenv venv
source venv/bin/activate
pip -r requirements.txt
```

<br>

Add a `.env` file:

```
vim .env
```

with

```
SENDER_KEY: Private key of account which will send the ETH
SIGNER_KEY: Private key of account which will sign the bundle (should be empty)
PROVIDER_URL: JSON-RPC Ethereum provider URL (e.g. Alchemy)
CHAIN_ID = 5 (Goerli)
```

<br>

Run:

```
python flashbots-example.py
```
