# 🚀 **Sol-Price-Loss-Free-Bot** 

The SOL Price Loss-Free Bot is a useful tool that helps protect against losses caused by SOL price fluctuations and make profit with sol price change. The bot automatically swaps all SOL in your wallet to USDC when the SOL price drops below a set limit. Conversely, when the SOL price rises above the limit, it swaps all USDC back to SOL. This ensures that you avoid losses during volatile market conditions.

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

Twitter: @erikerikerik116

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

LIMIT_SOL_PRICE = 181.5

swap Sol to Usdc : [https://solscan.io/tx/127YoP3VKVqJqRoamMMSMAf7ECisCNm2S19Fa9KZtm1Kuvp14a6jPDuXqd1Wfa8k87T5hkt6eS8m9EDUkiofDoNJ](https://solscan.io/tx/127YoP3VKVqJqRoamMMSMAf7ECisCNm2S19Fa9KZtm1Kuvp14a6jPDuXqd1Wfa8k87T5hkt6eS8m9EDUkiofDoNJ)

![image (10)](https://github.com/user-attachments/assets/09c83343-c627-4ee2-b45d-724bbd268a50)


swap Usdc to Sol : [https://solscan.io/tx/52fd1F5mF5BtJPdUmeXxGofLExeawpMpAzfSRZmt9ynBHgnfUUL3tv1DDA9cKgi4ETyNvmMf5Sxz398mkjEP6Qa9](https://solscan.io/tx/52fd1F5mF5BtJPdUmeXxGofLExeawpMpAzfSRZmt9ynBHgnfUUL3tv1DDA9cKgi4ETyNvmMf5Sxz398mkjEP6Qa9)


![image (9)](https://github.com/user-attachments/assets/7d67253f-68d2-48c1-a8dd-fc76052ae87d)


## 🚀 **Getting Started**

Follow these steps to get your **Sol-Price-Loss-Free-Bot** up and running!

### Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/eriksol116/sol-price-loss-free-bot.git
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
