---
description: Description of DeFuturesBot for Automated Management of Exchange Positions
---

# 🤖 DeFuturesBot

This bot is designed to automate point farming on decentralized exchanges that support perpetual contracts (perpetual futures). The primary goal of the bot is to create and manage delta-neutral positions that minimize market risks associated with directional price movements of an asset. The bot employs hedging strategies to maintain neutrality to changes in the market value of the underlying asset while generating profits from spreads, premiums, or other market inefficiencies.

#### Key Features:

* Market Analysis: The bot collects real-time data on prices, trading volumes, and spreads between futures markets on selected decentralized exchanges (DEXs). Currently, it supports Paradex and Backpack, with more platforms to be added soon.
* Position Opening: Automatically opens long and short positions to achieve a delta-neutral state.
* Risk Management: Sets limits on maximum drawdown, monitors margin requirements, and automatically closes positions when necessary.

#### How It Works:

* The bot connects to the API of the selected decentralized exchange (e.g., Paradex, Backpack, or similar platforms).
* The bot independently determines optimal entry and exit points.
* No additional actions required from the user.

#### Advantages:

* Resilience to market fluctuations due to a neutral delta.
* Full automation of processes, reducing human involvement.
* Compatibility with decentralized platforms, eliminating the need to trust funds to centralized intermediaries.

#### Usage Requirements:

* Connection via API keys or a private key.
