# megalayer vps: What $24.46/Year Actually Includes, Which Network Tier You Need, and When a Refund Is Possible (Plan and Price Tables)

The cheapest MegaLayer VPS you can verify right now is **$24.46 a year**: 1 vCPU, 1 GB RAM, 50 GB SSD, unmetered traffic, on a **10 Mbps** port in Hong Kong or a **30 Mbps** port in San Jose. That works out to about $2.04 a month, and what it buys is a small machine on a narrow port. A static site, a DNS node, a monitoring agent, a jump host or a test environment fits comfortably. A WordPress install with a stack of plugins will run, slowly. Anything serving video, large downloads or a busy database will not.

The rest of this is about choosing between the plans that actually exist: which prices are current and which are history, where the three bandwidth types differ, what a year really costs once the billing cycles are folded in, and the two clauses that decide whether your money comes back.

> **Quick pick.** Most people searching for megalayer vps want mainland-China-friendly routing on a small box, so take the **Hong Kong VPS Basic at $24.46/year** (1 core, 1 GB, 50 GB SSD, 10 Mbps unmetered, CN2/CMI/CU/HGC). If your users are in North America, or you simply want three times the port speed for the same money, take the **US VPS Entry at $24.46/year** with 30 Mbps. Singapore only makes sense if you specifically want the T3 facility and the standing 50% discount.
> 👉 [See the current plan list and live prices](https://account.lightlayer.net/?affid=74)

## MegaLayer VPS plans, with the date attached to every number

MegaLayer does not keep one tidy price page listing every plan. The figures below come from three different places: a live promo line on the company's own announcement feed, a standing Singapore discount, and a single official announcement from January 2021. Each is labelled, so you know which numbers you can order at today and which are reference only.

| Plan | vCPU / RAM | Storage | Port / traffic | Route | Price |
| --- | --- | --- | --- | --- | --- |
| HK VPS Basic | 1 / 1 GB | 50 GB SSD | 10 Mbps, unmetered | CN2 + CMI + CU + HGC | [ $24.46/yr](https://account.lightlayer.net/?affid=74) |
| HK VPS Standard | 2 / 2 GB | 50 GB SSD | 10 Mbps, unmetered | CN2 IEPL | [ Check price](https://account.lightlayer.net/?affid=74) |
| HK VPS Professional | 4 / 4 GB | 50 GB SSD | 20 Mbps, unmetered | Premium Network | [ Check price](https://account.lightlayer.net/?affid=74) |
| US VPS Entry (San Jose) | 1 / 1 GB | 50 GB SSD | 30 Mbps, unmetered | CN2 / International | [ $24.46/yr](https://account.lightlayer.net/?affid=74) |
| US VPS Standard | 2 / 2 GB | 50 GB SSD | 100 Mbps, unmetered | Multi-carrier | [ Check price](https://account.lightlayer.net/?affid=74) |
| US VPS Premium | 4 / 4 GB | 50 GB SSD | 200 Mbps, unmetered | Premium Network | [ Check price](https://account.lightlayer.net/?affid=74) |
| SG VPS Starter | 1 / 1 GB | 50 GB SSD | 10 Mbps, unmetered | Premium / International | [ 50% off, price at checkout](https://account.lightlayer.net/?affid=74) |
| SG VPS Business | 2 / 2 GB | 50 GB SSD | 10 Mbps, unmetered | Premium | [ 50% off, price at checkout](https://account.lightlayer.net/?affid=74) |
| SG VPS Enterprise | 4 / 4 GB | 50 GB SSD | 20 Mbps, unmetered | Multi-line BGP | [ 50% off, price at checkout](https://account.lightlayer.net/?affid=74) |
| Manila VPS (Jan 2021 list) | 2 / 2 GB up to 8 / 16 GB | 50–240 GB SSD | 10 Mbps Premium or 20 Mbps International, unmetered | CN2 IEPL / International | [ $24–$171/mo, ask for current](https://account.lightlayer.net/?affid=74) |

How to read that table:

- The two $24.46 rows are current. MegaLayer's own announcement feed carries the line "VPS $24.46 per year". The per-plan specs come from third-party plan write-ups, so confirm port speed and route on the order page before paying.
- "Check price" rows have no public figure. MegaLayer quotes them through sales tickets, which means you cannot comparison-shop them from a table.
- Singapore's 50% is described in plan write-ups as a continuing strategy rather than a first-month teaser, and the same discount extends 20% to Singapore dedicated servers. No public Singapore price is listed anywhere I could verify.
- The Manila row is from the official announcement dated **12 January 2021**: 2C/2 GB/50 GB at $24/month, rising through 2C/4 GB at $47, 4C/4 GB at $71, 4C/8 GB at $96, 8C/8 GB at $126 and 8C/16 GB/240 GB at $171, with the Premium 10 Mbps and International 20 Mbps variants priced identically. Treat it as a historical reference, not a current quote.

### The $713.41/yr "starting price" is a catalog error

Some directory sites advertise "21 MegaLayer VPS plans, from $713.41/yr". Open the table under that headline and there is not a single VPS in it. Every row is a dedicated server quoted in CNY per month, and $713.41 is just 399 CNY/month multiplied out to a year. That number is the annualised cost of an E3-1230 with 16 GB RAM in Singapore, not an entry point for a VPS. The real VPS floor is $24.46/year, and the gap between the two figures is roughly 29×. If you saw $713.41 quoted as a VPS price somewhere, that is where it came from.

The same caution applies to promo pages claiming dedicated servers "from 299/month". MegaLayer's own homepage sales block starts at $76.77 for an E3-1230 with 8 GB, and the 299 figure refers to a different machine class. Neither is a VPS starting price.

## Dedicated servers and multi-IP machines

Once you outgrow a 1 GB VPS, the jump is to a dedicated box. Two price lists circulate: USD figures from MegaLayer's live homepage sales block, and a CNY monthly list from a directory updated in October 2026. They do not cover identical configurations.

| Server | CPU / RAM | Storage | Bandwidth | IPs | Price |
| --- | --- | --- | --- | --- | --- |
| Entry dedicated, HK | E3-1230 / 8 GB | 1 TB HDD + 240 GB SSD | 10M Premium | 1 | [ $76.77/mo](https://account.lightlayer.net/?affid=74) |
| Performance dedicated, HK | E5-2660 / 16 GB | 1 TB HDD + 240 GB SSD | 10M Premium | 1 | [ $184.62/mo](https://account.lightlayer.net/?affid=74) |
| Multi-IP server, HK | E3-1230 / 8 GB | 1 TB HDD + 240 GB SSD | 10M Premium | multiple | [ $236/mo](https://account.lightlayer.net/?affid=74) |
| Multi-segment multi-IP, HK | 2× E5-2450 / 16 GB | 1 TB HDD + 240 GB SSD | 10M Premium | multiple | [ $279/mo](https://account.lightlayer.net/?affid=74) |
| Dedicated, Singapore | E3-1230 / 16 GB | 1 TB HDD + 240 GB SSD | 10M optimized / 20M international | 2 | [ from 399 CNY/mo](https://account.lightlayer.net/?affid=74) |
| Large multi-IP, HK | E3-1230 / 8 GB | 1 TB HDD + 240 GB SSD | 15M full duplex | 5 (/29) + 125 (/25) | [ 1,800 CNY/mo](https://account.lightlayer.net/?affid=74) |
| High-core, HK | 2× E5-2698 v3 (32C/64T) / 32 GB | 1 TB HDD + 240 GB SSD | 10M optimized / 15M / 20M international | 3 | [ 3,250 CNY/mo](https://account.lightlayer.net/?affid=74) |

The USD rows come from the homepage sales block; the CNY rows from the directory. CNY prices move with the exchange rate, and some plans require real-name verification. MegaLayer's news feed also lists a San Jose I3 server special at $42.71, which is the cheapest dedicated entry point advertised, though the configuration is not published next to it.

The multi-IP machines are the interesting line for anyone running SEO fleets: 130 usable addresses on one box at 1,800 CNY/month is a different product category from a $24.46 VPS, and no amount of VPS stacking replicates it.

## Premium, Standard and International: the choice that decides everything else

MegaLayer sells three bandwidth types and prices them differently. The port speed you get is set by the tier as much as by the plan size, and picking the wrong tier is the most expensive mistake available here.

**Premium Network** is the mainland-optimised tier, built on CN2. Hong Kong runs CN2/CMI/CU/HGC/HKIX and starts at 10 Mbps. San Jose runs CN2/CT/CU/CMI/PCCW/COGENT and starts at 30 Mbps.

**Standard Network** is Premium minus CN2, offered mainly in the US, starting at 100 Mbps.

**International Network** deliberately skips mainland optimisation. Hong Kong uses HKT and Zenlayer and starts at 20 Mbps; the US uses PCCW and COGENT and starts at 200 Mbps.

One detail worth separating: Hong Kong also carries a China Telecom 163 line, with 163, China Mobile, China Unicom, Zenlayer and HGC available as standard bandwidth options. That is a different product from the CN2 Premium route. If a plan description says "optimized" without naming CN2, ask which of the two you are getting.

The decision rules are short:

- Visitors in mainland China → **Premium**. Do not buy International because 200 Mbps looks better on paper. A 200 Mbps port that congests at 20:00 is worse than a 30 Mbps port that holds steady.
- Visitors outside China, or bulk transfers between overseas nodes → **International**. You get two to twenty times the port for the same or less money.
- Need throughput but no China routing at all → **Standard**, US, 100 Mbps upward.

Every VPS comes with native IPv4 and IPv6, not shared addresses and no NAT. That matters at this price band, where a lot of the competition hands you a port number on a shared IP.

## What a year actually costs, and the renewal question

$24.46 is an annual price. Plan write-ups describe the billing structure as: annual billed at 10 months (two free), semi-annual billed at 5 months, quarterly with an extra 5% off. If that holds, paying annually saves roughly 17% against monthly billing, and the entry plan lands at about $2.04 a month.

Two caveats on that arithmetic. The billing-cycle structure is described in third-party plan write-ups, not reproduced on a public MegaLayer price page I could verify, so treat it as indicative. More importantly, **nothing in the sources says whether $24.46 is a first-year price or a standing one**. Renewal is the number that decides whether a cheap host is actually cheap, and it is the number most write-ups skip. Check it on the order page before you pay.

The checkout and account portal used here sits on LightLayer's domain; LightLayer is MegaLayer's lightweight-cloud sub-brand. The order page is where the plan name, term and renewal price for the specific configuration are confirmed, which is exactly where you want to be looking before entering payment details.

## The clauses that decide whether you get a refund

MegaLayer's refund terms are narrow, and they are buried in policy pages rather than the homepage:

1. **Refunds only when the fault is MegaLayer's.** Reasons not attributable to MegaLayer, including a change of mind, fall outside the refund scope. This applies to regular-priced products as well as promotional ones.
2. **Promotional plans are generally non-refundable.** The $24.46 entry plan and the 50%-off Singapore plans are promotional.
3. **Some plans require real-name verification,** and CNY pricing floats with the exchange rate.

Read together, that means the cheap entry point is a commitment, not a trial. If you are unsure whether a 10 Mbps Hong Kong port handles your traffic, start with the smallest plan for one quarter rather than a year, even though the annual rate is better.

👉 [Check the current plan list and terms before you order](https://account.lightlayer.net/?affid=74)

## DDoS, uptime and support: what is actually documented

After a week-long attack campaign a few years back, MegaLayer moved its network behind Cloudflare Magic Transit. The company's own figures, quoted in third-party coverage, are 4,000+ attacks blocked in a single August week with peak traffic of 13 Gbps and no major service disruption, plus a 50% drop in network maintenance cost and a 60% drop in maintenance workload during large-scale attacks. Those are the vendor's numbers; there is no independent audit of them. Availability under attack is described as close to 100%.

The infrastructure behind that: data centres in Hong Kong (ME), Singapore (T3-certified, 99.99% power SLA), Manila and San Jose, with transit from GTT, Cogent, China Telecom, China Mobile, China Unicom, NTT, PCCW, Telia and TATA.

On support, Linux and Windows are both offered, and operations coverage is 7×24×365. The ticket response commitment quoted in third-party write-ups is 72 hours. That is a queue time, not a live-chat SLA, and it shapes what you should expect: a working server you manage yourself, with help arriving in days rather than minutes. Payment is by Alipay and PayPal, with credit card and WeChat appearing in some listings.

## Who should not buy MegaLayer

**Anyone whose audience is in Europe.** The locations on offer are Hong Kong, Singapore, Manila and San Jose. European traffic lands on a US or Asian route with added latency, and you would be paying for CN2 you never use.

**Anyone who needs a managed server.** A 72-hour ticket queue and a $2/month price point describe self-managed infrastructure. If you want someone to fix your stack, this is the wrong provider and the wrong budget.

**Anyone running anything load-bearing on 1 GB of RAM.** The $24.46 plan is a real server, but 1 GB with a 10 Mbps port is a small footprint. A WooCommerce store with a few hundred daily visitors will page. Budget for the 2 GB Hong Kong plan quoted through sales, or a US plan with a 100 Mbps port.

**Anyone hunting below $2/month for production.** Native IPv4 and IPv6 with no NAT is the thing you are paying for at this level. Below it, you are usually looking at shared addresses and crowded ports, which is a different trade.

## Picking a plan in one pass

- One small site, proxy or bot for mainland visitors → **HK VPS Basic**, $24.46/year.
- Same workload, North American users → **US VPS Entry**, 30 Mbps at the same price.
- A real application needing 2 GB RAM in Hong Kong → **HK VPS Standard**, quoted through sales.
- Singapore presence and the T3 facility → **SG VPS Starter** at the standing 50% off.
- Many addresses for SEO or multi-site hosting → the **HK multi-IP dedicated** at $236/month, or the /29 + /25 machine at 1,800 CNY/month.
- Heavy compute → **2× E5-2698 v3**, 32 cores and 64 threads in Hong Kong.

Two things to confirm on the order page before paying: the port speed and route attached to the exact plan name (the same name can appear with Premium or International routing), and the renewal price and billing term. Those two lines decide whether the annual price is a bargain or a first-year discount.

👉 [View the MegaLayer plans currently on sale](https://account.lightlayer.net/?affid=74)
