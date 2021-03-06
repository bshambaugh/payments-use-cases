Use Cases and Requirements for Web Payments on Mobile
==================

This document outlines the use cases and requirements for payments on mobile. The use cases and requirements were gathered by gathering data on web and native applications with payment functionality, as well as looking at native payment platforms. 


## Motivation
The main questions this document seeks to expore are:
* What functionality is being achieved by native payment applications and platforms which is missing from the web?
* What functionality is being offered through proprietary plugins to the web for payments?
* What methods of payments are being offered to users through these other methods of payments?

On March 24-25 the W3C will hold a [Workshop on Web Payments](http://www.w3.org/2013/10/payments/Overview.html). We have been asked to submit our use cases to help define the work the W3C will do on web payments in the future. 

## Payment Methods

The following are examples of applications across web, iOS, Android and Windows Phone that allow users to pay for goods or services via various methods. 

### Highlights

There are several Cryptocurrencies, and cryptocurrency related technologies:

Bitcoin, LiteCoin, Anoncoin, ZeroCoin, NameCoin, Colored Coins, MasterCoin, Bitshares, Counterparty, Ethereum, Dodgecoin, Nxtcoin, TerraCoin, Peercoin, KryptoKit Bitcoin Wallet, KnCWallet, Coinbase, BitPay


There are several APIs tailored specifically for developers:

Stripe, Balanced, BrainTree, WePay, Paymill, GoCardless, Coinbase, Ven, BitPay, ClickandBuy, 2checkout


There are technologies that allow for a prepaid card:

NetSpend, PaySafeCard


There are technologies that allow for new uses for magnetic strip card readers:

Coin, Loop


There are several technologies that rely on magnetic card readers attached to a mobile device:

Square, Intuit GoPayment, WorldPay


There are technologies that allow for a prepaid card:

NetSpend, PaySafeCard, Netteller


There is a technology similar to prepaid card in that you get a number:

Ukash


Technologies that use NFC (near field communication) (Tap to Pay):

Isis, Google Wallet, Coinbase 


There are technologies that rely on new "Internet of Things?" technologies:

Proxima (iBeacon technology == Bluetooth LE)


Technologies that use a QR-Code for POS (Scan to Pay):

Starbucks App, Ripple, Krypto Kit Bitcoin Wallet, BitPay, Coinbase, Monetas (OpenTransactions)


Technologies that allow you to buy before you visit the store:

PayPal, Square, GoPago, Starbucks Rewards


Technologies where you click on a button in a website to pay (Click to Pay):
Coinbase


Technologies that allow payment with the app:

BlueVia, Western Union, Square (pay with your name), PayPal (check in to pay, order ahead, pay at table), Stripe, Braintree, Western Union, Starbucks Rewards (order ahead),GoPago, KnCWallet, Coinbase, Loop, Monetas (OpenTransactions)


Technologies that allow you to save cards in the app:

Braintree, Coin, Loop, Isis, Paypal


Subscriptions/Recurring Payments within API:

Stripe, BrainTree, 2checkout, Paymill, GoCardless, WePay, Coinbase, Balanced (not explicit, but possible)


Disputes within API:

Stripe, Braintree (void before settled, refund after settled), Balanced (refund for debit, reversal for credit), 2checkout (refund invoice, refund line item), Paymill (refunds)


Coupons/Discounts within API:

Stripe, Braintree, 2checkout


List Products in API:

2checkout


Conditional Payments within API:

WePay


Coupons/Discounts within the App:

Paypal, Starbucks Rewards


API allows for pre-authorization:

Paymill


Digital Wallet within the App:


### Paypal - Web, iOS, Android, Windows
Paypal allows users to pay for goods and services, send money and manage a wallet system from the web and iOS, Android, Windows and native applications.

__Use Cases__
* Send money to other users (identifying the users via email)
* Pay for goods and services from third parties
* Pay for goods and services in store from third parties
* Add funds via a 'wallet' system
* Withdraw funds via a 'wallet' system
* Pay via wallet system
* Pay using credit and debit card
* Link and pay by a bank acocunt
* Link mobile phone number to account and use for pay receipts
* Send money to almost anyone with an email or mobile number
* Request money (payment made using any method - credit card, etc.)
* Turn mobile device into a register, in store or on the go. Accept cards, checks, and PayPal.
* Automatic foreign exchange
* Invoices that don't require payer to get a PayPal account

__Region & Currencies__

Worldwide and multi-currency.

__For Developers__

[SDK](https://developer.paypal.com/webapps/developer/docs/integration/mobile/mobile-sdk-overview/) for Android and iOS applications:
* UI that accepts a PayPal or credit card payment from the user
* Coordinate the payment with PayPal
* Return to proprieter a proof of payment.

![Paypal iOS App: Sending Money](images/paypaliOSsend.jpeg) 
![Paypal iOS App: Wallet](images/paypaliOSwallet.jpeg) 

### Google - Web, iOS, Android, Windows
Google wallet allows users to pay for goods and services and send money to other users. It also allows merchants to manage loyalty cards 

__Google Wallet Use Cases__
* Send money to other users (identifying the users via email)
* Pay for goods and services online from third parties
* Pay for goods and services in store from third parties
* Add funds via a 'wallet' system
* Withdraw funds via a 'wallet' system
* Pay via wallet system
* Pay using credit and debit card
* Manage loyalty schemes

__Region & Currencies__

Worldwide and multi-currency.

__For Developers__

[APIs](https://developers.google.com/wallet/):
* Payment for goods and services on third party apps
* Loyalty programmes
* Digital payments

![Google Wallet iOS App: Sending Money](images/googlewalletiossend.jpeg) 
![Google Wallet iOS App: Wallet](images/googlewalletios.jpeg) 


### Web Payments / PaySwarm - PLATFORMS?
[https://web-payments.org/specs/](https://web-payments.org/specs/)

__Use Cases__
![Use Cases](https://web-payments.org/specs/source/use-cases/)
* Add money to PaySwarm Authority from credit card or bank account
* Mobile Computing-based Purchase (NFC, Bluetooth LE) 
* Point-of-Sale Device (Routing of purchase requests by vendor) 
* Ability to re-sell digital content (automatic redistribution licenses) 
* Conditional Redistribution (enable redistribution only when certain parameters are met - smart contracts) 
* Buy a product online through the use of a PaySwarm button in a web browser
* Complete verifiability (digital signatures on assets, listings, digital receipts, and identity) 

__Region & Currencies__

* Worldwide with any currency (goal)

__For Developers__

Text.

### Web Payments / PaySwarm - PLATFORMS?
[https://web-payments.org/specs/](https://web-payments.org/specs/)

__Use Cases__
![Use Cases](https://web-payments.org/specs/source/use-cases/)
* Verifiable identity (Know Your Customer is built-in)
* Simple Web-based Payment Links
* Separated Machine-readable Asset Markup (the Asset) and Pricing Information (the Offer)
* Decentralized, Machine-readable Metadata (Assets and Services)
* Separation of Content from Licenses
* Micropayments to Thousands of Individuals
* Ability to re-sell digital content (automatic redistribution licenses)
* Recurring Payments
* Mobile Computing-based Purchase (NFC, Bluetooth LE)
* Point-of-Sale Device (Routing of purchase requests by vendor)
* Automated Vending (Routing of digital receipts by buyer)
* Currency Exchange (Automatic currency translation)
* Alternative Currencies (Support for Bitcoin, Ripple, Ven, etc.)
* Streaming Payments (Pay-as-you-go - pay based on usage)
* Crowd-funding (all-or-nothing funding models)
* Proof-of-Purchase and Verifiable Digital Receipts
* Conditional Redistribution (enable redistribution only when certain parameters are met - smart contracts)
* Complete verifiability (digital signatures on assets, listings, digital receipts, and identity)

__Region & Currencies__

Text.

__For Developers__

Text.

### Reference: Tim Swanson, Great Chain of Numbers: a guide to smart contracts, smart property, and trustless asset management

![http://www.ofnumbers.com/the-guide/](http://www.ofnumbers.com/the-guide/)

This covers large portions of the Bitcoin world.

See especially: ![http://www.ofnumbers.com/wp-content/uploads/2014/03/current-cryptoprotocol-infrastructure.png](http://www.ofnumbers.com/wp-content/uploads/2014/03/current-cryptoprotocol-infrastructure.png) 
at the bottom of the page ![http://www.ofnumbers.com/2014/03/04/chapter-3-next-generation-platforms/](http://www.ofnumbers.com/2014/03/04/chapter-3-next-generation-platforms/)

### Bitcoin

![https://bitcoin.org/en/](https://bitcoin.org/en/) "Bitcoin is an innovative payment network and a new kind of money."

Use Cases:

    "Instant Peer-to-Peer Transactions"
    "Worldwide Payments"
    "Zero or low processing fees"


![https://github.com/schildbach/bitcoin-wallet/wiki/Payment-Requests](https://github.com/schildbach/bitcoin-wallet/wiki/Payment-Requests)

"This document describes the possibilities of Bitcoin Wallet version 3.38+ to initiate and respond to payment requests."

    Scan-to-pay
    Tap-to-pay
    Click-to-pay
    In-app-payments


![https://en.bitcoin.it/wiki/BIP_0070](https://en.bitcoin.it/wiki/BIP_0070)

"This BIP describes a protocol for communication between a merchant and their customer, enabling both a better customer experience and better security against man-in-the-middle attacks on the payment process." 

### Litecoin

![https://litecoin.org/](https://litecoin.org/)

Features:
* Uses scrypt in proof-of-work algorithm

### Anoncoin


![https://anoncoin.net/](https://anoncoin.net/)

### ZeroCoin

![http://zerocoin.org/](http://zerocoin.org)

"Zerocoin is a proposed extension to the Bitcoin payment network that adds anonymity to Bitcoin payments."

### NameCoin

![https://www.namecoin.org/](https://www.namecoin.org/)

Use Cases:
* Basis for a decentralized domain name system

Features:
* Based on Bitcoin

Further Information:

![http://dot-bit.org/Namespace:Domain_names_v2.0](http://dot-bit.org/Namespace:Domain_names_v2.0)

Use Cases:
* Anonymity if the coin is used on TOR or I2P

Features:
* Presently the only crytocoin that supports the I2P Darknet
* Bitcoins untraceable to a wallet or ID

### Colored Coins
![http://coloredcoins.org/](http://coloredcoins.org/)

"the open source standard for decentralized exchange"

Use Cases:

* Chroma Wallet (http://chromawallet.com/) 
** "Next generation colored-coins wallet"
** issue securities/tokens of any kind: shares, bonds, tickets, private currencies, smart property
** Send and recieve colored coins

### MasterCoin
![http://www.mastercoin.org/](http://www.mastercoin.org/)

"The Master Protocol facilitates the creation and trading of smart properties and user currencies as well as other types of smart contracts. Mastercoins serve as binding between bitcoins (BTC), smart properties and smart contracts created on top of the Mastercoin Protocol."

Features:
* Decentralized Exchange - "a way to trade their Bitcoin for Mastercoin or any other digital currency with out having to use a third party."
* User currencies - tools to allow anyone, even non-developers, to create their own currency or commodity with their own rules
* Smart Property - "Smart properties and smart contracts are digitized property rights and contracts rights, which may be transferred amount individuals and business entities via a protocol facilitated by the Bitcoin network."
* Wallet - collection of saving addresses

### Bitshares
![http://invictus.io/bitshares.php](http://invictus.io/bitshares.php)

"Bitshares X is the first experiment in taking the ideas introduced by Bitcoin to the next level by producing trust-free digital assets that have the potential to track the price of anything" (https://docs.google.com/document/d/1RLcjSXWuU9vBJzzqLEXVACSCdn8zXKTTJRN_LfoCjNY/edit)

Features:
* Transparent Blockchains
* Unnecessary trust
* Irreversible transactions
* Income from transaction fees

Whitepapers:

![https://docs.google.com/document/d/1RLcjSXWuU9vBJzzqLEXVACSCdn8zXKTTJRN_LfoCjNY/edit](https://docs.google.com/document/d/1RLcjSXWuU9vBJzzqLEXVACSCdn8zXKTTJRN_LfoCjNY/edit)

![http://static.squarespace.com/static/51df1ba4e4b08840dcfce197/t/5212ca63e4b0348bfd2276c6/1376963171729/BitShares%20White%20Paper%20%282%29.pdf](http://static.squarespace.com/static/51df1ba4e4b08840dcfce197/t/5212ca63e4b0348bfd2276c6/1376963171729/BitShares%20White%20Paper%20%282%29.pdf)

### Counterparty Windows OS, GNU/Linux OS
![https://www.counterparty.co/](https://www.counterparty.co/)

"A distributed financial market"

"Counterparty is a distributed financial system built on top of the Bitcoin blockchain. "

Use Cases:
* Derivatives - "Leverage positions in currencies and commodities. Write a contract for difference with the terms you specify."
* Stocks - "Start a company and issue stock to initial investors. Distribute dividends to your shareholders automatically."
* Bets - "Issue trustless bets in the Counterparty ecosystem. Place a wager on any event with a Win/Loss outcome."

### Ethereum - Platform (Windows, Mac OSX, Linux)
![https://www.ethereum.org/](https://www.ethereum.org/)

"A revolutionary new platform for applications"

Features:
* Implementation of turing complete programming language combined with a blockchain

### Dogecoin
![http://dogecoin.com/](http://dogecoin.com/)

"dogecoin is an open source peer-to-peer cryptocurrency, favored by Shiba Inus worldwide."

### NxtCoin
![http://www.nxtcrypto.org/

Features:
* "Nxt is a 2nd generation, scalable cryptocurrency offering a novel method of eco-friendly mining."
* "Nxt is not an altcoin such as litecoin, peercoin, and others who have their code based on Bitcoin's source code are. It is brand new from scratch with its own code."

### TerraCoin
![http://terracoin.org/](http://terracoin.org/)


"Peer to peer decentralized digital currency with no central authority, no chargeback and low transaction fees."

Features:
* Wallet, which is a collection of key pairs to create and sign transactions
* A peer-to-peer currency based on Bitcoin

### PeerCoin
![http://www.peercoin.net/](http://www.peercoin.net/)

"Secure & Sustainable CryptoCoin"

Features:
* "Proof-of-stake replaces proof-of-work to provide most of the network security."
(http://www.peercoin.net/assets/paper/peercoin-paper.pdf)

### PermaCredits
![http://permacredits.org/](http://permacredits.org/)

"The Local Currency for the Global Permaculture Movement"

Features:
* The First Commodity Backed Crypto Currency


### Stripe - Web, iOS, Android
[https://stripe.com/](https://stripe.com/)

__Use Cases__
* "Charge your customers in their own local currency"
* "Pay out in any bank account"
* "Accept payments from anyone, anywhere" (e.g. use Stripe Connect to collect transaction fees)
* With Stripe connect, customers do not have to re-enter account information for any of the merchants connected Stripe accounts

'''For Developers:'''

* "A set of unified APIs that instantly enable businesses to accept and manage online payments." 
* "Build platforms with Stripe and offer payments to your users"
* Authentication: authenticate to the Stripe API by providing one of your API keys
* Errors: conventional HTTP response codes to indicate the success or failure of an API request
* Versioning: new versions are released for stripe when the API is changed in a backwards incompatible way
* Expanding: include the ID of another object in the response query
* Metadata: allows for user specified description and metadata
* Charges: an object that is created when a debit or credit card is charged
* Customer: object that allows you to execute recurring charges and track multiple charges for the same customer
* Cards: store multiple cards for a customer for use when needed
* Subscriptions: method for charging of a customers card on a recurring basis
* Plans: pricing information for different products and features on your website
* Coupons, Discounts: listing and application of discounts for customers (loyalty programs?)
* Invoices: "statements of what a customer owes for a particular billing period"
* Invoice Items: add a charge or credit to a customers account, but only perform the action at the end of the regular billing cycle
* Disputes: an object is created when a customer disputes a charge to their bank account or credit card
* Transfers: an object is created when Stripe sends money or a transfer is initiated with a third party bank
* Recipients: "Transfer money from a Stripe account to a third party bank account" (https://stripe.com/docs/api)
* Application Fees: an object is created when a fee is taken from a Stripe account
* Account: see properties of a Stripe Account
* Balance: object representing Stripe Balance
* Events: show interesting things for a Stripe Account
* Tokens: charge credit cards or send payments to bank accounts without holding sensitive information on your servers

__Region & Currencies__

Text.

__For Developers__

Text.

### Intuit GoPayment - PLATFORMS?
[http://www.intuit-gopayment.com/](http://www.intuit-gopayment.com/)

__Use Cases__
* Accept payments through mobile phone by swiping of a credit card on an encrypted card reader
* Allow up to 50 user accounts
* Invalidate charges and send receipts again
* View history and import to Quickbooks
* Apply sales tax with geolocation

__Region & Currencies__

Text.

__For Developers__

Text.

### Square - iOS
[https://squareup.com/](https://squareup.com/)

__Use Cases__
Square Wallet:

* Customers can pay with their phones where square is used.

![Square Wallet for Starbucks 1](images/Square_wallet_starbucks1.jpg)
![Square Wallet for Starbucks 2](images/Square_wallet_starbucks2.jpg)
![Square Wallet for Starbucks 3](images/Square_wallet_starbucks3.jpg)
![Square Wallet for Starbucks 4](images/Square_wallet_starbucks4.jpg)


Square Cash:

* Send and request money for free with the use of a debit card and an e-mail address.

__Region & Currencies__

Text.

__For Developers__

Text.

### Skrill - PLATFORMS?
[https://www.skrill.com/](https://www.skrill.com/) 
(Need to look into mobile)

__Use Cases__
* Connect all your payment options and use them without revealing any financial details
* Bank and credit card details are never revealed
* Send money instantly to anyone with an email address
* Digital wallet

Features:

* Chargeback protection
* Fast integration
* Anti-fraud screening
* Accept secure ‘password only’ payments in 40 currencies from over 36 million people worldwide

__Region & Currencies__

Text

__For Developers__

Text.

### BrainTree - Web, iOS, Windows, Android
[https://www.braintreepayments.com/](https://www.braintreepayments.com/)

__Use Cases__
* Accept payments in your App or Website
* One Touch Payments in mobile with Venmo Touch, no entering personal information or card number
** card information encrypted and stored on BrainTree's servers
* Acceptance of payments in over 130 currencies, and deposit into U.S. bank account in 13 currencies
* Client side encryption of payment information with Braintree.js before being sent to your servers

__Region & Currencies__

Worldwide and multi-currency.

__For Developers__

API:

* Manage credit cards, subscriptions, and transactions
* API libraries in Ruby, PHP, Python, Java, Perl, Microsoft.NET, Node.js
(continue with https://www.braintreepayments.com/docs/node/guide/overview)

### PayPal
![https://www.paypal.com/](https://www.paypal.com/)

Use Cases:

* Send money to almost anyone with an email or mobile number
* Request money (payment made using any method - credit card, etc.)
* Turn mobile device into a register, in store or on the go. Accept cards, checks, and PayPal.
* Automatic foreign exchange
* Invoices that don't require payer to get a PayPal account

(Observation: pay in the store is like Square. Investigate this.)
https://www.paypal.com/us/webapps/mpp/pay-in-stores


### World Pay - Web, iOS, Android
[http://www.worldpay.us/](http://www.worldpay.us/)

__Use Cases__
* In person payment processing solutions 
* Accept debit, credit cards, checks, and electronic benefits transfer
* Counter top terminals, web enabled terminals, and industry specific
* PC compatible magnetic stripe reader and PIN pad with web enabled terminals
* Skip signatures on small tickets
* Split balances between multiple cards to protect from payment fraud
* Accept payments with an Apple or Android phone or tablet with card reader and app
* Feature to key transactions manually
* Accept payments with wireless terminal
* Access to account information through web browser
* World Pay Accounting Plugin For Quickbooks
* Collect recurring payments from your customers' credit cards or bank accounts with ACG direct debit
* Set up payment plans for purchases that customers could not otherwise afford 

Features: 

* End-to-End Encryption from the time the card is swiped to authorization
* PCI compliant
* SSL, tokenization, address verification system, and credit card security code for fraud protection
* Reporting tools:
** Manage Chargebacks
** Real time reporting of recent transaction data such as refunds in addition to authorization amount, settlement date, and more
** Self service tools allow editing of business and account information, management of user accounts, management of terminals, and ordering of supplies
** Four step payment process: payment transmission to WorldPay's processing systems after the card is swiped, authorization by verification of payment details by WorldPay and by an authorization request with the necessary details to the appropriate financial institution, verification by the financial institution through validation of the authorization information and checking whether their are sufficient funds in the customer's account, approval if funds exist and information is correct
* next business day settlement and credit and debit card sales


__Region & Currencies__

Worldwide and multi-currency.

__For Developers__

[APIs](https://developers.google.com/wallet/):
* 

### WePay - iOS
[https://www.wepay.com/](https://www.wepay.com/) 
(need to look into mobile)

"A Flexible Payments API built specifically for Platforms"
--"built for marketplaces, crowdfunding, and small business software"

__Use Cases__
* Let users accept social payments
* Use Oauth2 to let users create a WePay account with a pop-up on your site
* Collect payment information with an embedded form or a custom form
** embedded form handles data validation, PCI compliance, and more
** custom data checkout form to pass credit card to WePay directly where it is stored and given a unique token so customers may be charged in the future
* Use subscriptions to automatically charge customers at regular intervals
* Use delayed payouts to take payments immediately but delay the merchants access to the funds 
* Generate revenue by applying your own transaction fees to payments on your platform
* Deposit payments directly to user's bank accounts

Features: 

* Protection with Veda, a proprietary social risk engine 

__Region & Currencies__

Text.

__For Developers__

API:

* Merchant Category Codes to Classify Businesses
* Instant Payment Notifications to track the state changes of payments, accounts, and other API objects asyncronously

### Balanced Payments - PLATFORMS?
[https://www.balancedpayments.com/](https://www.balancedpayments.com/)

__Use Cases__
* Accept credit cards and ACH debit payments from your customers.
* Use with any card processor or as a stand-alone service for same-day bank deposits.
* Combine card processing and bank payouts with escrow.
* Balanced provides client libraries and a RESTful API for you to easily integrate.
* Decide when to disburse funds
* Define your own fee structure

Features:

* Completely white-labeled
* No monthly fees. No setup fees. No recurring fees.

__Region & Currencies__

Text.

__For Developers__

API:
* Authentication
** Uses HTTPS with a secret key
* API Keys - API Key Secret to Perform Authenticated Requests [properties: create, fetch, list, delete]
* Bank Accounts - resource that represents a bank account [properties: create, fetch, list, update,delete, associate with customer, debit]
* Bank Account Verifications - verify ownership of a bank account using micro-donations [properties: create, fetch and confirm a bank account]
* Callbacks - receive information at a URL of your choice [properties: create, fetch, list, delete]
* Cards
* Card Holds
* Credits
* Customers
* Debits
* Events
* Orders
* Refunds
* Reversals

### 2checkout - PLATFORMS?
[https://www.2checkout.com/](https://www.2checkout.com/)

__Use Cases__
Use Cases:

* Automatic fraud protection
* Accept credit cards and PayPal
* Recurring billing
* REST-based Payment API

Features:

* Monitor account status and history (outgoing, incoming, charts, etc.)
* Works with multiple shopping carts

__Region & Currencies__

Text.

__For Developers__

Text.

### Amazon Payments - PLATFORMS?
[https://payments.amazon.com](https://payments.amazon.com) 
(check for mobile)

__Use Cases__
* Get name, email, zipcode on login via Amazon button
* Buy via mobile
* One-time payments: supports simple one-time payments
* Recurring payments: lets customers schedule recurring payments
* Deferred payments: gives you the control to charge the customer when you want
* Multi-use payments: enables you to charge the customer multiple times based on a single authorization
* Marketplace payments: facilitates multi-payment needs between buyers and sellers in a marketplace
* Micropayments

__Region & Currencies__

Text.

__For Developers__

Text.

### Dwolla - PLATFORMS?
[https://www.dwolla.com/](https://www.dwolla.com/)

__Use Cases__
* Pay friends through email, phone, LinkedIn or Twitter.
* Eliminate paper checks - Cheaper and faster than sending or receiving paper checks.
* Cut out credit card fees.
* Operate as an agent of a financial institution.
* Payments for web and mobile apps - simple payment buttons, an offsite checkout gateway and OAuth + a RESTful API.

Features:

* No percentages. No hidden fees. Just 25¢ per transaction or free for transactions $10 or less.

__Region & Currencies__

Text.

__For Developers__

Text.

### WebMoney - PLATFORMS?
[http://www.wmtransfer.com/](http://www.wmtransfer.com/) 
(check for mobile)

__Use Cases__
* Enter into legally binding contracts
* 3rd party contract arbitration
* Budget automation
* Shared financial accounts (multi-party accounts w/ multiple managers)
* Crowdfunded loans
* Buy and sell debt on an open market
* Peer-to-peer loans via trust limits
* Mass payments to thousands of individuals
* Mobile-based two-factor authorization of large payment amounts
* Electronic checks where payment is made to the bearer of the digital check
* SMS-based peer-to-peer payment
* real-time, offline mobile to mobile payments
* Allows the escrow of funds to be released when a certain business transaction is successful
* Login mechanism using bank-issued OpenID

__Region & Currencies__

Text.

__For Developers__

Text.

### Ukash - PLATFORMS?
[https://www.ukash.com/](https://www.ukash.com/) 
(check for mobile)

__Use Cases__
* Convert cash into 19-digit number which you can use to spend at stores
* Redeem online or at Moneygram locations

Features:

* Free to use money once converted to ukash.

__Region & Currencies__

Text.

__For Developers__

Text.


### Netteller - PLATFORMS?
[http://www.neteller.com/](http://www.neteller.com/) 
(check for mobile)

__Use Cases__
* Deposit money into eWallet from credit card or bank account
* Withdraw money from eWallet to bank account
* Pay at online stores supporting Netteller
* Pay friends and family
* eWallet tied to Mastercard card
* Multiple currency accounts

__Region & Currencies__

Text.

__For Developers__

Text.

### ClickandBuy - PLATFORMS?
[https://www.clickandbuy.com/](https://www.clickandbuy.com/)

__Use Cases__
* Mobile-optimized QR-code based payment page
* View all credits and transactions
* Multi-device compatibility - Make purchases on all end devices (PC, tablet, smartphone) including in-app possibilities
* Diversity - Integration of all standard payment procedures such as credit card, debit card, direct debit and bank transfer
* Sales with new customers - Easier transactions even for new customers thanks to carefully simplified payment processes	
* Micropayments - Attractive conditions even for the smallest amounts	
* Discretion - Secure storage of bank and credit card details
* Simplicity - Simple, secure payment with just a few details (new customers) or w/ username and password (registered customers)
* Speed - Even quicker payment with one-click payment
* Flexible payment models - 	Supports one-click payment as well as single and partial payment, payment in instalments, subscription and auto top-up	
* Flexibility - Convenient payment on all end devices
* Increased sales - Increased sales through target-group-specific e-mail, mobile and online marketing
* Purchasing benefits - Attractive welcome, discount and incentive offers in cooperation with shop partners

Features:

* Security - Protected by TÜV-approved and PCI-DSS-certified security technology of the highest quality
* Cost-savings - No basic monthly fee, no contract periods, payment methods as desired	
* Payment security - All payments checked using a well-established risk management system to prevent fraud and defaults
* Transparency - All transactions can be managed and monitored at all times via the merchant service area	
* Overview - Transactions and account balance can be viewed in any place at any time, on mobiles using the smartphone app
* International character - Purchases can be made in 120 currencies and 193 countries
* Protection - Additional protection for delivery items

__Region & Currencies__

Text.

__For Developers__

Text.

### PaySafeCard - PLATFORMS?
[https://www.paysafecard.com/](https://www.paysafecard.com/)

__Use Cases__
* Purchase PaySafeCard at nearest sales outlet in varying amounts 
* Purchase at Web Shops by entering a 16-digit paysafecard PIN
** The two cases above allow for payments online without a bank account or credit card
* Make larger payments with up to 10 PaySafeCard PINs
* PaySafeCard App 
** Find sales outlets in your area
** Veiw your PaySafeCard balance 
* Deposit into your Skrill digital wallet

__Region & Currencies__

Text.

__For Developers__

Text.

### Western Union - PLATFORMS?
[http://www.westernunion.com/Home](http://www.westernunion.com/Home)

[https://globalpay.westernunion.com/Default.aspx](https://globalpay.westernunion.com/Default.aspx)

__Use Cases__

Text.

__Region & Currencies__

Text.

__For Developers__

Text.

### Paymill - Web, iOS, Android
[https://www.paymill.com/](https://www.paymill.com/)

__Use Cases__
* Customers can pay directly on the developers website
* Payments processed in 100 currencies
* Only successfully closed transactions paid for
* Comprehensive risk and anti-fraud measures
* Payments paid in 23 different currencies
* Credit cards from around the world accepted
* Refund payments
* Subscription based payments

__Region & Currencies__

Text.

__For Developers__
API:

* Implemented with REST
* All response objects delivered as JSON objects
* test keys and live keys included
* Requests made with https
* Response codes for JSON objects such as transactions and refunds
* Different list views for different entities in the API
* Sort JSON response objects in the way you have requested
* payment objects represented by a credit card or through direct debit
* specific payment details with unique identifier
* Function returning a JSON object with a list of payments
* Function removing a specified payment
* Preauthorization object to reserve money from a clietns eridt card and execute a transaction later
* List payments, preauthorizations, transactions, refunds, clients, offers, subscriptions, webhooks
* Remove preauthorizations
* Transaction object with a unique identifier for charging of a credit card or a direct debit
* create a token or a payment object before executing a transaction
* Recieve details of an existing transaction with a transaction ID
* Refunds with their own calls for existing transactions, refunded to the account of the client (with a fee for every refund)
* Clients object to edit, delete, and update clients in addition to allowing refunds, subscriptions, inserting of credit card details
* Export client list as a CSV object
* Offer object which represents a recurring plan (over different periods) that a user can subscribe to
* Update and remove offers
* Subscriptions  to charge recurring payments on a credit card or a direct debit ... connects to offers object
* Use Webhooks to react automatically to certain events in Paymill's system, HTTP POST to a URL or send information to an e-mail
* Various internal objects lacking an public API endpoint: Fee Object, Invoice Object, Merchant Object, Payment method Object
* Paymill libraries in Java, JS, .NET, PHP, Python, Ruby

Features:

* All data in Paymill is encrpyted
* PCI DSS Level 1 compliant
** All credit card data is represented by token and private key only
* 3D-Secure XML based protocol available (see: en.wikipedia.org/wiki/3-D_Secure)
* Mobile SDK
** Available for both iOS and Android
** Delivered as a framework a Bundle for iOS and a JAR file for Android

### GoCardless - PLATFORMS?
[https://gocardless.com/](https://gocardless.com/)

"UK's leading online Direct Debit provider"

__Use Cases__
* Customers set up with direct debit in seconds by requests by e-mail or on your site (linked to GoCardless payment page)
* Payment submission and payment tracking online
* Bank details stored securely
* Notifications sent for compliance
* control when you get paid with direct debit
* Automatically retry failed payments
* Dashboard
** Status reports of all your payments and customers
** E-mail notification when a payment fails or a customer cancels
** Export data for use in other apps
* Upload a CSV to do business with multiple customers at once
* Link your page to GoCardless' page, request payments from the dashboard
* Automate recurring payments

__Region & Currencies__

Text.

__For Developers__
* Add a checkout button to your site or e-mails
* Integrate with accounting software
* REST API with Webhooks
** Automate your payments at any time with just one line of code
** RSA encryption and secure communication for customer data
** Easy to use API libraries allow for simple integration with a website

API: 

* Three resources that can take payments: bill, subscription, an pre-authorization
** Bill - payment from a customer's bank account
** Subscription - resource that will create a bill after a defined interval of time
** Pre-authorization - enables the developer to take variable payments without further action from the customer
* Payouts - payment made from GoCardless to a merchant's bank account
* Merchant - orrganization collectiong payments in one of three ways: one-off bills, subscriptions, and pre-authorizations
* user - something that has a bill, subscription, or pre-authorization with the merchant
* Webhook - HTTP POST to GoCardless to notify your server of changes to a resource
* With payment timings the amount and date of the next transaction will be illustrated, which is less than or equal to the viewable existing balance
* Official libraries in PHP, Ruby, Python, Node.js, .NET, and Java
* Community libraries for Wordpress, Clojure, and Perl
* Filtering in the URL to cut down the number of objects returned leading to faster API response time
* Optional pagination for when endpoints contain multiple records
* Pre-population of users payment pages on GoCardLess
* Webhooks in the form of POST requests sent to the when a resource changes status
* POST data contains information generated with the merchants "app secret" to prevent invalid web hooks
* Available Webhook objects: Bill (can be subscription or pre-authorization) [actions: created, paid, withdrawn, failed, cancelled, refunded, chargedback, retried], Pre-authorization [actions: cancelled, expired], Subscription [actions: cancelled, expired]
* Partner API to "create and manage multiple merchants". This includes:
** Partner account setup
** Creating multiple merchants
** Request [parameters: client_id, redirect_uri, scope, response_type]
** Response 
** Exchange authorization code for access token, HTTP access request with app identifier and app secret [parameters: client_id, code, redirect_uri, grant_type]
** Pre-populating information
* Resources
** Bill - "one-off payment from the user" - create one-off bill - confirm one-off bill - check the signature (use OAuth) - Complete the process - ..- list all bills - retrieve an existing bill - retry a failed bill - bill statuses
** Merchant - collects payments in three ways: one-off bills, subscriptions, and pre-authorizations - attributes: retrieve merchant details, 
** Payout - payment made from go-cardless to a merchants bank account - objects: list all payouts (array of payout objects), retrieve an existing payout ("returns a payout object")
* Pre-authorization - when merchant wants to collect variable direct debit from the customer until an expiration date
* Subscription - recurring direct debit for a fixed amount until an expiration date

### solution
text

__Use Cases__


__Region & Currencies__

Text.

__For Developers__

Text.

### GoPago - PLATFORMS
[http://www.gopago.com/](http://www.gopago.com/)

__Use Cases__

Text.

__Region & Currencies__

Text.

__For Developers__

Text.

### BlueVia - PLATFORMS?
[http://www.bluevia.com/](http://www.bluevia.com/)

"global network for charge to mobile payment"

Use Cases:

* Customers pay for digital goods using their mobile bill or prepaid account.
* Customers pay with just one click
* Can accommodate any content
* Form filling, registrations, redirections, and card details avoided 

Features:

* Mobile payments delivered safely and securely.
* Available in Argentina, Brasil, Chile, Columbia, Germany, Mexico, Spain, and the U.K.

(there is a mobile version, but what is this exactly?)
(check out BlueVia Labs: http://labs.bluevia.com/en/home/B)

API:
* SMS API - send and receive SMS, check the delivery status of sent SMS
* Voice API - make and receive calls, create conferences, IVRs, ...
* MMS API - send MMS with images, text, video, or audio from your APP
* Libraries for Android, Java, .NET, PHP, and Ruby LGPL v3.0
* Web Standards: OAuth, REST
* Find the location of a user
* Get Advertising


__Use Cases__


__Region & Currencies__

Text.

__For Developers__

Text.

### KryptoKit Bitcoin Wallet - Google Chrome Browser
[http://kryptokit.com/](http://kryptokit.com/), [Chrome Web Store](https://chrome.google.com/webstore): KryptoKit Bitcoin Wallet

__Use Cases__
* Instant Bitcoin Wallet and secure Instant Messaging System that Runs in the Browser
* Create a Bitcoin Wallet without usernames or passwords
* Client Side Encryption, user data not sent to servers
* Deposit to a wallet through a provided address or QR code
* Extraction of Bitcoin addresses of the pages viewed to a bulleted list in the wallet window
* Create, Import, or Export a BrainWallet (i.e. a Bitcoin address created from a passphrase)
* Optional password protection of the Bitcoin wallet
* One click backup of KryptoKit Data
* Create GPG key and share the public key with anyone with which you want to communicate
* Instant Message notifications within the browser
* Bitcoin market charts in multiple currencies
* Contact list to store most often used addresses
* Bitcoin directory of places to spend Bitcoin
* Click the Bitcoin address you wish to send Bitcoins to and enter the amount you wish to send

__Region & Currencies__

Text.

__For Developers__

Text.

### Clinkle
[https://www.clinkle.com/](https://www.clinkle.com/)

Not launched yet.

__Use Cases__
* Mobile App for Mobile Wallet
* Wallets linked to Credit Cards and Bank Accounts
* Provide merchants with information about customers for targeted sales promotions

__Region & Currencies__

Text.

__For Developers__

Text.

### NetSpend - PLATFORMS?
[http://www.netspend.com](http://www.netspend.com)

__Use Cases__

Use Cases:

* Register for an account and receive a card in the mail
* Activate your card online or by phone
* Deposit money through direct deposit of your paycheck or by visiting 100,000 Netspend locations
* Make purchases anywhere Visa and MasterCard debit cards are accepted
* Use at ATM
* Through an online portal see transactions, balance, and deposits
* Pay bills online either in the moment or schedule later
* Receive SMS messages when money is available in your account
* Create a budget
* Mobile
** transfer money to and from savings account

__Region & Currencies__

Text.

__For Developers__

Text.

### KnCWallet - Android
[http://kncwallet.com/](http://kncwallet.com/)

__Use Cases__
* Send and receive Bitcoins using mobile phone contacts
* Back up encrypted wallet to Google Drive and DropBox

__Region & Currencies__

Text.

__For Developers__

Text.

### Freshbooks - PLATFORMS?
[http://www.freshbooks.com](http://www.freshbooks.com)

(example of what the above web payments solutions may integrate with)

__Use Cases__
* Cloud Accounting Software
* Integration with various payment gateways such as stripe, PayPal, beanstream, Authorize.net, 2checkout.com, Braintree, eway, iTransact

__Region & Currencies__

Text.

__For Developers__

Text.

### Starbucks App - iPhone, Android 

[http://www.starbucks.com/coffeehouse/mobile-apps](http://www.starbucks.com/coffeehouse/mobile-apps)

Use Cases:

* Pay with your phone (though a barcode scan displayed on the phone's screen)
* Earn stars toward Starbucks rewards
* Get directions to nearest Starbucks store
* Obtain information about beverages, food, and nutrition
* Listen to pick of the week songs
* Send eGifts to contacts
* Be the first to hear of special offers
* Reload by cash at the register with a minimum of $5.00
* Reload by Paypal, or choose an existing Starbucks gift card

For iPhone:
![Starbucks iPhone Mycards](images/Starbucks_iPhone_MyCards.png)
![Starbucks iPhone Reward](images/Starbucks_iPhone_Reward.png)
![Starbucks iPhone eGift](images/Starbucks_iPhone_eGift.png)
![Starbucks iPhone Home](images/Starbucks_iPhone_Home.png)
![Starbucks iPhone locationfinder](images/Starbucks_iPhone_locationfinder.png)
For Android:
![Starbucks Android Wallet](images/Starbucks_Android_wallet.jpg)
![Starbucks Android rewards](images/Starbucks_Android_rewards.jpg )
![Starbucks Android rewards2](images/Starbucks_Android_rewards2.jpg )
![Starbucks Android location finder](images/Starbucks_Android_locationfinder.jpg)
![Starbucks Android reload card](images/Starbucks_Android_reload_card.jpg)

### Coinbase - Web, Android, iPhone, SMS  
![http://www.coinbase.com](http://www.coinbase.com)

Use Cases:
* Mobile Wallet
* Add bank account to buy or sell Bitcoin in minutes
* Free payment processing to $1M, 1% after
* Receive the exact amount of local currency you price your products at (no exchange rate risk)
* No chargebacks with Bitcoin
* Wallets and private keys stored with AES-256 encryption. Coinbase runs on SSL.
* 97% of consumer funds are stored offline in bank vaults
* Two factor authentication on all coinbase accounts: enter a code from a mobile phone in addition to username and password

https://coinbase.com/docs/merchant_tools/getting_started

Features:
* SQL injection filters to prevent CSRF attacks
* Hashed passwords, strong password check, application credentials separated from the code base and database
* variety of actions rate limited, such as password attempts
* "We whitelist attributes on all models to prevent mass-assignment vulnerabilities"

API:
* REST based API available to apps and websites
https://coinbase.com/docs/api/overview

### Hive Mac OSX 
![https://www.hivewallet.com/](https://www.hivewallet.com/)

Features:
* Easy to create a Bitcoin wallet
* Coins - "Create and organize your contacts; send and receive bitcoins in a matter of seconds."
* Built in apps included
* Backup through Drop Box and Time Machine
* Easy to Use
* Security - "Security is our primary goal. Be safe while you enjoy the Bitcoin ecosystem with Hive!"

### BitPay 
![https://bitpay.com/](https://bitpay.com/)

Use Cases:
* The merchant receives their local currency while you pay in Bitcoins
* Pay phone to phone by scanning a QR code

Features:
* No risk of identity theft. Authenticate only the money.
* Charge backs eliminated.

### Proxima Wallet 
![http://www.proxima.io/#home](http://www.proxima.io/#home)

### Loop 
![http://www.looppay.com/](http://www.looppay.com/)

Review:
http://www.theverge.com/2014/2/19/5425494/loop-wallet-mobile-payments-review

Use Cases:
* Pay with your phone
* Usable with traditional credit card reader
* Load an unlimited number of cards, including gift cards and loyalty cards
* Pay with the FAB that attaches to your phone when it is not attached to your phone using a default card
* Save ID card to phone

Features:
* Approximates NFC by "tricking" the card reader by transmitting wireless magnetic data
* Works at 90% of retailers

### Isis - Android, iOS 
![https://www.paywithisis.com/](https://www.paywithisis.com/)

Use Cases:

* Mobile wallet holds offers and loyalty cards from participating merchants

### Coin 
![https://onlycoin.com/](https://onlycoin.com/)

Use cases:
* Replaces all of your cards with one card
* Mobile app can store an unlimited number of cards, coin card can store 8
* "Our mobile app will allow you to add, manage and sync the cards that you choose to store on your Coin."
* Take a picture of the card, and swipe the coin through a device to add it

### Ven
![http://www.ven.vc/about](http://www.ven.vc/about)

"Ven is a global digital currency that's easy to use and great for the environment."

Use Cases:

    Online wallet
    Buy items online
    Setup payment/invoice pages

Features:

    Using the system gives you access to Hubs around the world
    Buy/sell hub stuff by using Ven
    From comparison to Bitcoin:
        "Hedge stability - from diversified asset banking"
        "Transparent Social - linked to social network, HubID"
        "Central exchange - a responsible reserve system"
        "Asset basis - currencies, commodities, carbon"
        "Meritocratic - works within existing regulatory system"
        "Digital Accounting - big data ledger, transaction histories"
        "Native Ecosystem - visible network, transaction tracing"
        "$2.5M total - projected 2014 FX trades: $1B
        "Helps nature - over 5 million Amazon trees saved to date"

Attributes:

    Stable - "Ven is less volatile than the market"
    Global
    Secure
    Green - Does not require extensive energy (i.e. CO2 emissions) to produce

For Developers:

http://developers.hubculture.com/

APIs:

    Public Ven Price
    Realtime Ven Price
    FIX Market Trading
    Mobile Device API
    Authority

Screenshots:

Transactions: Ven-UseCase1-Transactions.png
Transactions Ledger: 
Content Micropayment: 
Store: 

### Ripple
![https://ripple.com/client](https://ripple.com/client)

Ripple is a payment network this is open source, decentralized, and free to use. It provides distributed clearing, settlement, and foreign exchange. There are web and iOS apps for making payments but, more importantly, Ripple can be used to bridge other payment networks and can be integrated with other wallet solutions.

Use Cases:

    Bridge other payment networks
    Payments in any currency or store of value (USD, EUR, BTC, gold, etc)
    Wallet can hold any store of value
    In-stream foreign exchange (payment senders and recipients need only deal in their preferred currencies, the network handles the exchange automatically)
    Payments executed atomically, avoiding currency risk
    Distributed clearing and settlement system (clearing takes 2-10 seconds)
    Distributed foreign exchange platform that cross-currency payments take advantage of automatically
    Remittances
    Micro-transactions
    Based on public-private key cryptography
    Practically 0 network transaction fees (currently 1 USD can pay the network fees for more than 5 million transactions)

Regions & Currencies:

    Currently, AUD, BTC, CAD, CHF, CNY, DOG (dogecoin), DYM (silver dimes), EUR, GBP, ILS, JPY, LTC (litecoin), NMC (namecoin), NXT (nxtcoin), TRC (terracoin), USD, XAG (silver), XAU (gold), XRP (ripple native currency)
    Network is global
    All that is needed to use Ripple in another region or currency is for a 3rd party to start a gateway. Gateways accept and store currency outside of the network and issue IOUs for customers to use on the network

For Developers:

    Source code for backend, frontend, and developer tools is open source and on Github: https://github.com/ripple
    RPC and Websocket APIs available, REST API is in beta
    Wiki and Developer Portal have documentation and other resources


Ripple Wallet:  
Send Ripple: 
Receive Ripple: 
Trade XRP: 
Establish trust with another node in the Ripple network: 

More Info: https://ripple.com/ripple_primer.pdf

### OpenTransact 
![http://www.opentransact.org/](http://www.opentransact.org/)

OpenTransact vs. PaySwarm:

Manu Sporny, Webpayments: PaySwarm vs. OpenTransact Shootout, http://manu.sporny.org/2011/web-payments-comparison/

Pelle Braendgaard, OpenTransact the payment standard where everything is out of scope,
http://stakeventures.com/articles/2011/12/21/opentransact-the-payment-standard-where-everything-is-out-of-scope

### OpenTransactions 

http://opentransactions.org/

(from: https://en.bitcoin.it/wiki/Open_Transactions)

"A financial crypto and digital cash software library."

Features:

* Centralized transaction system
* untraceable anonymous (versus pseudonymous) transactions
* no latency (instant finality of settlement / no risk of double spending)
* "Untraceable Digital Cash (real blinded tokens)" 
* "Anyone An Issuer (Ricardian-style Contracts)" 
* "Bearer-only, Fully-Anonymous (when used cash-only)" 
* "Pseudonymous User Accounts (user account == PGP key)" 
* "No Account History (asset account == the last receipt)" 
* "Many Financial Instruments (cheques, cash, vouchers, invoices...)" 
* "Basket Currencies (10 "baskets" == 5 gold, 3 silver)"  
* "Markets with Trades (stop, fill-or-kill, limit orders...)" 
* "Payment Plans"
* "Moneychanger (Qt-based desktop client)"

For Developers:

API (http://opentransactions.org/wiki/index.php?title=API)

### Loom 
![https://loom.cc/help](https://loom.cc/help)

"Loom is a system which enables people to transfer ownership of any kind of asset privately and at will."

### Magic Money 
![http://www.csee.umbc.edu/~woodcock/cmsc482/proj1/magmoney.html](http://www.csee.umbc.edu/~woodcock/cmsc482/proj1/magmoney.html)

"Magic Money is a publicly available digital cash system, using PGP, the Chaum protocols for blind signatures, and the email system to offer an on-line transaction system."

### Opencoin 
![http://opencoin.org/](http://opencoin.org/)

"The opencoin project is about "digital cash". We develop a protocol to use the original idea of electronic cash in daily life. For this we also develop a system consisting of minting software, wallet software and everything that is necessary to have a system for anonymous electronic transactions."

### Public Key Transaction Processor 
![https://www.facebook.com/publickeytransaction](https://www.facebook.com/publickeytransaction)

### Ricardo 
![http://wiki.dgcmagazine.com/index.php?title=Ricardo](http://wiki.dgcmagazine.com/index.php?title=Ricardo)

"Ricardo is an architecture for Internet payment systems originally developed by Ian Grigg and Gary Howland of Systemics, Inc. in 1995, and has continued under development by Ian Grigg through 2013. The underlying design goal of Ricardo as a payment system was to support financial trading, the toughest of all Internet payment scenarios."

### Truledger 
![http://truledger.com/]([http://truledger.com/)

"Truledger is an anonymous, digitally-signed general ledger and trading system."

### Voucher-Safe 
![http://www.voucher-safe.com/index.cfm](http://www.voucher-safe.com/index.cfm)

### Micro Payment Transfer Protocol (MPTP) Version 0.1 ==
![http://www.w3.org/TR/WD-mptp](http://www.w3.org/TR/WD-mptp)

"This is a W3C Working Draft for review by W3C members and other interested parties."

"A protocol for transfer of payments through the services of a common broker is described."

### Common Markup for micropayment per-fee links 
![http://www.w3.org/TR/Micropayment-Markup/](http://www.w3.org/TR/Micropayment-Markup/)

"This specification provides an extensible way to embed in a Web page all the information necessary to initialize a micropayment (amounts and currencies, payment systems, etc). This embedding allows different micropayment electronic wallets to coexist in a interoperable manner."


## Other Use Cases
Here are some other use cases not detailed in the above examples.
