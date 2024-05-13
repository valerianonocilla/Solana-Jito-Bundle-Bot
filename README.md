# Solana Self Jito Bundle Bot

## New update, much faster and more efficient. Generate each purchase with a different amount to simulate as much as possible and go unnoticed.

Fastest script for solana to deploy & snipe from 27 different wallets in ms from launch using JITO and on-chain program. 

Bundle Create Pool & Snipe SPL Token in the same block with JITO

* Code is fully functional (Javascript/TS) 🛠️
* Utilizes JITO Bundle to create a new raydium pool & snipe the token in the same block. ⏰
* PM on telegram: [@SatoruGojox0](https://t.me/SatoruGojox0) 🧑‍💻

## Features

* **Market Creation:** Easily create markets with a lower cost of 0.3 SOL instead of 3 SOL.
* **Multiple Wallet Operations:** Utilize up to 27 different wallets to perform instant market operations programatically.
* **Comprehensive Trading Strategies:** From simple sell orders to sophisticated strategies involving a percentage of the supply.
* **Liquidity Management:** Options to add and remove liquidity effectively.
* **Guaranteed First Buys:** First 27 buys of the coin will always be yours and completely undetected using different keypairs and fee payer.
* **Comprehensive Documentation:** Even if you have no code experience, you will still be able to deploy and snipe using the easy prompts and the documentation attached.

## Script Functions

Execute these steps in sequential order. After executing each step, verify the transaction bundle has landed by checking the first included transaction on Jito Explorer.

**A) Create Keypairs**

Run this step as needed, not necessarily for every launch. Ensure the existent keypairs hold no SOL before proceeding because this will override them with new keypairs.

**B) Premarket**

Execute steps 2 through 6 in order. If a bundle does not land, re-execute the step with a higher tip. Step 1 is optional because you can create a market through other methods as well.

**C) Create Pool**

Repeatedly invoke the pool creation & bundling function. Increasing the tip and repeated attempts are recommended due to Solana congestion at peak times.

**D) Sell Features**

After the pool is live, proceed to either:

* Sell all keypairs at once and reclaim WSOL in the subsequent step.
* Gradually sell portions of the token supply on demand. This process involves transferring a percentage of each keypair's token balance to the fee payers and selling it all in one bundle.

**E) LP Removal**

This step removes liquidity from the market(if LP tokens are not burned)

## Other tools

* [Solana Volume Bot](https://github.com/valerianonocilla/Volume-Bot-Solana/)


## Support

**Lifetime Support** in: [@SatoruGojox0](https://t.me/SatoruGojox0)


## Full Version and Demo

For access to the full version of the bot and a demo, please contact:

Telegram: [@SatoruGojox0](https://t.me/SatoruGojox0)
