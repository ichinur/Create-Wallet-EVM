# EVM Wallet Generator

A quick guide to install dependencies and run the wallet generator script.

## Prerequisites

* Python 3.7 or higher
* `pip` package manager

## Install Modules

Run the following command to install required packages:

```bash
pip install eth-account mnemonic
```

## Run the Script

1. Place the Python script (e.g., `generate_wallet_evm.py`) in your working directory.

   ```bash
   python3 generate_wallet_evm.py
   ```
2. When prompted, enter the number of wallets you want to generate (e.g., `5`).

The script will create or overwrite three files in the same folder:

* `mnemonic.txt` (one 12-word phrase per line)
* `pk.txt` (one private key per line)
* `add.txt` (one Ethereum address per line)

**Security Reminder:** Keep generated files safe and do not share private keys or mnemonics.
