# Payment

You should always use cryptocurrency when buying anything potentially illegal. PayPal, Cashapp, credit cards, debit cards, gift card and pretty much every other fiat currency can be traced directly back to you. This entire guide is pointless if you make a mistake here, so read carefully. 

## What cryptocurrency should I use? 

You can use Monero or BTC. Monero is drastically easier and doesn't require anything extra, it's all baked into the protocol.
BTC has been around the longest and it's the most popular, so most vendors accept it. It's fine if done right, but keep in mind that [every single transaction is public](https://blockstream.info/tx/recent), which is why you'll be making a new wallet for each purchase. 

## But my vendor doesn't accept crypto!

Find a better one. Any vendor that is reckless enough to not take crypto is also most likely very reckless with your information and shouldn't be trusted. 

## What about bank transfers / Western Union?

Linking your bank account to an illegal drug transaction is a terrible idea. 

## How do I set up a wallet? 

For Monero, see: [How do I set up a Monero wallet on Tails?](/diyhrt-opsec/operating_system/#how-do-i-set-up-a-monero-wallet-on-tails)
For BTC, 

## How do I buy crypto?

Buy Monero or Bitcoin (also known as XMR) from one of the exchanges listed at [kycnot](https://kycnot.me/search?q=&type=&xmr=on). If you have crypto at Binance / Kraken / any other exchange, withdraw it immediately. If it asks for identity verification do not provide it, and consider that money lost. 
If you're buying Monero, you can get it sent straight to your address. If you're buying BTC, check the below section. 

## How do I use Bitcoin securely?

Since you're using Tails, you already have Electrum installed, in Applications > Internet > Electrum Bitcoin Wallet

It will ask you a couple setup questions. When it asks what kind of wallet you want to create, pick standard wallet. When it asks if you want to create a new seed or restore one, pick "Create new seed". It should show you your seed. This is very important, and you should store it in a safe place outside of your computer, so you can recover your coins. Pick a strong password, unique when asked using the mnemonic method previously discussed. 

#### Configuring your wallet

Go to Tools > Preferences and turn on "Use dynamic fees" and "Enable Replace-By-Fee". Then switch to the "Transactions" tab in the new window and check the option "Use multiple change addresses". Then switch to the "Appearance" tab and switch the "Base unit" to BTC and change the "Online Block Explorer" to "blockchainbdgpzk.onion". After that, you should also change the value of "Zeros after decimal point" to something like 5. Now close the dialog by clicking on "Close". Last, press CTRL + A so you get the "Addresses" tab displayed which shows all your Bitcoin addresses belonging to your wallet. 

TODO: how to buy Bitcoin