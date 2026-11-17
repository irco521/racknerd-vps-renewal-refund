# Cheap annual VPS: is RackNerd's $21.99 plan enough, what renewal really costs, and the refund rule to read before you pay (full plan table)

RackNerd's 1 GB KVM special costs **$21.99 a year**, which is $1.83 a month for 1 GB RAM, 1 vCPU, 20 GB of RAID-10 SSD and 3 TB of monthly transfer on a 1 Gbps port. It is the cheapest plan in their lineup I'd call usable, and it's also the one many readers should skip: the **$35.99 2 GB plan** costs $14 more per year and removes the memory ceiling you hit the first time you put a database next to a web server.

Two details decide this purchase more than the spec sheet. The annual rate is recurring for as long as you keep the service, and RackNerd does not refund VPS payments. That means you pick the right size before checkout, because there is no undo button a week later.

> **Quick picks**
> - **1 GB, $21.99/yr** — WireGuard or OpenVPN endpoint, a static site, Uptime Kuma, a single bot.
> - **2 GB, $35.99/yr** — the default for most people: n8n, Coolify, Gitea, Vaultwarden, a small Nextcloud.
> - **4 GB, $59.99/yr** — anything AI-adjacent, or a full Nginx + PHP + MySQL + Redis stack.
> - **8 GB, $119.99/yr** — OpenClaw, Jellyfin transcoding, or 20 TB of monthly traffic.
> 👉 [See the current annual specials and check which locations are in stock](https://bit.ly/RacKnerd)

## The full RackNerd lineup

Two product lines matter here, and they bill differently. The Special Promo plans are annual only. The Standard KVM plans are billed monthly and carry more storage and more vCPU per dollar of RAM.

**Annual specials (annual billing only)**

| Plan | RAM / vCPU | SSD | Transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM Special | 1 GB / 1 core | 20 GB | 3,000 GB/mo | **$21.99/yr** | [Take the $21.99 plan](https://bit.ly/RacKnerd) |
| 2 GB KVM Special | 2 GB / 2 cores | 35 GB | 5,000 GB/mo | **$35.99/yr** | [Take the $35.99 plan](https://bit.ly/RacKnerd) |
| 4 GB KVM Special | 4 GB / 3 cores | 60 GB | 7,000 GB/mo | **$59.99/yr** | [Take the $59.99 plan](https://bit.ly/RacKnerd) |
| 6 GB KVM Special | 6 GB / 6 cores | 100 GB | 12,000 GB/mo | **$89.99/yr** | [Take the $89.99 plan](https://bit.ly/RacKnerd) |
| 8 GB KVM Special | 8 GB / 7 cores | 150 GB | 20,000 GB/mo | **$119.99/yr** | [Take the $119.99 plan](https://bit.ly/RacKnerd) |

All five include KVM virtualization, RAID-10 SSD, a 1 Gbps port, full root access, the ctrl control panel, and a choice of data center locations.

**Standard KVM (monthly billing, more storage per tier)**

| Plan | RAM / vCPU | SSD | Transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 512 MB KVM | 512 MB / 1 core | 30 GB | 500 GB/mo | $26.99/yr | [See the 512 MB plan](https://bit.ly/RacKnerd) |
| 1 GB KVM | 1 GB / 2 cores | 50 GB | 1,000 GB/mo | $17.99/mo | [See the 1 GB monthly plan](https://bit.ly/RacKnerd) |
| 2 GB KVM | 2 GB / 3 cores | 75 GB | 2,000 GB/mo | $20.59/mo | [See the 2 GB monthly plan](https://bit.ly/RacKnerd) |
| 4 GB KVM | 4 GB / 4 cores | 130 GB | 3,000 GB/mo | $24.59/mo | [See the 4 GB monthly plan](https://bit.ly/RacKnerd) |
| 6 GB KVM | 6 GB / 5 cores | 170 GB | 4,000 GB/mo | $27.59/mo | [See the 6 GB monthly plan](https://bit.ly/RacKnerd) |
| 8 GB KVM | 8 GB / 6 cores | 220 GB | 5,000 GB/mo | $36.59/mo | [See the 8 GB monthly plan](https://bit.ly/RacKnerd) |
| 12 GB KVM | 12 GB / 7 cores | 300 GB | 6,000 GB/mo | $55.99/mo | [See the 12 GB monthly plan](https://bit.ly/RacKnerd) |

The 512 MB row is listed by RackNerd at an annual figure while every other Standard plan is monthly, so treat it as an oddity and read the cart total rather than the table. Stock and available locations change per offer, and the checkout total is the only number that counts.

## What $21.99 actually buys, and what it doesn't

You get a KVM guest with root access, a 1 Gbps port, instant provisioning after payment, and the ctrl panel for reboots, OS reinstalls, an HTML5 VNC console, rDNS management, root password resets, inbound firewall rules and one-click apps. Supported installs include CentOS, Rocky Linux, AlmaLinux, Fedora, Debian and Ubuntu; custom ISOs go through a support ticket. Payment options cover PayPal, major credit cards, Alipay, Bitcoin, Ethereum and USDT.

You do not get a managed server. Nobody patches your kernel, nobody answers a live chat at 2 a.m., and the support channel is tickets only. Platform problems get 24/7 coverage; your broken Nginx config does not.

You also don't get backups. RAID-10 survives a dead drive. It does nothing about a mistyped `rm -rf`, and there is no bundled snapshot product on the VPS side. Plan to push encrypted backups to a second provider or object storage from day one.

## Renewal: the number that doesn't move

The usual fear with annual budget hosting is a first-year hook, then a renewal at two or three times the price. RackNerd's specials FAQ addresses it directly: the specials are "lifetime recurring," renewable at the same rate for as long as you keep the service.

Run the arithmetic on the 1 GB plan. Year one is $21.99. Two years is $43.98. Three years is $65.97. The per-month figure stays at $1.83 the whole way through, and the 2 GB sits at $3.00/mo equivalent, the 4 GB at $5.00, the 6 GB at $7.50, the 8 GB at $10.00.

What did change is the entry price. During Black Friday 2025 the 1 GB special was $10.99 a year, and the 2 GB tier was $18.93 (on a 2.5 GB SKU, so not a straight comparison). Today's equivalents are $21.99 and $35.99. If you are reading this in a holiday promo window, there may be a lower tier on offer, but the historical low is not the current price and shouldn't be your budget assumption.

👉 [Lock in the $21.99 annual rate before the current stock sells through](https://bit.ly/RacKnerd)

## The refund question, answered by RackNerd's own documentation

RackNerd's knowledgebase is unambiguous: per their terms of service, they do not offer refunds or a money-back guarantee on VPS services. There is no trial period either.

That single policy reshapes how you should buy. The first hour after deployment is your evaluation window, not the first month. Provision the box, run a quick YABS benchmark, watch `htop` for CPU steal, test your real route with `mtr`, and if the node underperforms, open a ticket with those results and ask about a migration. Third-party benchmarks across their fleet show real host-to-host spread, from a Buffalo node scoring 910 in Geekbench 6 single-core to a Dallas box on older Xeons scoring 414. You are buying into a pool of hardware, and the node you land on is part of what you paid for.

Cancellation is also on you. Reviews of the service document a requirement to notify support in writing roughly five days before the renewal date to stop a cycle. Put a calendar reminder a week ahead of the anniversary and you won't pay for a year you don't want.

## Annual special vs monthly billing: the 4.9x gap

The same 4 GB of RAM costs $59.99 for a year on the special and $24.59 a month on the standard plan. Over twelve months that's $59.99 against roughly $295, close to five times more, even though the monthly plan throws in 130 GB of storage instead of 60 GB and one extra core.

The break-even sits around four months of commitment. If you need a box for a two-week test, or you specifically need to be able to walk away next month, monthly billing from RackNerd or from a European monthly provider is the honest answer. Past four months, the annual special wins on total cost with room to spare.

👉 [Compare the annual specials against monthly billing side by side](https://bit.ly/RacKnerd)

## Which plan fits which job

**1 GB / $21.99.** A WireGuard or OpenVPN endpoint for a household, a static site behind Nginx, Uptime Kuma, a single microservice, a Linux playground. RackNerd's own guidance is that this tier is fine for a small PHP app and not the place to run Node.js with a database unless you enjoy tuning OOM behaviour.

**2 GB / $35.99.** The general-purpose starting point. RackNerd lists n8n and Coolify as comfortable from 2 GB, and that tier also handles a few simultaneous self-hosted services (Nextcloud, Gitea, Vaultwarden) or a small private Minecraft server. The second vCPU matters here: compiling anything on one core turns a five-minute job into a coffee break.

**4 GB / $59.99.** The entry point for AI tooling. RackNerd's one-click catalogue requires at least 4 GB for Hermes Agent, AnythingLLM, Ollama and LibreChat. It's also the smallest size where a full Nginx + PHP-FPM + MySQL + Redis stack has breathing room.

**6 GB / $89.99 and 8 GB / $119.99.** OpenClaw wants 8 GB. So does Jellyfin or Plex with transcoding, a heavier database, or several apps on one box. The 8 GB plan's 20 TB of monthly transfer is the real differentiator if you're serving media or large downloads rather than just running services.

## Locations, and the Amsterdam case

RackNerd runs locations across the US, Canada and Europe, with Asia-optimized routing available out of Los Angeles. The Amsterdam facility sits inside Equinix AM5, a carrier-neutral site with ISO 50001, ISO 9001, ISO 14001 and SOC 2 Type II certification, N+1 power and N+2 cooling. It peers through AMS-IX, one of the largest internet exchanges in the world, which is why routes to Frankfurt, London and Paris land in the 6–8 ms range and local latency stays under 1 ms.

One ordering trap: the general specials page does not pre-select Amsterdam. Open the location dropdown and confirm your target data center is actually there before you pay, because the available locations vary by offer. RackNerd also runs location-specific store pages where a given SKU can carry a different annual price than the general special, so if a cheaper Amsterdam listing shows up, the cart total is the number to trust.

## Where RackNerd loses

Monthly European providers beat an annual commitment on flexibility, and anyone who needs NVMe should look elsewhere since these plans are RAID-10 SSD.

| Provider | Entry configuration | Price | Billing |
| --- | --- | --- | --- |
| HOSTKEY | 1 core / 1 GB | from €2/mo | Monthly, no commitment |
| Melbicom | KVM NVMe entry tier | from €3.90/mo | Monthly |
| EDIS Global | KVM Smart, 1 vCPU | €4.99/mo | Monthly, multiple EU sites |
| Hostwinds | Unmanaged SSD Cloud 1, 1 vCPU / 1 GB | $4.99/mo | Monthly |
| Scaleway | Stardust1-S, micro instance | $0.51/mo | Monthly, stock notoriously scarce |
| Dewlance | 1 GB / 1 vCPU / 40 GB NVMe, US | $18/yr | Annual |

EDIS at €4.99 a month is roughly €60 a year for a single vCPU against RackNerd's $21.99. HOSTKEY's €2 entry beats the annual plan for the first two months of a short project and loses badly by month six. A Liquid Web roundup from October 2026 puts the floor of the whole market at about $2 a month, with most VPS landing between $4 and $100, which is the context in which a $1.83/mo annual plan is unusual rather than normal.

## Ordering, and the twenty minutes after

1. Pick the plan and confirm the location dropdown shows your target data center.
2. Choose the OS, set a hostname and a root password of at least 8 characters.
3. Pay. Provisioning is instant, not queued for manual review.
4. Expect two emails: an order confirmation, then the one with your IP and login credentials.
5. SSH in, then benchmark before you migrate anything real.

That last step isn't ceremony. Run YABS, check `htop` for steal, and `mtr` your actual route. A node that underperforms on day one is a support ticket with evidence attached, and migration requests are more likely to be honoured before you've built a stack on top of it.

## The decision, in one place

A VPN endpoint, a static site, or a monitoring box: 1 GB at $21.99 a year, and don't overspend on capacity you won't use. A handful of self-hosted services with a database: 2 GB at $35.99, which is where most readers should land. Anything AI-adjacent or a full web stack: 4 GB at $59.99. Media serving or OpenClaw: 8 GB at $119.99.

Before you type a card number, confirm two things on the order page: that your data center appears in the location dropdown, and that the cart total matches the price you expect. After that, treat the first hour as your only inspection window, because the payment is final and the renewal, at least, will never surprise you.

👉 [Start with the 1 GB annual plan at $21.99, or size up from the same specials page](https://bit.ly/RacKnerd)
