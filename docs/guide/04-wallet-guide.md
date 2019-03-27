---
title: Solar Wallet Guide
---
# Solar Wallet Guide


## Payments

### Receive Payment

1. Go to the relevant account.
2. Select “Receive”

![null](/images/receive-button.png)

3. Your public key is written under the QR code. Click it to copy it. Send this public key to the entity/person you would like to receive a payment from. You can also scan the QA code with another Stellar wallet.

![null](/images/blur-2.png)

### Send Payment

1. Go to the relevant account.
2. Select the send button.

![null](/images/receive-button.png)

3. Fill in the destination address of the recipient
4. Add the amount and select the asset you want to send. 
5. Optionally, you can also include a text or an ID for your transaction by choosing “Text” or “ID” respectively under "Memo type" and then fill in the relevant information. Click “SEND”.

![null](/images/screen-shot-2019-02-26-at-13.00.17.png)

4. Fill in your password and click “Confirm” to proceed with your payment. If you don’t have a password, simply click “Confirm” to make the payment.

## Multi-Signature Account

### Enable Multi-Sig Feature

1. Go to main settings (click the “setting” icon on the top right corner of the main menu).

![null](/images/settings-button.png)

2. Click the toggle switch next to "Enable Multi-Signature Features" to activate.

### Make Account Multi-Sig

1. Go to the relevant account’s settings (click the “setting” icon on the top right corner on the account overview).  
2. Select "Manage Signers".
3. Select "Add Co-Signer" on the top right corner of the page.
4. Add the public key of the co-signer and enter the number of required co-signers for every transaction. Select "Apply Changes" to confirm it.

![null](/images/blue-3.png)

::: tip
"Required signatures" mean the number of accounts needed to authorize a transaction. For example, this could be 3/4 for an account that requires 75% approval to make a transaction.
:::

5. To remove a co-signer, simply select the "cross" icon next to the public key of the co-signer. Only the owner of the mult-sig account can remove/add co-signers.

### Create Multi-Sig Transaction

1. Follow the normal procedure to [send payment](https://docs.solarwallet.io/guide/04-wallet-guide.html#send-payment).
2. The owner of the other account(s) should go to the account page and look for "Transactions to co-sign". Identify the particular transaction and select "Review". If there is a password, type in password and press enter to authorize the transaction. If not, simply click "Confirm" to authorize the payment. 

![null](/images/screen-shot-2019-03-05-at-15.24.05.png)

3. After the authorization, the transaction will be carried out immediately. 

## Asset Management

To learn about assets, go to the [Stellar section](https://boring-edison-1091b3.netlify.com/guide/02-stellar-guide.html#about-assets)

### Add EURT/USD/CNY

1. Go to the relevant account’s settings (click the “setting” icon on the top right corner on the account overview). 
2. Select "Manage Assets". 
3. Select the asset you would like to trust. Then, select “trust asset”.

![null](/images/screen-shot-2019-02-26-at-13.05.35.png)

4. Type in the password of your account and select “confirm”. If you don't have a password, skip this step.

You are now ready to trade the asset which you have trusted.

### Add Custom Assets

1. Go to the relevant account’s settings (click the “setting” icon on the top right corner on the account overview). 
2. Select "Manage Assets".
3. Select "Add Custom Asset" on the top right corner of the window.
4. Put in the code, issuer (issuing account public key) and limit (maximum balance to hold). Select "Trust Asset" to confirm.

![null](/images/screen-shot-2019-02-26-at-09.37.19.png)

You are now ready to receive/send/trade the asset which you have trusted.

## DEX

### Trade view

![null](/images/trading-assets.png)

### Make a Trade

1. Go to the relevant account. Select "Trade" on the top right corner. 
2. On the Trade view, select the type of assets and the amount of the assets you would like to sell. Then, choose the selling price (regular, fast or super fast). The lower the selling price, the faster your assets would be sold. Next, select the assets you would like to purchase. The amount you would receive according to your selling price would be generated automatically. Finally click "Place Order" to confirm the your exchange order. 

## Testnet

To learn about assets, go to the [Stellar section](/guide/02-stellar-guide.html#about-stellar)

### Enable Testnet features

1. Go to main settings (click the “setting” icon on the top right corner of the main menu).
2. Click the toggle switch next to "Show Testnet Accounts" to activate the testnet option.
3. Select the arrow next to "Settings" to go back to the main page.
4. Now when you're back on the main page, the button "Switch to Testnet" would appear next to the setting button. Select "Switch to Testnet" to go to testnet.
5. To go back to "mainnet" or to leave testnet, select the "Switch to Mainnet" button next to the setting button.

### Friendbot

Friendbot is a tool on the Stellar testnet, which gives you free testnet lumens. Friendly, indeed.
