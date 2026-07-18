# Vultr Payment Methods Complete Guide: Which Cards, Crypto, PayPal, Alipay Options Work? How to Pay Without Card Declines or Hidden Charges? (Includes Full Plan Pricing & $300 Free Credit Tips)

If you've ever tried to spin up a cloud server only to have your card declined three times in a row, you already know why people search for "vultr payment methods" more often than you'd expect. It's not a glamorous topic. But it's the kind of thing that decides whether your project ships tonight or stalls until your bank opens on Monday.

This guide walks through every payment option Vultr currently accepts, what each one is actually good for, where the small print hides, and how the billing model works once your money is in. Along the way we'll also lay out the full Vultr plan lineup so you can pick a payment method that fits the workload you're paying for.

## Why Vultr Payment Methods Matter More Than You Think

Vultr runs 33 cloud data center regions and bills in US dollars worldwide. The platform accepts a wider mix of payment rails than most of its competitors — credit cards, PayPal, Alipay, UnionPay, nine different cryptocurrencies through BitPay, wire transfer, ACH, and gift codes. That breadth isn't an accident. Vultr's user base leans international: developers in São Paulo, indie hackers in Shenzhen, fintech teams in Frankfurt, and crypto-native founders who would rather not touch a bank at all.

The catch is that "accepts" doesn't always mean "works smoothly for you." PayPal needs a backup funding source, crypto settlements can take a few minutes to confirm, Alipay requires a Chinese account, and card declines often come down to your bank's fraud rules — not Vultr. Knowing the quirks ahead of time saves you a support ticket and a half-day of waiting.

