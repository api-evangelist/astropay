# AstroPay (astropay)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
