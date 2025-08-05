# Daily Swap for Plume Mainnet ( Ambient DEX )
Daily swap automation bot for interacting with the Plume Portal.

![plume portal](https://github.com/user-attachments/assets/77751fb2-1bdd-4290-a3a7-85feac591662)

## Feature bot
- Automated wallet login and authentication.
- Auto approve.
- PLUME ↔ pUSD

***For now, only PLUME to pUSD is operational. Please wait for the latest update!***

### Link :
https://portal.plume.org/?referrer=CornflowerResourcefulSort487

## Installation

Clone the project and install dependencies:

```bash
git clone https://github.com/Espenzuyderwyk/Daily-autoswap-plume.git
```
```bash
cd Daily-autoswap-plume
```
```bash
npm install
```

## ⚙️ Environment Setup
Create a .env file in the root directory:

```bash
nano .env
```

Input your private key and wallet address
You can change the random config as you wish

```bash
PRIVATE_KEY=your_private_key
WALLET_ADDRESS=your_wallet_address
PLUME_RPC=https://rpc.plume.org

MIN_PLUME=3
MAX_PLUME=5
MIN_PUSD=0.5
MAX_PUSD=1

MIN_TX=10
MAX_TX=30
MIN_DELAY=60
MAX_DELAY=180
```

## ▶️ Run the Bot
To run the automated PLUME ↔ pUSD swap bot:

```bash
node bot.js
```

It will perform a random number of swap transactions with randomized amounts and time delays.

### * If this bot doesn't work, you can swap manually first!

# The bot will:
1. Login wallet
2. Display information
3. Process transactions daily
4. Monitor and display user stats

# Disclaimer

This script is created for educational and personal experimentation purposes. It is not to be used for illegal activities, spam, or violations of GitHub rules.

- Use of this script is entirely the responsibility of the user.
- Do not use it to violate GitHub's Terms of Service.
