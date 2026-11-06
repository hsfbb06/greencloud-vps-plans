# greencloud vps plans: current pricing for every product line, the limits most reviews skip, and how to pick the right one

GreenCloud's plans are spread across so many pages that most people searching "greencloud vps plans" just want one answer: what does it actually cost, and which line is worth buying. Here's the short version. GreenCloud currently sells five main product lines: monthly SSD KVM VPS from **$6/month**, monthly Ryzen KVM VPS from **$6/month**, annual Budget KVM Sale plans from **$15/year**, annual Storage KVM from **$25/year**, and Windows VPS from around **$8/month**. The catch is that the differences between these lines — traffic caps, refund rights, IPv6 allocation, and stock — matter more than the sticker price, and several of those details never make it into the comparison posts ranking on page one.

> **Quick pick**
> Most readers fit one of two profiles. If you want a refund window and monthly flexibility, the **SSDKVM-2 at $10/month** (1 core, 2 GB RAM, 15 GB SSD, 2 TB traffic) is the sensible entry point. If you're price-sensitive and know you'll keep the VPS for a year, the **Budget KVM Sale at $25/year** (2 cores, 4 GB RAM, 35 GB disk, 4 TB traffic) works out to about $2/month — but it's non-refundable and stock is limited. 👉 [Check GreenCloud's current plans and prices](https://greencloudvps.com/billing/aff.php?aff=6679)

## The full lineup of GreenCloud VPS plans

GreenCloud runs five VPS product lines plus dedicated servers, all on KVM virtualization and managed through the VirtFusion control panel. Every Linux VPS plan includes 1 free backup/snapshot, and the company claims 99.99% network and power uptime with a public status page you can check yourself. Official numbers list around 30 locations across 4 continents and 32 datacenters; a third-party audit in September 2026 counted 26 datacenters in 13 countries, including Tokyo, Singapore, Hong Kong, Frankfurt, Amsterdam, London-area, and a dozen US cities. Either way, the location count is genuinely large for a budget provider — it's the main reason people end up on their plans page in the first place.

Here's how the lines break down.

### SSD KVM VPS (monthly billing)

This is the standard budget line, sold on the green.cloud pricing page as five fixed tiers. All plans sit behind a 10Gbps port on SSD storage in RAID-10.

| Plan | CPU / RAM | Storage | Traffic | Price | Buy |
| --- | --- | --- | --- | --- | --- |
| SSDKVM-1 | 1 core / 1 GB | 15 GB SSD | 1.5 TB | $6/mo | [Get SSDKVM-1](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-2 | 1 core / 2 GB | 15 GB SSD | 2 TB | $10/mo | [Get SSDKVM-2](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-3 | 2 cores / 4 GB | 30 GB SSD | 4 TB | $20/mo | [Get SSDKVM-3](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-4 | 4 cores / 8 GB | 60 GB SSD | 8 TB | $40/mo | [Get SSDKVM-4](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-5 | 8 cores / 16 GB | 120 GB SSD | 12 TB | $80/mo | [Get SSDKVM-5](https://greencloudvps.com/billing/aff.php?aff=6679) |

One detail the pricing table itself mentions but most reviews skip: Asia-Pacific locations get roughly half the traffic. On the SSDKVM line, APAC allocations drop to 750 GB / 1 TB / 2 TB / 4 TB / 6 TB for tiers 1 through 5.

### Ryzen KVM VPS (monthly billing)

Same five-tier pricing structure, but with NVMe storage instead of SSD. The published tiers are $6 / $10 / $20 / $40 / $80 per month for 1 core/1 GB/15 GB, 1 core/2 GB/30 GB, 2 cores/4 GB/50 GB, 4 cores/8 GB/80 GB, and 8 cores/16 GB/150 GB respectively.

| Plan | CPU / RAM | Storage | Traffic | Price | Buy |
| --- | --- | --- | --- | --- | --- |
| RyzenKVM-1 | 1 core / 1 GB | 15 GB NVMe | 750 GB | $6/mo | [Get RyzenKVM-1](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-2 | 1 core / 2 GB | 30 GB NVMe | 1 TB | $10/mo | [Get RyzenKVM-2](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-3 | 2 cores / 4 GB | 50 GB NVMe | 2 TB | $20/mo | [Get RyzenKVM-3](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-4 | 4 cores / 8 GB | 80 GB NVMe | 4 TB | $40/mo | [Get RyzenKVM-4](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-5 | 8 cores / 16 GB | 150 GB NVMe | 6 TB | $80/mo | [Get RyzenKVM-5](https://greencloudvps.com/billing/aff.php?aff=6679) |

Location changes the deal here more than on the SSD line. US locations (Los Angeles, Chicago, Ogden, San Jose) and Amsterdam run 10Gbps ports with higher traffic caps — 1.5 TB to 12 TB depending on tier. Singapore and Hong Kong run 1Gbps ports with 750 GB to 6 TB. Stock also moves around: at the time of the most recent check, the entire Tokyo (IIJ) and Amsterdam Ryzen series showed zero available, while Singapore DC2 and Hong Kong DC2 had inventory. If you're buying specifically for an Asian location, check stock before planning anything around it.

### Budget KVM Sale (annual billing)

This is where the aggressive pricing lives. The sale page sells location-specific SKUs in three tiers, and the specs per tier are consistent even though the CPU and storage type vary by datacenter:

| Tier | CPU / RAM | Storage | Traffic | Price | Buy |
| --- | --- | --- | --- | --- | --- |
| Tier 1 | 1 core / 2 GB (+1 GB swap) | 20 GB SSD | 2 TB | $15/yr | [Check Tier 1 availability](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Tier 2 | 2 cores / 4 GB | 35 GB SSD or NVMe | 4 TB | $25/yr | [Check Tier 2 availability](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Tier 3 | 4 cores / 8 GB | 60 GB SSD or NVMe | 8 TB | $45/yr | [Check Tier 3 availability](https://greencloudvps.com/billing/aff.php?aff=6679) |

Depending on which datacenter you pick, the CPU is an EPYC Rome, EPYC Milan, or an older E5v4, with either NVMe or SSD in RAID-10. The page doesn't let you choose — you buy the specific location SKU that's in stock.

Two things to know before clicking order on any of these. Every Budget KVM Sale plan is marked **"No refund / Money back on this plan"** — the 7-day refund policy does not apply. And stock is genuinely limited per location; recent checks showed some locations with fewer than 10 units and others completely sold out, with Kansas City allocations getting a smaller /112 IPv6 block instead of the usual /64.

### Storage KVM VPS (annual billing)

For backup and archival workloads, this line swaps speed for capacity with HDD storage. Verified pricing works out to $25/year for 1 vCPU / 2 GB RAM / 500 GB HDD / 3 TB traffic, $45/year for 2 vCPU / 3 GB / 1 TB HDD / 6 TB, and $80/year for 4 vCPU / 6 GB / 2 TB HDD / 10 TB. CloudsPress currently ranks GreenCloud first out of 13 providers in its storage VPS category, which tracks with how few budget providers offer HDD-backed VPS at all. 👉 [See current Storage KVM pricing](https://greencloudvps.com/billing/aff.php?aff=6679)

### Windows VPS

GreenCloud also sells Windows VPS with unmetered traffic on 1Gbps ports, starting around $8/month for 1 core / 1 GB RAM / 25 GB SSD, scaling up through higher tiers at $12, $24, $32, and beyond. Windows licensing is the reason for the price jump over the Linux lines. If you need RDP for a small remote desktop or a Windows-specific app, this is the relevant line; for anything else, the KVM plans above are cheaper per resource.

## The limits most GreenCloud VPS reviews don't mention

These are the details buried in checkout pages and policy notes that actually affect ownership.

**Renewal prices are not published.** An independent audit in September 2026 checked all 17 plans listed on GreenCloud's pricing pages and found renewal prices published for exactly zero of them. The promo and monthly prices you see are what's listed; what you'll pay at renewal isn't. Budget for the possibility that year two costs more than year one, and screenshot your order terms when you buy.

**The 7-day refund has exceptions.** GreenCloud offers a 7-day refund policy for first-time customers, but it excludes dedicated servers, proxies, and — easy to miss — payments made with cryptocurrency. If a refund option matters to you, pay with PayPal or a card, and remember the Budget KVM Sale line is excluded from refunds entirely.

**IPv6 allocation varies by location.** Most locations hand you a /64 block. Kansas City Budget plans and the Singapore DC2 and Hong Kong DC2 Ryzen plans hand you a /112. A /64 is an effectively unlimited address space for a single VPS; a /112 caps you at 65,536 addresses. For typical use this changes nothing, but if your project provisions many IPv6 addresses (proxy pools, IPv6-only services), it's a real constraint.

**Upgrades are capped at 100%.** You can add resources at $3/month per 1 GB of RAM, per CPU core, or per 10 GB of SSD — but only up to double your plan's original spec. A 4 GB plan can grow to 8 GB, no further. If you expect to outgrow your plan, buying the next tier up usually beats stacking add-ons.

**Stock is location-dependent and shifts weekly.** Popular locations cycle between available and zero-inventory. Don't build a deployment plan around a specific datacenter without confirming it has units.

## Promotions: what's actually running

GreenCloud runs sales more often than most providers, and they follow recognizable patterns rather than one-off discounts:

- **Triennial double-up.** Buying or renewing Budget or Premium KVM plans on a 3-year billing cycle has repeatedly come with doubled disk and monthly traffic during Black Friday, anniversary, and mid-year sales.
- **Anniversary cashback.** The 13th birthday sale (October 2026) gave 13% back as account credit on purchases and renewals of $500 or more.
- **Flash-sale SKUs.** Numbered plans like the 2222 (2 cores / 2 GB / 22 GB NVMe / 2,222 GB traffic at $22/year) or 8888 UK ($88/year) appear and disappear across sale events. They're genuinely good value while they last, but they rotate.
- **Black Friday codes.** Past events have included codes taking 50% off Budget KVM VPS, though these are tied to specific sale windows and expire.

None of these require hunting for coupon sites — they're applied through the store itself or by opening a ticket, as with the cashback offers. 👉 [See what's currently on sale at GreenCloud](https://greencloudvps.com/billing/aff.php?aff=6679)

## Which GreenCloud VPS plan should you buy

Match the line to the job, not the other way around:

- **General-purpose server, want a safety net:** SSDKVM-2 at $10/month. The $6 tier's 1 GB RAM is workable for a lightweight proxy or DNS box but cramped for a web stack.
- **Cheapest usable VPS for a full year:** Budget KVM Sale $25/year tier, provided a location with stock suits your latency needs and you accept the no-refund terms.
- **Lowest latency to Asia:** Ryzen KVM in Singapore DC2 or Hong Kong DC2 — while accepting the 1Gbps port, reduced traffic, and /112 IPv6. Tokyo is the theoretically ideal location for Japan traffic but has been frequently out of stock.
- **Heavy traffic or bandwidth-bound work:** SSDKVM-4 or SSDKVM-5, or a US Ryzen location with the 10Gbps uplink and up to 12 TB monthly traffic.
- **Backups and file archives:** Storage KVM annual plans, where $45/year gets you 1 TB of HDD storage.
- **Windows applications:** the Windows VPS line from ~$8/month.

## FAQ

**Does GreenCloud publish renewal prices for its VPS plans?** No. As of the most recent audit of its pricing pages, none of the listed plans display a renewal rate, so first-term and renewal costs can differ.

**Can I get a refund on a GreenCloud VPS?** First-time customers have a 7-day refund window, excluding dedicated servers, proxies, crypto payments, and all Budget KVM Sale plans, which are explicitly non-refundable.

**What control panel and extras come with the plans?** All KVM plans use the VirtFusion control panel and include one free backup/snapshot. Reinstalls and power management are self-service.

**What payment methods does GreenCloud accept?** PayPal, credit cards, bank transfer, Alipay, UnionPay, and crypto (BTC, BCH, ETH, SOL, USDT). Note the crypto refund exclusion above.

**How is the support and uptime record?** GreenCloud claims 99.99% network and power uptime with a verifiable public status page, a 24/7 in-house support team, and an average ticket response of 9 minutes — those are official figures, so treat the uptime claim as a commitment you can check against the status page rather than an independent benchmark. For what it's worth, the company also holds LowEndTalk's "#1 Top Provider" and "#1 Most Stable Provider" badges as displayed on its own pricing page.

## Before you click order

Two quick checks will save you most GreenCloud regrets. First, confirm your chosen location actually has stock and gives you the IPv6 block you need — Kansas City and the Singapore/Hong Kong Ryzen plans are the /112 exceptions. Second, decide your refund posture up front: if there's any chance you'll want out within a week, stay on the monthly SSD or Ryzen lines and pay with PayPal or card, because the annual sale plans won't take it back.

If you've matched your use case to a line above, the next step is just checking today's inventory and pricing at your preferred location — 👉 [browse GreenCloud's full plan list here](https://greencloudvps.com/billing/aff.php?aff=6679) — since stock and sale SKUs are the two things on this page that change fastest.
