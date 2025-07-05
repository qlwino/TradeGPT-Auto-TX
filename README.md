


# 🚀 **TRADEGPT-AUTO-TX**

Automated trading and wallet interaction bot for the [0g.ai Galileo Testnet](https://chainscan-galileo.0g.ai/).  
Easily automate wallet queries, random swaps, and performance checks using the TradeGPT platform.

---

## **✨ FEATURES**

- **Batch Wallet Automation**: Process multiple wallets at once using private keys from `.env`.
- **Random TradeGPT Actions**: Simulates real user behavior with randomized prompts and swaps.
- **Automated Token Swaps**: Swap testnet USDT for other supported tokens using Uniswap router.
- **Wallet Information**: Fetches and displays OG/USDT balances and TradeGPT points.
- **Flexible & Customizable**: Change tokens, prompts, or network settings in the script.

---

## **🛠️ GETTING STARTED**

### **1. Clone the Repo**

```bash
git clone https://github.com/qlwino/TradeGPT-Auto-TX.git
cd TradeGPT-Auto-TX
````

### **2. Install Dependencies**

```bash
npm install
```

### **3. Configure Your .env**

Add your wallet private keys to a `.env` file in the project directory:

```env
PRIVATE_KEY_1=0xabc...your_key...
PRIVATE_KEY_2=0xdef...your_other_key...
# Add more as needed
```


### **4. Run the Bot**

```bash
node index.js
```

You’ll be prompted for the number of random chat actions/swaps per wallet.

---

## **💡 HOW IT WORKS**

1. **Wallet Scanning**: Loads each wallet and fetches testnet balances and points.
2. **Action Loop**: For each wallet, runs:

   * Random prompts to the TradeGPT API
   * Random swaps of testnet USDT for other tokens
   * Transaction and status logging
3. **Summary**: Shows updated wallet stats at the end of each session.

---

## **🪙 SUPPORTED TOKENS**

Supported tokens are listed in the `tokens` object in the script.
Modify or expand the list as you wish!

---

## **🔗 REQUIREMENTS**

* Node.js v18 or later
* A `.env` file with your private keys (see above)
* Testnet OG & USDT tokens on [0g.ai Galileo Testnet](https://chainscan-galileo.0g.ai/)

---

## **⚠️ DISCLAIMER**

* For educational and testnet use only.
* **Never use with real/mainnet funds.**
* Use at your own risk!

---

## **📄 LICENSE**

MIT

---

```

