=== Breezepay ===

Contributors: Breezepay
Tags: Cryptocurrency, WooCommerce, USDC, USDT, Payments
Requires at least: 6.0
Tested up to: 6.4
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Make cryptocurrency payments a breeze in your WooCommerce store with the Breezepay plugin.

== Description ==

Make cryptocurrency payments a breeze in your WooCommerce store with the Breezepay plugin.

Breezepay is the fastest and easiest way for your customers to pay with cryptocurrency. By integrating Breezepay into your WooCommerce store, customers can opt to pay using USDC or USDT stablecoins across various blockchains, ensuring you receive the correct value for your goods while accessing a broader market of cryptocurrency users, without the volatility typically associated with cryptocurrency transactions.

== Community and Support ==

Join our [Discord Community](https://discord.gg/UQN8FPQ7wq)


== Supported Blockchains ==

- Ethereum
- Solana
- XRPL
- Tron (coming soon)

== Supported Cryptocurrencies ==

- USDT
- USDC
- AUDD (coming soon)

== Supported Wallets ==

- MetaMask
- Phantom
- Xumm/Xaman

== Benefits ==

- **Peer-to-peer:** Customers pay directly into your wallet. Breezepay never holds your funds.
- **Instant payments:** Transactions settle in your wallet immediately.
- **No chargebacks:** Cryptocurrency transactions require the customer to have sufficient funds, reducing fraud.
- **Dedicated Service:** Our team is always ready to assist with your Breezepay integration.
- **Easy payment experience:** Designed for simplicity, Breezepay encourages fewer drop-offs and increased revenue.
- **No upfront fees:** Breezepay is free to set up, with no monthly fees. We charge a modest 2% fee per transaction.

== Requirements ==

To install and configure WooCommerce Breezepay, you will need:

* WordPress Version 6.0 or newer
* WooCommerce Version 7.4.0 or newer (installed and activated)
* PHP Version 7.4 (Recommended version 8.0)
* Breezepay merchant account

== Installation ==

### Automatic Installation

1. To do an automatic install of Breezepay, log in to your WordPress dashboard, navigate to the Plugins menu, and click “Add New.”
2. In the search field type “Breezepay,” then click “Search Plugins.”
3. Once you’ve found our plugin, you can install it by clicking “Install Now,”.
4. Activate the plugin once the installation if finished.
5. Navigate to WooCommerce settings to configure Breezepay as your payment gateway.

### Activation

It’s easy breezy to activate Breezepay on your WooCommerce store: 

1. Contact Breezepay at [breezepay.com.au/get-started](https://breezepay.com.au/get-started) to receive your Client ID number and Secret Key
2. Set up your wallets to receive funds
3. Enter the above details into the Breezepay plugin, on your Wordpress admin panel. 

### Client ID Number + Secret Key

To receive these, contact us at [breezepay.com.au/get-started](https://breezepay.com.au/get-started) with your WooCommerce business name, website URL, and your wallet addresses to receive funds from your sales. After you have submitted these details, your Client ID number and Secret Key will be sent to you. 

### Wallet Set-Up

Breezepay currently accepts Solana, Ethereum and XRP wallets. We recommend using Phantom (Solana), MetaMask (Ethereum), and Xumm (XRP). 

### How to set up: 

Setup one or all of the wallets from the links below. You can find your wallet addresses by doing the following: 

1. [Phantom](https://phantom.app/learn/guides/how-to-create-a-new-wallet): On the wallet home page, click the receive button and choose Solana as the option. Your 44 character wallet address will then appear, with the option to copy it. Click copy, and paste it into your contact email to Breezepay. 

2. [MetaMask](https://support.metamask.io/hc/en-us/articles/360015489531-Getting-started-with-MetaMask): On the wallet home page, click the receive button and choose Ethereum as the option (it will likely already be defaulted to Ethereum). Your 42 character wallet address will then 
appear, with the option to copy it. Click copy, and paste it into your contact email to Breezepay. 

3. [Xaman (formerly Xumm)](https://help.xumm.app/app/getting-started-with-xaman/installing-xumm): On the wallet home page, click the receive button and choose XRP. Your 34 character wallet address will then appear, with the option to copy it. Click copy, and paste it into your contact email to Breezepay.

At Breezepay, we prioritise security, safeguarding your financial transactions.

== Screenshots ==

1. Breezepay payment button at the point of checkout
2. The payment process (select wallet)
3. Connect wallet
4. Confirm transaction

== Changelog ==

1.0.0 - Initial release.

== Upgrade Notice ==

1.0.0 - Welcome to Breezepay! Enjoy seamless cryptocurrency transactions in your WooCommerce store.

== Use of Third Party API ==

The WooCommerce Breezepay plugin depends on Breezepay API (https://api.paywithbreeze.co/api/v1) to generate unique, one-time, short lived payment url to which users are redirected to complete the payment process.

Breezepay's api uses OAuth 2.0 merchants client ID and client secret for validation.
It then takes the 'total amount' and 'reference ID' of customer's WooCommerce order, to generate the unique, one-time, short lived payment URL

Refer to our [Terms and Condition](https://www.breezepay.com.au/termsandconditions) and [Privacy Policy](https://www.breezepay.com.au/privacy) for any further conditions regarding or data collection or privacy aspects.
