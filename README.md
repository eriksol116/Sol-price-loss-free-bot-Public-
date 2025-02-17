# 🚀 **Sol-Price-Loss-Free-Bot** 

The SOL Price Loss-Free Bot is a useful tool that helps protect against losses caused by SOL price fluctuations. The bot automatically swaps all SOL in your wallet to USDC when the SOL price drops below a set limit. Conversely, when the SOL price rises above the limit, it swaps all USDC back to SOL. This ensures that you avoid losses during volatile market conditions.

Welcome to the **PumpFun Sniper Bot v5.2**! This bot watches for new `pump.fun` token mints on the Solana blockchain in real-time by using Geyser(Yellowstone), making it the perfect tool to monitor token launches. 🌟

### 🎯 **Key Features**

- 🛰️ **Automatic SOL to USDC Swap**: 
    Converts all SOL to USDC if the price falls below the defined limit.

- 🛰️ **Automatic USDC to SOL Swap**: 
    Converts all USDC to SOL if the price exceeds the defined limit.
  
- 🔍 **Customizable Parameters**: 
    Users can configure fetch intervals, price limits, and balance thresholds.

- 📊 **Loss Protection**: 
    Prevents losses due to SOL price fluctuations.

- ⚡ **JITO Support**: 
    Enables Jito fee configuration for optimized transactions.

---


## 📞 **Stay Connected**

Gmail: tom.kinddev@gmail.com

Telegram: [@erikerik116](https://t.me/erikerik116)

Discord: @erikerik116

## 🧑‍💻 **Environment Variables**

Create a .env file and add the following configuration:

PRIVATE_KEY=
RPC_ENDPOINT=
RPC_WEBSOCKET_ENDPOINT=
QUOTE_MINT=EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v
MAIN_MINT=So11111111111111111111111111111111111111112
COMMITMENT_LEVEL=confirmed
IS_JITO=true
JITO_FEE=0.00001

FETCH_SOL_PRICE_TIME=60000  # Fetch SOL price every 60 seconds
LIMIT_SOL_PRICE=180  # Threshold price for swapping SOL/USDC
MIN_SOL_BALANCE=0.01  # Minimum SOL balance to keep in wallet


## 🧑‍💻 **Setup and Usage**

swap Sol to  : https://solscan.io/tx/2zjrjqA6Jfrqc8FpasmfY4Eedgci36QoXVHCr2dS8MGQ7F4hEN8TQJ37TetYP75cj1u9kh4Eu7NgDvRvqZ425GBW

![grpc-buy-1-block-mint](https://github.com/user-attachments/assets/5ad5c0a9-1931-41fd-a088-630e58866078)

Token but : https://solscan.io/tx/2fJctjpCnidkCQqcWupj9rcyVYRYVNodNWV6982RDmXyXmiHVozvgPrBwqWwvhQiEvFJ8BsaUXN1HPF2GW856VXb

![grpc-buy-1-block-buy](https://github.com/user-attachments/assets/1bc5edcb-716d-4e5f-9fef-0ff10bc8cf16)


## 🚀 **Getting Started**

Follow these steps to get your **PumpFun Sniper Bot v5.2** up and running!

### Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/yourusername/sol-price-loss-free-bot.git
    ```

2. **Install Dependencies**:

    Navigate to the project directory and run the following command:

    ```bash
    cd sol-price-loss-free-bot
    npm install
    ```

3. **Configure API Token**:

    Replace the API token in the `ENDPOINT` variable:

    ```ts
    const ENDPOINT = 
    ```
    And set other variables in env file.

4. **Run the Bot**:

    Start the bot by running:

    ```bash
    npm run start
    ```

---

## 🧑‍💻 **Notes**

The bot requires a valid Solana RPC provider.

Ensure that your wallet has enough SOL for transaction fees.

JITO fee can be adjusted if needed.