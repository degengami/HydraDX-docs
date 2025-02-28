---
id: howto_lp
title: Provide Liquidity
---

import useBaseUrl from '@docusaurus/useBaseUrl';

On this page you will find a **step-by-step guide for providing liquidity** in the HydraDX Omnipool. Becoming a liquidity provider allows you to **earn rewards** from the fees generated by trades in the pool.

Before deciding to become a liquidity provider, we encourage you to visit our [product page](/) and to **get yourself familiar** with the unique features of the HydraDX Omnipool.

## 00 Transport tokens
If you would like to execute a trade using a non-native asset (e.g. DOT or DAI), you first need to get these assets to the HydraDX chain. This step does not apply to HDX.

There are two different mechanisms to transport non-native assets:
* [Cross-chain transfer](https://app.hydradx.io/#/cross-chain) - use this tool to transfer assets from other Polkadot parachains, or from Polkadot itself. Step-by-step documentation [here](howto_xcm);
* [Ethereum bridge](https://www.portalbridge.com/#/transfer) - for bridging assets from the Ethereum ecosystem. Step-by-step documentation [here](/howto_bridge).

These solutions can also be used to transport tokens outside of the HydraDX network.

## 01 Navigate to Omnipool Liquidity
[https://app.hydradx.io/#/liquidity](https://app.hydradx.io/#/liquidity)

<div style={{textAlign: 'center'}}>
  <img alt="metadata" src={useBaseUrl('/howto_lp/lp_screen.jpg')} />
</div>

## 02 Connect Your Account
Click on `Connect wallet` **(1 in image above)** and connect to your preferred Polkadot wallet. After that, select your account.

## 03 Managing Your Liquidity

### Adding Liquidity
To add liquidity for a given asset, click the button `Add liquidity` which is located right next to that asset **(3)**.

:::important
In the HydraDX Omnipool, each individual asset has a Total Value Locked (TVL) cap. This means that once the cap has been reached, users can no longer further add liquidity for that specific asset. 

The individual caps for each asset will be reviewed from time to time by the team; any suggested revisions (either from team or the community) will be submitted as proposals via governance and voted on.
:::

<div style={{textAlign: 'center'}}>
  <img alt="metadata" src={useBaseUrl('/howto_lp/add.jpg')} width="500px" />
</div>

Fill in the amount of liquidity you wish to provide **(1)**, click `Add liquidity` **(2)** and sign the transaction using your wallet.

Next, you can learn [how to join Hydrated Farms](/howto_hydrated_farms) and earn additional rewards on top of the rewards from trading fees.

### Removing Liquidity
<div style={{textAlign: 'center'}}>
  <img alt="metadata" src={useBaseUrl('/howto_lp/remove_1.jpg')} />
</div>

To remove liquidity, toggle the dropdown located right next to the relevant asset **(1)** and click `Remove liquidity` **(2)** on the position you wish to exit.

<div style={{textAlign: 'center'}}>
  <img alt="metadata" src={useBaseUrl('/howto_lp/remove_2.jpg')} width="500px" />
</div>

Toggle or enter the amount of liquidity you wish to withdraw **(3)**, click on `Remove liquidity` **(4)** and sign the transaction using your wallet.