👉 [Start with the official signup page and claim your new account credit here](https://www.vultr.com/?ref=9738262-9J).

## The Full List of Accepted Vultr Payment Methods

Pulled directly from Vultr's billing documentation, here's what's currently supported.

### Credit and Debit Cards

Vultr accepts five major card networks:

- **Visa**
- **Mastercard**
- **American Express**
- **Discover**
- **JCB**

Debit cards carrying any of these network logos work too. When you first link a card, you'll see a small temporary authorization hold — that's a validation check, not a charge, and it releases on its own within a few days based on your bank's policy.

The most common reason a card gets declined on Vultr isn't a Vultr problem. It's your bank's fraud system flagging an international USD charge. If that happens, calling your bank to authorize the transaction usually fixes it on the next attempt. You can also fall back to PayPal or crypto to get around a stubborn card issuer.

### Cryptocurrency via BitPay

This is where Vultr stands out from most mainstream cloud providers. Through BitPay, the platform accepts nine different digital assets:

- **Bitcoin (BTC)**
- **Bitcoin Cash (BCH)**
- **Ethereum (ETH)**
- **Dogecoin (DOGE)**
- **Paxos Standard (PAX)**
- **Binance USD (BUSD)**
- **Litecoin (LTC)**
- **USD Coin (USDC)**
- **Gemini Dollar (GUSD)**

The flow is straightforward. At checkout you select BitPay, connect your preferred wallet (BitPay supports over 100 wallets including Exodus, MetaMask, Electrum, Trust, and Coinbase), pick your coin, and either scan the QR code or paste the receiving address manually. Settlement typically takes a few minutes depending on network congestion.

For users who care about privacy or who operate in regions with restricted card access, crypto is the path of least resistance. Stablecoins like USDC, BUSD, PAX, and GUSD are especially handy because they avoid the price volatility of BTC or ETH while still letting you settle without a bank.

### Third-Party Payment Platforms

Three major third-party rails are supported:

- **PayPal** — works globally, with regional add-ons like Giropay and bank transfers in some markets. Note that PayPal requires a backup funding source (a linked card or bank account) before it will activate a billing agreement with Vultr. Without that backup, the PayPal option simply won't go through.
- **Alipay** — the dominant wallet in mainland China. Useful if you have a Chinese Alipay account; less useful otherwise, since you need a local Chinese account to use it.
- **UnionPay** — China's card network. Accepts both debit and credit UnionPay cards, which opens Vultr up to a large segment of users who don't carry Visa or Mastercard.

### Wire Transfer and ACH

For larger accounts — agencies, enterprises, anyone running enough infrastructure that card limits become a problem — Vultr accepts wire transfer and ACH. The receiving account is held by The Constant Company, LLC (Vultr's parent) at JP Morgan Chase, with routing number 021000021 and account number 119932835. Wire transfers typically take 3–5 business days to land. The SWIFT code for international wires is CHASUS33.

You'll want to include your account email in the wire memo. Without it, Vultr's accounts team has to manually match the deposit to your account, which can drag out the timeline.

### Gift Codes and Promo Codes

Vultr also lets you redeem gift codes and promo codes through the **Gift Code** section of the billing portal. Promo credits expire, and you'll need to link a valid credit card or PayPal to register for services and unlock promotions. The system enforces one promo per user.

## Current Vultr Promotions Worth Knowing

Vultr is running several new-customer offers simultaneously. They can't be combined, but each one is generous enough on its own to make the signup worthwhile.

- **$300 free credit** — the headline offer, redeemable with code **FLY300VULTR** on signup. Credit applies to select products and is valid for 30 days.
- **$250 free credit** — a slightly smaller alternative offer.
- **$200 free credit** — another entry-level option.
- **Double your deposit** — Vultr matches your first deposit dollar for dollar, up to $100, when you open a new account.

All four require a new account, and all four require linking a valid payment method to be eligible. The promotional credit applies to select products only.

👉 [Activate the $300 free credit through this signup link](https://www.vultr.com/?ref=9738262-9J).

## How Vultr Billing Actually Works

Once your money is in, the billing model is worth understanding because it affects how fast you burn through credit.

### Hourly Billing With a Monthly Cap

Every server on your account is billed hourly, and the hourly rate is the monthly rate divided by 672 hours (28 days). If a server stays online for more than 672 hours in a calendar month, you only pay the monthly cap — never more. Invoices are generated on the 1st of each month.

One nuance: if you upgrade an instance mid-month, you'll see two line items on that month's invoice — one for the old plan, one for the new — and the total billed hours can exceed 672 because both plans were running during the same calendar month.

### Stopped Instances Still Cost Money

This trips people up. A stopped instance keeps reserving its RAM, SSD, IPs, and vCPU, so it keeps accruing charges until you destroy it. If you want to stop paying for a server, the only option is the **DESTROY** button in the customer portal. Snapshotting first is a good idea if you might want it back.

### USD Only, No Local Currency

Vultr bills exclusively in US dollars worldwide. This keeps pricing consistent across regions and avoids exchange-rate drift, but it means international users will see FX conversions on their card or PayPal statement.

### Tax Adds a Line Item

Prices on the website don't include tax. Vultr collects VAT, consumption tax, or sales tax in a long list of countries — typically 10–20%, with some markets like Norway and Ukraine hitting 20–25%. The tax location is based on your account address, which initially mirrors your primary payment method's address at signup. If you have a valid tax exemption, you can submit your Taxpayer Registration Certificate via support ticket.

### Bandwidth Quotas

Each account gets 2 TB of free outbound bandwidth per month, with no carryover. Instance bandwidth accrues hourly based on the plan's monthly cap. Overage is charged at **$0.01 per GB** worldwide. Inbound traffic is free.

### Add-On Costs to Watch

A few extras that quietly add to your bill:

- **Automatic backups** — 20% higher base fee on the instance
- **Stored snapshots** — $0.05 per GB per month
- **DDoS Protection** — $10 per month per instance, adds 10 Gbps of mitigation
- **Additional IPv4 addresses** — up to two extra per instance for an added fee

## Setting Up Your Default Payment Method

When you add more than one payment method to your account, the most recent one becomes the default and gets charged automatically each billing cycle. Older methods are kept as backups. You can't delete the default method — you have to add a new one first to demote it.

If you'd rather pay manually, you can preload funds into your account balance in advance. Vultr's system will not auto-charge in that case; it draws from your prepaid balance until it runs dry.

To manage payment methods, head to the **Billing** section inside the Vultr Console. The same screen shows your account limits, which increase over time as you build a credible usage history. If you need a higher limit sooner, open a support ticket explaining your use case.

## The Complete Vultr Plan Lineup

Picking a payment method is half the equation. The other half is knowing what you're actually paying for. Below is the full plan grid currently shown on Vultr's pricing page, grouped by product family. Prices are monthly with the hourly rate in parentheses. The hourly rate is the monthly rate divided by 672.

### Cloud Compute — Regular Performance

Powered by previous-generation Intel CPUs and standard SSD. Best for low-traffic sites, blogs, dev/test environments.

| vCPU | Memory | Bandwidth | Storage | Monthly | Hourly | Link |
|------|--------|-----------|---------|---------|--------|------|
| 1 | 0.5 GB | 0.50 TB | 10 GB | $2.50 (IPv6 only) | $0.004 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 1 | 0.5 GB | 0.50 TB | 10 GB | $3.50 | $0.005 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 1 | 1 GB | 1.00 TB | 25 GB | $5 | $0.007 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 1 | 2 GB | 2.00 TB | 55 GB | $10 | $0.015 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 2 | 2 GB | 3.00 TB | 65 GB | $15 | $0.022 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 2 | 4 GB | 3.00 TB | 80 GB | $20 | $0.030 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 4 | 8 GB | 4.00 TB | 160 GB | $40 | $0.060 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 6 | 16 GB | 5.00 TB | 320 GB | $80 | $0.119 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 8 | 32 GB | 6.00 TB | 640 GB | $160 | $0.238 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 16 | 64 GB | 10.00 TB | 1280 GB | $320 | $0.476 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 24 | 96 GB | 15.00 TB | 1600 GB | $640 | $0.952 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |

### Cloud Compute — High Performance (AMD EPYC / Intel Xeon + NVMe)

The newer-generation shared-CPU tier. Noticeably faster than Regular Performance for roughly the same money on smaller plans.

| vCPU | Memory | Bandwidth | Storage | Monthly | Hourly | Link |
|------|--------|-----------|---------|---------|--------|------|
| 1 | 1 GB | 2.00 TB | 25 GB | $6 | $0.009 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 1 | 2 GB | 3.00 TB | 50 GB | $12 | $0.018 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 2 | 2 GB | 4.00 TB | 60 GB | $18 | $0.027 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 2 | 4 GB | 5.00 TB | 100 GB | $24 | $0.036 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 4 | 8 GB | 6.00 TB | 180 GB | $48 | $0.071 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 4 | 12 GB | 7.00 TB | 260 GB | $72 | $0.107 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 8 | 16 GB | 8.00 TB | 350 GB | $96 | $0.143 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |
| 12 | 24 GB | 12.00 TB | 500 GB | $144 | $0.214 |  [Deploy](https://www.vultr.com/products/cloud-compute/?ref=9738262-9J) |

### Cloud Compute — High Frequency (3GHz+ Intel Xeon + NVMe)

Built for latency-sensitive workloads where single-thread speed matters more than core count. Same price ladder as High Performance but with faster per-core clock speeds.

| vCPU | Memory | Bandwidth | Storage | Monthly | Hourly | Link |
|------|--------|-----------|---------|---------|--------|------|
| 1 | 1 GB | 1.00 TB | 32 GB | $6 | $0.009 |  [Deploy](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |
| 1 | 2 GB | 2.00 TB | 64 GB | $12 | $0.018 |  [Deploy](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |
| 2 | 2 GB | 3.00 TB | 80 GB | $18 | $0.027 |  [Deploy](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |
| 2 | 4 GB | 3.00 TB | 128 GB | $24 | $0.036 |  [Deploy](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |
| 3 | 8 GB | 4.00 TB | 256 GB | $48 | $0.071 |  [Deploy](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |
| 4 | 16 GB | 5.00 TB | 384 GB | $96 | $0.143 |  [Deploy](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |
| 6 | 24 GB | 6.00 TB | 448 GB | $144 | $0.214 |  [Deploy](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |
| 8 | 32 GB | 7.00 TB | 512 GB | $192 | $0.286 |  [Deploy](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |
| 12 | 48 GB | 8.00 TB | 768 GB | $256 | $0.381 |  [Deploy](https://www.vultr.com/products/high-frequency-compute/?ref=9738262-9J) |

### Optimized Cloud Compute — General Purpose

Dedicated AMD EPYC vCPUs. No noisy neighbors. The sweet spot for production web apps, e-commerce, and game servers.

| vCPU | Memory | Bandwidth | Storage | Monthly | Hourly | Link |
|------|--------|-----------|---------|---------|--------|------|
| 1 | 4 GB | 4.00 TB | 30 GB | $30 | $0.045 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 | 8 GB | 5.00 TB | 50 GB | $60 | $0.089 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 4 | 16 GB | 6.00 TB | 80 GB | $120 | $0.179 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 8 | 32 GB | 7.00 TB | 160 GB | $240 | $0.357 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 16 | 64 GB | 8.00 TB | 320 GB | $480 | $0.714 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 24 | 96 GB | 9.00 TB | 480 GB | $720 | $1.071 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 32 | 128 GB | 9.00 TB | 640 GB | $960 | $1.429 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 40 | 160 GB | 10.00 TB | 768 GB | $1,200 | $1.786 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 64 | 192 GB | 11.00 TB | 960 GB | $1,920 | $2.857 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 96 | 256 GB | 12.00 TB | 1280 GB | $3,840 | $5.714 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |

### Optimized Cloud Compute — CPU Optimized

More CPU per dollar than RAM or storage. Built for video encoding, CI/CD, batch processing, HPC, analytics.

| vCPU | Memory | Bandwidth | Storage | Monthly | Hourly | Link |
|------|--------|-----------|---------|---------|--------|------|
| 1 | 2 GB | 4.00 TB | 25 GB | $28 | $0.042 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 | 4 GB | 5.00 TB | 50 GB | $40 | $0.060 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 | 4 GB | 5.00 TB | 75 GB | $45 | $0.067 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 4 | 8 GB | 6.00 TB | 75 GB | $80 | $0.119 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 4 | 8 GB | 6.00 TB | 150 GB | $90 | $0.134 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 8 | 16 GB | 7.00 TB | 150 GB | $160 | $0.238 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 8 | 16 GB | 7.00 TB | 300 GB | $180 | $0.268 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 16 | 32 GB | 8.00 TB | 300 GB | $320 | $0.476 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 16 | 32 GB | 8.00 TB | 500 GB | $360 | $0.536 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 32 | 64 GB | 9.00 TB | 500 GB | $640 | $0.952 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 32 | 64 GB | 10.00 TB | 1000 GB | $720 | $1.071 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |

### Optimized Cloud Compute — Memory Optimized

High RAM-to-CPU ratio. Built for MySQL, Memcached, in-memory caches, real-time analytics.

| vCPU | Memory | Bandwidth | Storage | Monthly | Hourly | Link |
|------|--------|-----------|---------|---------|--------|------|
| 1 | 8 GB | 5.00 TB | 50 GB | $40 | $0.060 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 | 16 GB | 6.00 TB | 100 GB | $80 | $0.119 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 | 16 GB | 6.00 TB | 200 GB | $100 | $0.149 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 | 16 GB | 6.00 TB | 400 GB | $125 | $0.186 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 4 | 32 GB | 8.00 TB | 200 GB | $160 | $0.238 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 4 | 32 GB | 8.00 TB | 400 GB | $195 | $0.290 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 4 | 32 GB | 8.00 TB | 800 GB | $250 | $0.372 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 8 | 64 GB | 9.00 TB | 400 GB | $320 | $0.476 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 8 | 64 GB | 9.00 TB | 800 GB | $390 | $0.580 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 8 | 64 GB | 9.00 TB | 1600 GB | $500 | $0.744 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 16 | 128 GB | 10.00 TB | 800 GB | $640 | $0.952 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 16 | 128 GB | 10.00 TB | 1600 GB | $785 | $1.168 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 16 | 128 GB | 10.00 TB | 3200 GB | $1,000 | $1.488 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 24 | 192 GB | 11.00 TB | 1200 GB | $960 | $1.429 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 24 | 192 GB | 11.00 TB | 2400 GB | $1,175 | $1.749 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 24 | 192 GB | 11.00 TB | 4800 GB | $1,500 | $2.232 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 32 | 256 GB | 12.00 TB | 1600 GB | $1,280 | $1.905 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 32 | 256 GB | 12.00 TB | 3200 GB | $1,565 | $2.329 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |

### Optimized Cloud Compute — Storage Optimized

Heavy NVMe SSD allocation. Built for Cassandra, MongoDB, OLTP workloads.

| vCPU | Memory | Bandwidth | Storage | Monthly | Hourly | Link |
|------|--------|-----------|---------|---------|--------|------|
| 1 | 8 GB | 4.00 TB | 150 GB | $75 | $0.112 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 | 16 GB | 6.00 TB | 320 GB | $125 | $0.186 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 | 16 GB | 6.00 TB | 480 GB | $155 | $0.231 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 4 | 32 GB | 7.00 TB | 640 GB | $250 | $0.372 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 4 | 32 GB | 7.00 TB | 960 GB | $310 | $0.461 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 8 | 64 GB | 8.00 TB | 1280 GB | $500 | $0.744 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 8 | 64 GB | 8.00 TB | 1920 GB | $620 | $0.923 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 16 | 128 GB | 9.00 TB | 2560 GB | $1,000 | $1.488 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 16 | 128 GB | 9.00 TB | 3840 GB | $1,240 | $1.845 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 24 | 192 GB | 10.00 TB | 3840 GB | $1,500 | $2.232 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 24 | 192 GB | 10.00 TB | 5760 GB | $1,850 | $2.753 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 32 | 256 GB | 12.00 TB | 5760 GB | $2,000 | $2.976 |  [Deploy](https://www.vultr.com/pricing/?ref=9738262-9J) |

### Cloud GPU — NVIDIA GH200 and H100

For AI training, large-scale inference, and HPC. Both plans below are priced on a 36-month, 100% prepaid reserved instance contract. Hourly figures assume 730 hours per month.

| GPU Model | GPU Count | GPU RAM | vCPU | RAM | Storage | Bandwidth | Monthly | Link |
|-----------|-----------|---------|------|-----|---------|-----------|---------|------|
| NVIDIA GH200 | 1 | 96 GB | 72 | 480 GB | 4800 GB | 25 TB | $2,913 |  [Inquire](https://www.vultr.com/products/gpu/?ref=9738262-9J) |
| NVIDIA H100 | 8 | 640 GB | 224 | 2048 GB | 32640 GB | 15 TB | $13,432 |  [Inquire](https://www.vultr.com/products/gpu/?ref=9738262-9J) |

For additional GPU contract durations and payment options on these higher-tier plans, contact Vultr directly through the GPU product page.

## Choosing the Right Payment Method for Your Use Case

The best payment method depends less on which is "best" in the abstract and more on what you're trying to do.

**For solo developers and side projects**, credit card is the path of least friction. Link a Visa or Mastercard, set it as default, and let it auto-charge. Just keep an eye on the small authorization hold when you first sign up — it's normal and refunds itself.

**For users in mainland China**, Alipay and UnionPay avoid the international-USD-charge friction that often gets Visa and Mastercard declined by domestic banks.

**For privacy-conscious users or anyone in a country with card restrictions**, crypto via BitPay is the cleanest workaround. USDC, BUSD, and the other stablecoins let you settle without exposing yourself to crypto volatility.

**For agency or enterprise accounts running enough infrastructure to hit card limits**, wire transfer and ACH unlock larger funding rounds in a single move. Just build in the 3–5 day settlement buffer.

**For new users testing the platform**, claim the $300 promo credit first. Link a card or PayPal to qualify, then use the credit to experiment across multiple instance types before committing real money.

## Common Payment Pitfalls and How to Avoid Them

A handful of issues come up over and over in user feedback.

**Card declines despite valid funds.** Usually a fraud-flag from your bank, not Vultr. Call the bank, authorize the charge, retry. Failing that, switch to PayPal with the same card as a backup funding source.

**PayPal refusing to activate the billing agreement.** PayPal requires a linked backup funding source (card or bank account). Add one in your PayPal account settings first.

**Charges continuing after stopping an instance.** Stopped instances still reserve resources. Use the **DESTROY** button — and snapshot first if you might want the server back.

**Unexpected invoice totals after upgrading mid-month.** Each plan runs as its own line item during the month you upgrade. Total billed hours can exceed 672 in that case. Plan upgrades for the start of a billing cycle if you want clean invoices.

**Promo credit not applying.** Promo codes require a linked payment method and a fresh account. Redeem the code under the **Gift Code** section of the billing portal, not at signup checkout.

## Final Thoughts

The "vultr payment methods" question looks simple on the surface — what cards work, what crypto is supported, whether PayPal is on the list. The useful answer runs deeper. The right payment method is the one that matches your region, your bank's quirks, your accounting workflow, and the size of the bill you're about to run up.

Vultr's payment flexibility is genuinely one of its competitive advantages. Most cloud providers lean heavily on cards and PayPal. Vultr covers cards, PayPal, Alipay, UnionPay, nine cryptos via BitPay, wire transfer, ACH, and gift codes. That breadth means there's almost always a path that works for your situation — whether you're a developer in Lagos trying to get around a card restriction, an agency owner in Berlin running up against card limits, or a crypto-native founder who'd rather not touch a bank at all.

Pair the right payment method with the right plan and the $300 new-account credit, and you can run real production workloads for the first month without paying a cent out of pocket. That's a hard combination to beat.

👉 [Open a Vultr account, link your preferred payment method, and claim the $300 free credit through this signup link](https://www.vultr.com/?ref=9738262-9J).
