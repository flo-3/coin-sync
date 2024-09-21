# Coin sync: Crypto Portfolio Manager Bot

## Overview
This project is a Telegram-based bot that simplifies cryptocurrency portfolio management by utilizing a dynamic embedded wallet. It allows users to link multiple wallets from various blockchains into one unified view. With real-time updates, seamless transactions, and an intuitive interface, the bot provides an efficient way to manage crypto portfolios directly within Telegram.

## Key Features
Link All Wallets in One Place: Connect wallets from multiple blockchain networks to monitor all assets in a single interface.

Real-Time Portfolio Updates: Receive dynamic updates on portfolio balances to stay informed about the current value of your holdings.

Gas Fee Optimization Alerts: Get real-time notifications when gas fees drop, enabling you to time transactions for the lowest costs.

Seamless Micro-Transactions: Conduct fast and secure peer-to-peer crypto payments within Telegram, ideal for tipping and rapid transfers.

Portfolio Performance Monitoring: Gain insights and alerts on portfolio movements, such as significant gains, losses, or price trends.

Security Alerts: Receive notifications about suspicious contract interactions or unknown tokens, ensuring your crypto assets are protected.

## Technology
The bot integrates a dynamic embedded wallet that adapts to multiple blockchain ecosystems, allowing seamless interactions across diverse crypto assets. Key technologies include:

Real-Time Notifications: Utilizes Telegram’s API to send alerts on gas fees, portfolio changes, and security warnings.

Integrated Transactions: Conduct transfers, swaps, or staking directly from the Telegram interface via the embedded wallet.

## User Experience
Designed for both new and experienced crypto enthusiasts, the bot offers:

Easy linking and tracking of multiple wallets in one view.
Daily, weekly, or on-demand portfolio summaries.
Secure micro-transactions and real-time market insights.

## Installation

Steps to have the Telegram app running

1. Create a Bot on Telegram using Botfather, [link to tutorial](https://core.telegram.org/bots/tutorial#getting-ready)
2. Clone this repo, run `cp .env.sample .env` and use your own Dynamic environment ID by replacing `NEXT_PUBLIC_DYNAMIC_ENV_ID` in the `.env` file
3. Deploy your website online. [link to tutorial](https://vercel.com/docs/deployments/git#deploying-a-git-repository)
4. Using Botfather, add the website url that should be opened for your TMA. [link to tutorial](https://docs.ton.org/develop/dapps/telegram-apps/step-by-step-guide#3-set-up-bot-mini-app)
5. Use Bot `TOKEN` from Telegram and your website url as LOGIN_URL in the `.env` file.
6. Run telegram bot `ts-node scripts/bot.ts`. If you do not have `ts-node` you can install it by running `npm -g i ts-node`
7. Go to your Telegram Bot and type `/start`

[Build Around the Booming Telegram Ecosystem](https://www.dynamic.xyz/ecosystems/telegram)
