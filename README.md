# Moonshot Volume Bot
This solana Moonshot volume bot is designed to increase token volume on solana moonshot. Distribution of SOL to multiple wallets and execute automated buy and sell transactions on the Solana Moonshot platform. It's for giving basic understanding about main workflow of moonshot volume bot, and I have advance full version for it - Feel free to reach out of me when you want full/advanced version, when you face difficulty[Whatsapp: https://wa.me/13137423660, Telegram: https://t.me/DevCutup].

## How to use it
### .env File Setup
Before starting the bot, configure the `.env` file with the required details:
- **MINT:** Enter your token's correct mint address.
- **MICROLAMPORTS:** Fee for each transaction. Default: `400000` (0.000165 SOL).
- **SLIPPAGE:** Custom slippage for each transaction. Default: `1000` (10%).
- **MIN_BUY, MAX_BUY:** Minimum and maximum limits for each transaction.
- **MIN_DELAY, MAX_DELAY:** Minimum and maximum delay in milliseconds for each transaction.
- **VOLUME_WALLETS:** Number of wallets to use (e.g., 5, 10, 100).

### Installation 
1. Download and extract the bot on your Windows or Linux system.
2. Open the terminal in the bot's folder or open the folder in Visual Studio, then open the terminal.
3. Run the following command to install dependencies:
   ```sh
   npm install
   ```
4. To start the bot, use one of the following commands:
   ```sh
   npm start
   ```
   Or
   ```sh
   node main.js
   ```
5. The bot will create the required wallets and store them in `logs.json`. Ensure you copy each public key, add the necessary funds, and confirm the funds are above the min and max buy limits to run the bot without interruptions.

## Features
- Min & Max Buy & Sell Limit
- Custom Fee & Slippage & Fee
- Custome number of wallets
- Custom Fee Option

## Contacts
- Whatspp: https://wa.me/13137423660
- Telegram: https://t.me/DevCutup