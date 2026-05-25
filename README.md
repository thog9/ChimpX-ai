# Chimpx Auto Bot Scripts 🚀

This collection of Python scripts empowers you to interact seamlessly with the Chimpx platform, a blockchain-based system for Solana wallet automation. The core script, `main.py`, offers automation and multi-account support for core Chimpx activities.

🔗 Register: [Chimpx](https://app.chimpx.ai/)

## ✨ Features Overview

### General Features

- **Multi-Account Support**: Reads private keys from `pvkey.txt` to perform actions across multiple accounts.
- **Auto Wallet Creation**: Automatically creates new Solana wallets and redeems invite codes.
- **Colorful CLI**: Uses `colorama` for visually appealing output with colored text and borders.
- **Asynchronous Execution**: Built with `asyncio` for efficient blockchain interactions.
- **Error Handling**: Comprehensive error catching for blockchain transactions and RPC issues.
- **Bilingual Support**: Supports both English and Vietnamese output based on user selection.
- **Proxy Support**: Supports HTTP, HTTPS, and SOCKS5 proxies for network requests.

### Included Scripts

✨ Auto Referral Bot

- ✅ Automatic creation of new Solana wallets
- ✅ Automatic redemption of invite codes
- ✅ Displays wallet information, allocation, and personal codes
- ✅ Supports multistream (multi-threading)
- ✅ Supports proxy (HTTP, HTTPS, SOCKS5)
- ✅ Beautiful UI with colorama

✨ Auto Bot for Existing Wallets

- ✅ Automatic nonce retrieval and wallet verification
- ✅ Automatic allocation checking
- ✅ Automatic invite code redemption
- ✅ Displays detailed wallet information and personal code stats
- ✅ Supports multistream (multi-threading)
- ✅ Supports proxy (HTTP, HTTPS, SOCKS5)
- ✅ Beautiful UI with colorama

## 🛠️ Prerequisites

Before running the scripts, ensure you have the following installed:

- Python 3.8+
- `pip` (Python package manager)
- **Dependencies**: Install via `pip install -r requirements.txt` (ensure `solders`, `base58`, `PyNaCl`, `aiohttp`, `aiohttp-socks`, `colorama`, and `inquirer` are included).
- **pvkey.txt**: Add private keys (one per line) for wallet automation (for bot mode).
- **proxies.txt** (optional): Add proxy addresses for network requests, if needed.

## 📦 Installation

1. **Clone this repository:**
   ```sh
   git clone https://github.com/thog9/ChimpX-ai.git
   cd ChimpX-ai
   ```
2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Prepare Input Files:**
   - For Auto Bot mode: Open the `pvkey.txt`: Add your private keys (one per line) in the root directory.
   ```sh
   nano pvkey.txt 
   ```
   - For Auto Ref mode: No input file needed, just run and specify number of wallets to create.
   - Create `proxies.txt` for specific operations (optional):
   ```sh
   nano proxies.txt
   ```
   Format: `ip:port:user:pass` (one per line)
   Example:
   ```
   http://username:password@proxy.com:8080
   socks5://username:password@proxy.com:1080
   ```
4. **Run:**
   ```sh
   python main.py
   ```
   - Choose a language (Vietnamese/English).
   - Select the script you want to run.

## 📨 Contact

Connect with us for support or updates:

- **Telegram**: [thog099](https://t.me/thog099)
- **Channel**: [CHANNEL](https://t.me/thogairdrops)
- **Group**: [GROUP CHAT](https://t.me/thogchats)
- **X**: [Thog](https://x.com/thog099) 

----

## ☕ Support Us

Love these scripts? Fuel our work with a coffee!

🔗 BUYMECAFE: [BUY ME CAFE](https://buymecafe.vercel.app/)

🔗 WEBSITE: [BUY SCRIPTS](https://thogtoolhub.com/)
