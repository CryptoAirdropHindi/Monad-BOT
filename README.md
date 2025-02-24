# Monad Testnet Automation Guide

## Prerequisites
- Ensure you have **MON** & **ETH MON** in your wallet.
- Complete all **Monad Testnet** tasks before running the script.

---

## Installation

1. **Clone the Repository**
   ```bash
   https://github.com/CryptoAirdropHindi/Monad-Bot.git
   cd Monad-Bot
   ```
2. **Install Dependencies**
   ```bash
   npm install ethers@5 dotenv ethers ora readline cfonts prompts colors axios chalk figlet solc
   ```
3. **Set Private Key**
   ```bash
   echo PRIVATE_KEY=0x2xxxxxxxxxxx > .env
   ```
4. **Create and Use Screen**
   ```bash
   screen -R monad
   ```
5. **Run the Application**
   ```bash
   node main.js
   ```
(Press Ctrl + A, then D to keep the session running in the background.)


**Node.js Cleanup & Reinstallation**
   ```bash
	sudo apt remove --purge nodejs npm libnode-dev -y
	sudo apt autoremove -y
	sudo rm -rf /usr/include/node /usr/lib/node_modules ~/.npm ~/.nvm
	curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
	sudo apt install -y nodejs
	node -v && npm -v
   ```
  ---------------------------------------------------------------------------------------------------------------------------

"Great, all set! If you have any questions, don’t hesitate to ask in our Telegram channel."
Or if you'd like something more friendly and engaging:
- Telegram - https://t.me/Crypto_airdropHM
- Youtube - https://www.youtube.com/@CryptoAirdropHindi6
