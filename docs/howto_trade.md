---
id: howto_trade
title: Trade in Omnipool
---

import useBaseUrl from '@docusaurus/useBaseUrl';

This page provides a **step-by-step guide** which will **help you execute your first trades** using the HydraDX Omnipool.

The HydraDX Omnipool is a next-gen AMM which unlocks unparalleled efficiencies, you can find out more in our [product documentation](/).

<div style={{textAlign: 'center'}}>
  <img alt="metadata" src={useBaseUrl('/howto_trade/trade_screen_st.jpg')} />
</div>

## 00 Transport tokens
If you would like to execute a trade using a non-native asset (e.g. DOT or DAI), you first need to get these assets to the HydraDX chain. This step does not apply to HDX.

There are two different mechanisms to transport non-native assets:
* [Cross-chain transfer](https://app.hydradx.io/cross-chain) - use this tool to transfer assets from other Polkadot parachains, or from Polkadot itself. Step-by-step documentation [here](howto_xcm);
* [Ethereum bridge](https://www.portalbridge.com/#/transfer) - for bridging assets from the Ethereum ecosystem. Step-by-step documentation [here](/howto_bridge).

These solutions can also be used to transport tokens outside of the HydraDX network.

## 01 Enter Omnipool
[https://app.hydradx.io/#/trade](https://app.hydradx.io/trade)

## 02 Connect Your Account
Click on `Connect wallet` **(1 in image above)** and connect to your preferred Polkadot wallet. After that, select your account.

## 03 Execute a Trade
The HydraDX Trade UI allows you to intuitively execute a trade:

* Select the pair of tokens you intend to trade **(2)**;
* Enter the amount of tokens for the trade **(3)**.  
You can enter the amount of tokens you would like to pay with (e.g. 5000 DAI), but you can also enter the amount of tokens you would like to receive (e.g. 1000 HDX);
* If you would like to adjust your slippage preferences, you can do so in `Settings` **(4)**;
* To complete the trade with instant execution (pre-selected) **(5)**, click on `Swap` **(7)** and sign the transaction using your wallet. Otherwise, follow the additional steps below.

## 04 Execute a Split Trade
If your trade is large enough so that price impact would be > 0.15%, the UI will allow you to select `Split trade` **(6)** - breaking your trade into multiple smaller trades executed over < 3 hours and therefore reducing your price impact.

* Select the pair of tokens and amounts as in **03 Execute a Trade** above;
* Select `Split trade` **(6)**;
* To schedule your Split trade execution, click on `Place trades` **(7)** and sign the transaction using your wallet.

Stay hydrated, not liquidated.
