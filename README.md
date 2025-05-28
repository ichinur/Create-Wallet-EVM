# EVM Wallet Generator

This Python script allows you to generate multiple Ethereum Virtual Machine (EVM) compatible wallets, including their mnemonic phrases, private keys, and addresses.

## Features

* **Batch Wallet Generation:** Generate any desired number of wallets in a single run.
* **Secure Generation:** Utilizes `eth-account` and `mnemonic` libraries for secure wallet creation.
* **Output to Files:** Automatically saves generated mnemonic phrases, private keys, and addresses to separate text files for easy access.

## Prerequisites

Before running the script, ensure you have Python installed. This script was developed and tested using Python 3.x.

You'll also need the following Python libraries:

* `eth-account`
* `mnemonic`

You can install them using pip:

```bash
pip install eth-account mnemonic
```

```bash
python3 generate_wallet_evm.py
