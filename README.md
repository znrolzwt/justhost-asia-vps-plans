# LowEndBox VPS deals, verified: what JustHost.asia charges from $1.99/mo, which plan is worth buying, and the port-speed catch behind "unmetered" traffic (full plan table)

JustHost.asia's cheapest buyable VPS is the **Promo** plan: 1 core, 512 MB RAM, 5 GB NVMe, **$1.99/month**. Its real limit is the network port, 10 Mbps fair-share, which caps out at 1.25 MB/s no matter how much monthly traffic the listing advertises.

Most people working through a lowendbox vps shortlist don't need 512 MB. They need the cheapest plan with a port they can actually use. That's **Sirius Special at $2.25/month on a 12-month term**: 1 GB RAM, 20 GB NVMe, 300 Mbps, KVM. Twenty-seven dollars a year.

Put that next to the rest of this month's promo crop and JustHost.asia is not the RAM-per-dollar winner. One-gigabyte VPSes are going for $12/year elsewhere, and 4 GB NVMe boxes are down to $2.39–$3.20/month on annual billing. What this provider sells instead is location choice, a config builder, and an IPv6-only tier from $1.60/month. Whether that's worth a premium depends entirely on what you're deploying, and the rest of this page is about figuring that out.

> **The short version**
> - **Best value overall:** Sirius Special, 1 GB / 20 GB NVMe / 300 Mbps, **$2.25/mo billed 12 months** ($27/year).
> - **Cheapest box:** VPS Promo, 512 MB, **$1.99/mo**, but only a 10 Mbps port.
> - **Docker, game server, multiple sites:** Vega Special, 4 GB / 80 GB NVMe / 500 Mbps, **$6.23/mo billed 12 months**.
> - 👉 [See the current JustHost.asia VPS lineup and prices](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## The full JustHost.asia plan list, with both price columns

Every plan below is KVM, NVMe, with DDoS protection included and an unmetered fair-share port. The prices are USD; the second price is the effective monthly rate when you prepay 12 months, which is where the advertised 20% comes from.

| Plan | RAM / vCPU / NVMe | Port (fair-share) | Monthly | 12-month rate | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 512 MB / 1 / 5 GB | 10 Mbps (~4 TB) | $1.99 | shown at checkout | [Order Promo](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 GB / 1 / 10 GB | 100 Mbps (~31 TB) | $3.81 | $3.05 | [Order New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Double Star | 2 GB / 2 / 20 GB | 200 Mbps (~62 TB) | $7.08 | $5.67 | [Order Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Bright Star | 4 GB / 4 / 30 GB | 300 Mbps (~93 TB) | $9.80 | $7.84 | [Order Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Sirius | 1 GB / 1 / 20 GB | 300 Mbps (~93 TB) | $4.85 | $3.88 | [Order Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 2 GB / 1 / 30 GB | 300 Mbps | $6.92 | $5.53 | [Order Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Alpha Centauri | 2 GB / 2 / 40 GB | 400 Mbps (~124 TB) | $8.99 | $7.19 | [Order Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Vega | 4 GB / 2 / 80 GB | 500 Mbps (~155 TB) | $13.44 | $10.75 | [Order Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 GB / 4 / 120 GB | 750 Mbps (~232 TB) | $18.30 | $14.64 | [Order Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

The ladder keeps going above Capella with Rigel at 4 cores / 8 GB / 200 GB NVMe; its price sits on the plan page rather than in the comparison list.

There is a second, cheaper set of SKUs on the product page marked as special offers, with lower prices for what the pages describe as the same hardware:

| Plan | RAM / vCPU / NVMe | Port | Monthly | 12-month rate | Order |
| --- | --- | --- | --- | --- | --- |
| Sirius Special | 1 GB / 1 / 20 GB | 300 Mbps | $2.81 | $2.25 | [Check Sirius Special](https://justhost.asia/en/vps?ref=196392) |
| Arcturus Special | 2 GB / 1 / 30 GB | 300 Mbps | $4.01 | $3.21 | [Check Arcturus Special](https://justhost.asia/en/vps?ref=196392) |
| Vega Special | 4 GB / 2 / 80 GB | 500 Mbps | $7.79 | $6.23 | [Check Vega Special](https://justhost.asia/en/vps?ref=196392) |
| Yildun Special | 8 GB / 4 / 200 GB | 750 Mbps | $16.20 | $12.96 | [Check Yildun Special](https://justhost.asia/en/vps?ref=196392) |
| Betelgeuse Special | 12 GB / 6 / 400 GB | 750 Mbps | $26.40 | $21.12 | [Check Betelgeuse Special](https://justhost.asia/en/vps?ref=196392) |
| Altair Special | 24 GB / 8 / 600 GB | 750 Mbps | $47.40 | $37.92 | [Check Altair Special](https://justhost.asia/en/vps?ref=196392) |

Sirius, Arcturus and Vega appear on both lists with identical published cores, RAM, disk and port speed, at roughly 58% of the standard price on the Special side. Nothing on either page explains the gap. Ask support which SKU you're being sold and what the difference is before you pay the higher figure. If the answer is "the same server, older chassis", the Special wins without argument.

## "Unmetered traffic" is a port speed wearing a disguise

The traffic figures in brackets above are not allowances. They're what the port moves if you saturate it every second of a 30-day month, which is why a 10 Mbps plan claims "4+ TB" and a 750 Mbps plan claims "232+ TB". The provider isn't capping your bytes; the pipe does it for you.

What that means in practice:

- **10 Mbps** = 1.25 MB/s. A 100 GB off-site backup pull takes about 22 hours. A 5 GB site restore takes over an hour.
- **100 Mbps** = 12.5 MB/s. The same 100 GB pull lands in around two hours.
- **750 Mbps** = 93 MB/s. Under 20 minutes for that 100 GB, if the disk and the far end keep up.

For a static site doing 20–50 GB a month, even the 10 Mbps Promo is fine, because you'll never touch the ceiling. For anything that pushes data in bursts, the port is the spec you should be comparing, not the terabyte number. This is the single most common thing the promo posts leave out, and it's why a "4 TB" plan can feel slower than a "1 TB" plan on another host.

## What year one and year two actually cost

The 20% is a billing-term discount, not a first-invoice coupon, and JustHost.asia doesn't publish a separate renewal rate. Renew on the same 12-month term and year two costs the same as year one. That's the useful part: no renewal cliff to plan around, unlike hosts that advertise a low first term and reprice afterwards. Confirm it with support if you're prepaying a large plan, because a term discount that quietly expires is exactly the kind of thing that doesn't show up until month thirteen.

Year-one arithmetic on the plans worth considering:

- **Sirius Special:** $33.72 if you pay monthly for twelve months; $27.00 if you prepay. The prepay saves $6.72.
- **New Star:** $45.72 monthly; $36.60 prepaid. Saves $9.12. Note this plan is only sold in terms of three months or longer, so there's no true month-to-month option.
- **Vega Special:** $93.48 monthly; $74.76 prepaid. Saves $18.72.
- **Bright Star:** $117.60 monthly; $94.08 prepaid. Saves $23.52.

The prepay discount is worth taking on anything you intend to keep for a year. It is not worth taking on a host you haven't tested. Which brings up the next point.

👉 [Compare the Special offers against the standard tariff before you pay list price](https://justhost.asia/en/vps?ref=196392)

## How it stacks up against the current LowEndBox-style promo crop

Cheap VPS pricing in late 2026 is aggressive, and it helps to see where these numbers sit. All of the following are the same rough tier of low-end, KVM, NVMe hosting:

| Provider | Plan | Price | Location |
| --- | --- | --- | --- |
| Servitro | 1 GB / 10 GB NVMe / 1 TB | $12/year | Frankfurt |
| Servitro | 4 GB / 25 GB NVMe | $3.20/mo, or $35.20/year | Frankfurt |
| GenixNode | 4 GB / 40 GB NVMe | from $2.39/mo billed annually | Istanbul, Sofia |
| GenixNode | 4 GB / 40 GB NVMe | $6.19/mo | London, New York, Los Angeles and others |
| Kainode | 4 GB / 1 TB transfer | $5.99/mo | Singapore |
| RackNerd | entry plans | from $21.99/year | multiple |
| **JustHost.asia** | **1 GB / 20 GB NVMe / 300 Mbps** | **$2.25/mo billed annually** | pick at order |
| **JustHost.asia** | **4 GB / 80 GB NVMe / 500 Mbps** | **$6.23/mo billed annually** | pick at order |

Two things fall out of that table. At the very bottom of the range, a 512 MB box at $1.99/month is roughly double what a 1 GB annual plan costs elsewhere, so if all you want is the cheapest possible Linux shell, JustHost.asia isn't the answer. Move up one notch and the picture changes: Sirius Special gives you triple the port speed and double the disk of a $12/year 1 GB plan, for a bit over twice the annual spend.

At 4 GB the comparison gets more interesting. Vega Special lists 80 GB of NVMe and a 500 Mbps port for $6.23/month, against 40 GB and a shared 1 Gbps port for $2.39–$6.19 elsewhere depending on region. You're paying a premium over the absolute floor, and getting double the disk and a much faster port for it. If you need a specific city rather than the cheapest city, that trade is usually the right one.

## What the reviews say about uptime and support

The Trustpilot page for justhost.asia is dominated by complaints, and they cluster around two themes rather than price. Every reviewer concedes the service is cheap; several say so in the first line.

The recurring complaints: the on-site live chat is a bot that can't resolve anything, ticket replies arrive hours later or after the server has already come back on its own, and there is no public status page, so during an outage you can't tell whether you're looking at five minutes or two days. One reviewer describes a full outage on 2 March 2026 across servers and control panel with no updates for 15 hours. Another reports moving from Amsterdam to Helsinki after throughput collapsed to roughly 20 Mbit/s with 1500 ms latency, and notes that the migration was manual and required rebuilding the server from scratch. One more says planned maintenance is announced after the fact, when the service stops responding.

Set against that, support is documented as responding within 48 hours, and the platform sells managed services as a paid add-on.

What to do with that: don't treat this as a host for anything where an unplanned 24-hour absence costs you money. It's a reasonable fit for a personal project, a staging box, a VPN endpoint, a monitoring node, a small site where a day of downtime is annoying rather than fatal. Keep your own backups on a different provider, and keep a snapshot you can restore from without needing their panel.

## Pick by job, not by price

The plan names don't tell you anything. Here's the mapping that does:

**A shell, an IRC bouncer, a DNS secondary, a tiny proxy** → VPS Promo at $1.99/month. 512 MB is enough for Alpine or a minimal Debian with a handful of services, and none of those jobs care about a 10 Mbps port. Don't put a website with images on it.

**One small site, an app, a VPN with real throughput** → Sirius Special at $2.25/month on 12 months. It's cheaper than New Star's annual rate while giving twice the disk and three times the port, so New Star only makes sense if you specifically want the shorter minimum term.

**Docker, a Minecraft server, several sites behind one IP** → Vega Special at $6.23/month on 12 months. 4 GB is the point where containers stop fighting over memory, and 80 GB of NVMe leaves room for images and logs.

**Anything above 8 GB** → Yildun or Betelgeuse Special, but check the price against a dedicated server first. At $21.12/month for 12 GB you're in the range where dedicated hardware starts being a conversation.

**IPv6-only experiments** → the IPv6-only family starts at $1.60/month. If you need a real IPv4 address, budget for the IPv4+IPv6 family instead, which starts at $2.60.

👉 [Order the $1.99 VPS Promo plan if you only need a shell](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392)

## Six things to confirm before you pay

1. **Which SKU you're buying.** The same specs are listed at two prices. Confirm the Special price applies to the plan in your cart.
2. **The minimum term.** New Star, Double Star and Bright Star require three months or more. Sirius, Arcturus and Vega don't carry that restriction.
3. **Whether IPv4 is included.** The cheapest entries on the product page are IPv6-only. Check the address type on the plan, not just the price.
4. **The port speed of your specific plan.** Nothing else about a low-end VPS degrades an experience faster than a 10 Mbps ceiling on a job that needs 100.
5. **The checkout total on 12 months.** Promo shows a discount field without a 12-month figure, so the cart is the only place the real annual number appears.
6. **Your own backup plan.** Given the outage reports, assume the panel may be unreachable exactly when you need it. Snapshot to storage you control.

KVM matters in this bracket too. A KVM guest gets dedicated memory and disk allocation, which is the structural difference between a real VPS and an oversold container sold on the same specs sheet. JustHost.asia lists KVM across the lineup, so the distinction here is between plans rather than between hosts.

If your workload is a shell or a small service and you want a location you can choose rather than one you're handed, start at the bottom and pay monthly for the first cycle: 👉 [check the Promo plan and the rest of the JustHost.asia VPS range](https://justhost.asia/en/services/vps/tariffs-all?ref=196392). If it holds up for a month, move to Sirius Special on a 12-month term and take the 20%.
