# AstroPay (astropay)

AstroPay is a Uruguay-founded fintech and electronic money institution offering a multicurrency wallet, virtual and physical AstroCards, FX, and cross-border money transfers for consumers across Latin America, plus a business platform that lets merchants accept payments, issue cards, manage payroll, and pay out to wallets and bank accounts. AstroPay is regulated as an EMI in the UK, Denmark, Isle of Man, and Brazil, and operates across Argentina, Brazil, Chile, Mexico, Peru, Colombia, Uruguay, and additional global corridors with support for ARS, BRL, CLP, COP, EUR, GBP, MXN, PEN, USD, USDT, and UYU. For developers, AstroPay exposes a comprehensive REST platform through [developers.astropay.com](https://developers.astropay.com) covering payments, payouts, PIX, issued cards, savings, scheme transfers, user account management, tokenization, settlements, transaction reporting, hosted/embedded Checkout, QR-code POS, Wallet-on-File, Cashouts, and signed webhook callbacks.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/astropay/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Payments, Payment Processing, Payouts, Wallet, Digital Wallet, Multicurrency, Cards, Card Issuing, PIX, LATAM, Latin America, Brazil, Argentina, Mexico, Chile, Peru, Colombia, Uruguay, Fintech, Foreign Exchange, Cross-Border Payments, Checkout, QR Payments, Tokenization, Embedded Finance, Money Transfer, Remittance, Gaming Payments, Marketplace Payments, Payroll

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## Geographic Coverage

| Region | Primary methods |
|---|---|
| Brazil | PIX, Boleto, AstroPay wallet, local card processing |
| Argentina | Bank transfers, AstroPay wallet, local withdrawals |
| Mexico | SPEI, OXXO, AstroPay wallet |
| Chile | Local bank rails, AstroPay wallet |
| Peru | Local bank rails, AstroPay wallet |
| Colombia | AstroPay wallet, FX |
| Uruguay | AstroPay wallet (home market), local rails |
| India | Direct Withdrawal local rails |
| Global | Multicurrency wallet, AstroCard, USDT, FX |

## APIs

### AstroPay Payments API
Core Payments API on the AstroPay platform for creating, retrieving, and managing payment transactions across the AstroPay wallet network and supported local payment methods. Backs merchant pay-in flows initiated from Checkout or built directly server-to-server.

**Human URL:** [https://developers.astropay.com/docs/platform/payments](https://developers.astropay.com/docs/platform/payments)

### AstroPay Payout API
Send funds to AstroPay wallets, bank accounts, and other supported destinations. Used for marketplace seller payouts, gaming withdrawals, payroll disbursements, and B2B settlements across LatAm corridors.

**Human URL:** [https://developers.astropay.com/docs/platform/payout](https://developers.astropay.com/docs/platform/payout)

### AstroPay PIX API
PIX integration for Brazil's instant payment rail. Create PIX charges, receive PIX payments, and issue PIX payouts backed by AstroPay's local Brazilian licensing.

**Human URL:** [https://developers.astropay.com/docs/platform/pix](https://developers.astropay.com/docs/platform/pix)

### AstroPay Cards Management API
Programmatic issuance and lifecycle management of AstroPay virtual and physical prepaid cards. Used by businesses to issue branded cards to employees, contractors, marketplace participants, and end users.

**Human URL:** [https://developers.astropay.com/docs/platform/cards-management](https://developers.astropay.com/docs/platform/cards-management)

### AstroPay Users Management API
Create and manage platform users associated with a merchant or partner account, including KYC linkage and access control to AstroPay platform resources.

**Human URL:** [https://developers.astropay.com/docs/platform/users-management](https://developers.astropay.com/docs/platform/users-management)

### AstroPay User Account Management API
Manage the financial accounts attached to a platform user, including multicurrency balances, statements, and account settings.

**Human URL:** [https://developers.astropay.com/docs/platform/user-account-management](https://developers.astropay.com/docs/platform/user-account-management)

### AstroPay Scheme Transfers API
Move funds across AstroPay accounts and between schemes inside the AstroPay network — wallet-to-wallet transfers and internal book transfers.

**Human URL:** [https://developers.astropay.com/docs/platform/scheme-transfers](https://developers.astropay.com/docs/platform/scheme-transfers)

### AstroPay Savings Account API
Create and manage interest-bearing savings accounts attached to AstroPay platform users.

**Human URL:** [https://developers.astropay.com/docs/platform/savings-account](https://developers.astropay.com/docs/platform/savings-account)

### AstroPay Settlements API
Retrieve merchant settlement files, reconcile settled transactions, and download settlement reports.

**Human URL:** [https://developers.astropay.com/docs/platform/settlements](https://developers.astropay.com/docs/platform/settlements)

### AstroPay Tokenizer API
PCI-compliant card data collection. Cards are tokenized client-side via the iOS and Android Tokenizer SDKs and the resulting token is used server-to-server, reducing PCI scope for merchants.

**Human URL:** [https://developers.astropay.com/docs/platform/tokenizer/tokenizer-api](https://developers.astropay.com/docs/platform/tokenizer/tokenizer-api)

### AstroPay Partners Services API
For integrators and partner platforms to manage sub-merchants, services, and partner-scoped resources on the AstroPay platform.

**Human URL:** [https://developers.astropay.com/docs/platform/partners-services](https://developers.astropay.com/docs/platform/partners-services)

### AstroPay Direct Payment API
Local pay-ins via the AstroPay payment processing rail. Supports Brazil and Mexico with local payment methods (PIX, Boleto, OXXO, SPEI) for merchants integrating without the AstroPay wallet.

**Human URL:** [https://developers.astropay.com/docs/payment-processing/direct-payment/getting-started](https://developers.astropay.com/docs/payment-processing/direct-payment/getting-started)

### AstroPay Direct Withdrawal API
Local payouts and withdrawals into bank accounts across Argentina, Brazil, Chile, India, and Peru. Used by marketplaces, gaming operators, and other payout-heavy businesses.

**Human URL:** [https://developers.astropay.com/docs/payment-processing/direct-withdrawal/getting-started](https://developers.astropay.com/docs/payment-processing/direct-withdrawal/getting-started)

### AstroPay Checkout API
Hosted and embedded payment acceptance flow with offsite (redirect), embedded (iframe / web component), and React Native integration modes. Themed, internationalized, with full payment-lifecycle management (create, callback/status, refund).

**Human URL:** [https://developers.astropay.com/docs/accept-astropay/checkout/overview](https://developers.astropay.com/docs/accept-astropay/checkout/overview)

### AstroPay QR Payments API
In-person and point-of-sale acceptance. Payment Code API (create, update, status, exchange-rate) and POS API (create, get, search) for issuing QR codes that customers scan with the AstroPay wallet.

**Human URL:** [https://developers.astropay.com/docs/accept-astropay/qr-payments/introduction](https://developers.astropay.com/docs/accept-astropay/qr-payments/introduction)

### AstroPay Wallet-on-File API
Link an AstroPay wallet to a merchant account so funds can be pulled in one-click for recurring purchases. Covers account linking (incl. singular generator), partner branding, funds-pulling, transaction status, refunds, and webhooks.

**Human URL:** [https://developers.astropay.com/docs/accept-astropay/wallet-on-file/getting-started](https://developers.astropay.com/docs/accept-astropay/wallet-on-file/getting-started)

### AstroPay Cashouts API
Wallet Payouts / Cashouts v1 — send payouts to AstroPay wallet holders, including closed-loop transactions back to the originating wallet. Supports merchant onboarding, status checks, and callbacks.

**Human URL:** [https://developers.astropay.com/docs/accept-astropay/wallet-payouts/cashouts-v1/getting-started](https://developers.astropay.com/docs/accept-astropay/wallet-payouts/cashouts-v1/getting-started)

### AstroPay Transaction Report API
Merchant balance and transaction export endpoints for reconciliation, accounting, and reporting across both the Accept AstroPay and Payment Processing surfaces.

**Human URL:** [https://developers.astropay.com/docs/payment-processing/transaction-report/introduction](https://developers.astropay.com/docs/payment-processing/transaction-report/introduction)

### AstroPay Webhooks
Platform-wide signed webhook callbacks for asynchronous payment, payout, card, wallet-on-file, and account events.

**Human URL:** [https://developers.astropay.com/docs/platform/callbacks/webhooks](https://developers.astropay.com/docs/platform/callbacks/webhooks)

### AstroPay E-Commerce Plugins
Pre-built integrations that drop AstroPay acceptance into popular e-commerce platforms without custom development. Shopify is the first supported platform.

**Human URL:** [https://developers.astropay.com/docs/accept-astropay/ecommerce-plugins/introduction](https://developers.astropay.com/docs/accept-astropay/ecommerce-plugins/introduction)

## Common Properties

- [Website — astropay.com](https://www.astropay.com)
- [Portal — Developer Portal](https://developers.astropay.com)
- [Documentation — Platform Introduction](https://developers.astropay.com/docs/platform/introduction)
- [GettingStarted](https://developers.astropay.com/docs/platform/introduction)
- [Authentication](https://developers.astropay.com/docs/platform/authentication)
- [Errors](https://developers.astropay.com/docs/platform/errors-codes)
- [Webhooks](https://developers.astropay.com/docs/platform/callbacks/webhooks)
- [StatusPage](https://status.astropay.com)
- [Support — Business](https://business-support.astropay.com/)
- [Help — App](https://app.astropay.com/help)
- [Contact](https://developers.astropay.com/contact/)
- [SignUp — Business](https://business.astropay.com)
- [Personal](https://www.astropay.com/personal)
- [Business](https://www.astropay.com/business)
- [Blog](https://www.astropay.com/blog)
- [Careers](https://astropay.careers.hibob.com)
- [GitHubOrganization](https://github.com/astropay)
- [LinkedIn](https://www.linkedin.com/company/astropay)
- [Twitter](https://twitter.com/astropayglobal)
- [SDK — iOS Tokenizer](https://developers.astropay.com/docs/platform/tokenizer/ios-sdk/getting-started)
- [SDK — Android Tokenizer](https://developers.astropay.com/docs/platform/tokenizer/android-sdk/getting-started)
- [SDK — React Native Payments Library](https://developers.astropay.com/docs/accept-astropay/checkout/private/payments-lib-react-native/getting-started)
- [Plugins — Shopify](https://developers.astropay.com/docs/accept-astropay/ecommerce-plugins/shopify)

## Solutions

- Gaming and iGaming payments — deposits and withdrawals via local methods and AstroPay wallet
- Online marketplaces — split payouts to LatAm sellers in local currency
- Cross-border payroll — pay remote workers and contractors into AstroPay wallets
- Travel and ticketing — accept AstroPay across LatAm travelers
- Cryptocurrency on/off-ramps via USDT support
- E-commerce checkout — Shopify and custom storefronts
- Streaming and subscriptions — recurring billing through Wallet-on-File
- Remittance — bank deposits and wallet-to-wallet transfers
- Financial services and embedded finance for partner platforms

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
