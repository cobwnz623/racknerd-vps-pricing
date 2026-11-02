# cheapest vps: What $21.99/Year Really Gets You, How Renewal Pricing Works, and Which RackNerd Plan to Pick

Searching for the cheapest vps gets you a wall of listicles, most of which quote first-year teaser prices and go quiet when renewal comes up. So here's the short version first: the cheapest currently listed KVM VPS plans from RackNerd start at **$21.99 per year** (about $1.83/month), renew at the same price for as long as you keep the service, and include full root access, a 1 Gbps port, and a dedicated IPv4. The catches that deal posts tend to skip: there are **no refunds**, support is unmanaged, and the cheapest plan only has 1 GB of RAM — enough for a tunnel or a hobby project, tight for much else.

This article walks through the full plan table with verified prices, the renewal math that decides whether "cheap" stays cheap, the fine print from RackNerd's own knowledgebase, and a plan-picking rule based on what you actually want to run.

> **Quick picks**
> - Most people: **2 GB KVM VPS — $35.99/year** (2 vCPU, 35 GB SSD, 5 TB traffic). It's the cheapest plan with two cores and enough RAM for Docker or a small production site.
> - Bare minimum on a tight budget: **1 GB KVM VPS — $21.99/year** (1 vCPU, 20 GB SSD, 3 TB traffic).
> - 👉 [Check all five RackNerd VPS specials and current prices](https://bit.ly/RacKnerd)

## RackNerd's current VPS specials: the full plan table

RackNerd's specials page currently lists five annual KVM VPS plans, from $21.99 to $119.99 per year. All prices below are taken directly from the official specials page, and every plan shares the same baseline: full root access, 1 IPv4 address, 1 Gbps network port, KVM virtualization, and deployment across multiple datacenter locations.

| Plan | vCPU | RAM | SSD | Monthly Transfer | Annual Price | Order |
| --- | --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS (listed as Most popular) | 1 | 1 GB | 20 GB | 3 TB | **$21.99** | [ Get the 1 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=952) |
| 2 GB KVM VPS | 2 | 2 GB | 35 GB | 5 TB | **$35.99** | [ Get the 2 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=953) |
| 4 GB KVM VPS | 3 | 4 GB | 60 GB | 7 TB | **$59.99** | [ Get the 4 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=954) |
| 6 GB KVM VPS | 6 | 6 GB | 100 GB | 12 TB | **$89.99** | [ Get the 6 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=955) |
| 8 GB KVM VPS | 7 | 8 GB | 150 GB | 20 TB | **$119.99** | [ Get the 8 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=956) |

One detail worth noticing in that table: RAM and CPU don't scale evenly. The jump from 2 GB to 4 GB costs $24/year more but only adds one core; the jump from 4 GB to 6 GB adds three cores for $30/year. If CPU matters more to you than RAM, the 6 GB plan is disproportionately generous.

Also know that special-plan configurations are fixed — you can upgrade later, but you can't downgrade a special to a cheaper tier and keep the original price locked. Order the size you actually need.

A second product line exists alongside these specials: regular KVM VPS plans billed monthly, tracked by deal sites at roughly $17.99–$55.99 per month with larger storage allowances. Those are a different market segment entirely — the specials are where the low prices live, and they're what this article focuses on.

## The renewal question: does the cheap price stick?

Yes — and this is the single biggest reason to take these specials seriously. RackNerd's own specials page FAQ states it plainly: "These RackNerd VPS specials are lifetime recurring. You can renew at the same rate for as long as you decide to keep the service."

That matters more than it sounds. A hosting-comparison site that tracks renewal pricing across 106 budget VPS providers found that only 16 of them even publish a renewal price, and just 6 of those never raise it. Among hosts that do publish both numbers, the median sign-up price is about $3.16/month while the median renewal is about $4.88/month. Run that through three years and you get roughly $155: one year at the intro rate, two years at the renewal rate. This "year one cheap, year two painful" pattern is the standard trap in the cheap VPS market.

Here's the three-year math for RackNerd's plans, renewal included, with no price change at any point:

- 1 GB: $65.97 over three years (~$1.83/month the whole time)
- 2 GB: $107.97 over three years (~$3.00/month)
- 4 GB: $179.97 over three years (~$5.00/month)

For context, one comparison site lists the cheapest same-price-renewal entry plan in its database at $2.99/month for 2 GB RAM — $108 over three years, billed monthly. RackNerd's 2 GB special comes out almost exactly even on total cost, but bills annually. Against the median renewal pattern above, the 2 GB special saves you roughly $47 over the same three years while carrying a lifetime price lock.

Holiday pricing has dipped lower than the current table in the past — deal trackers recorded 1 GB New Year and Black Friday specials around $10.99–$11.29/year — but those are limited-run events, and the current standing specials start at $21.99. If you land here during a holiday sale, grab it; if not, the standing price still renews forever at whatever you pay.

👉 [Lock in the 2 GB KVM rate at $35.99/year](https://my.racknerd.com/aff.php?aff=11397&pid=953)

## The fine print most deal posts skip

Two things about RackNerd rarely make it into promo articles, and both come from the company's own knowledgebase rather than grumpy forum posts.

First, **there is no money-back guarantee**. The official knowledgebase answer reads: "Per our terms of service, we do not offer refunds or have a money back guarantee," and a separate entry confirms that requesting immediate cancellation doesn't get your money back either. Combined with annual billing, this means a wrong purchase is a lost $21.99–$119.99, not a free trial. It's the main reason to read the plan table carefully before ordering instead of "trying it and seeing."

Second, the service is **unmanaged**. RackNerd provides 24/7 ticket support for platform-level problems — the network, the node, the control panel — but everything inside your VPS is your responsibility. There's no hand-holding for configuring your web server or debugging your app. If you need managed hosting or a Windows license, these Linux specials aren't the right product, and a Windows VPS roundup is a better place to look.

A few smaller policy details worth knowing before you order:

- Payment is by major credit cards (Visa, AMEX, Discover and similar) per the knowledgebase. RackNerd's official blog also lists PayPal, cryptocurrencies (BTC, LTC, ETH, ZEC), Union Pay, Alipay, iDEAL, and wire transfer among accepted methods — availability can vary, so check the checkout screen when you order.
- You can request an IP replacement at no extra charge within a limited window after deployment — useful if your assigned IP starts life on a bad reputation list.
- Custom ISO installs are possible, but only by submitting a support ticket; the standard order flow offers CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, or Ubuntu.
- The ctrl panel handles reinstalls, root password resets, an HTML5 VNC console, and inbound firewall rules, so most recovery tasks don't require a ticket.

## Which plan fits which project

Pick by RAM first, because RackNerd's own one-click app catalog tells you exactly where the floors are. The ctrl panel ships with one-click installers, and the official page is explicit about minimums: n8n and Coolify run comfortably from 2 GB; Ollama, AnythingLLM, LibreChat, and Hermes Agent want at least 4 GB; OpenClaw needs 8 GB.

That translates into a simple decision rule:

- **Tunnel, proxy, VPN node, Linux practice box** → 1 GB at $21.99/year. One core and 20 GB SSD is fine here. Just know that none of the one-click apps are rated for this plan — you're working over SSH.
- **Small website, Docker stack, n8n automation, Coolify** → 2 GB at $35.99/year. Two cores and 5 TB traffic make this the sensible default. It's the plan a user on a hosting forum singled out as an amazing price for what you get, after support fixed an rDNS request within ten minutes.
- **Local AI tools** (running models through Ollama, hosting a LibreChat instance, self-hosting AnythingLLM) → 4 GB at $59.99/year is the floor, and honestly the minimum you should accept. RAM-hungry model loading on 2 GB ends in swap thrashing.
- **Agent frameworks and heavier AI stacks** → 8 GB at $119.99/year, the only plan that meets OpenClaw's requirement, with 7 cores and 20 TB traffic to back it up.

One trap hides in the older holiday editions of these deals: past New Year specials sold a 2 GB plan with only one core, while the standing 2 GB special carries two cores and more traffic. Same RAM, meaningfully different machines — when a limited-time price looks tempting, compare core counts against the standing table before assuming it's better.

The regular monthly KVM line makes the specials look even better than they first appear. Deal trackers list the regular 4 GB monthly plan at $24.59/month — the 4 GB special costs $59.99 for an entire year, roughly 20% of that. The specials are configured more modestly on storage, but for annual-budget buyers the price gap is the story.

👉 [Order the 4 GB KVM plan for AI workloads](https://my.racknerd.com/aff.php?aff=11397&pid=954)

## Locations and what performance to actually expect

RackNerd operates around 20 datacenter locations. Per its looking-glass listings, North America covers Los Angeles (two facilities), San Jose, Seattle, Dallas, Chicago, New York, Ashburn, Atlanta, and Toronto; Europe covers Strasbourg, Amsterdam, and Dublin. The Los Angeles nodes are the ones third-party reviewers point to for Asia-bound traffic, since that network is routed with Asia in mind. Location availability varies by promotion, so confirm your preferred city is selectable in the order form before paying.

Performance is respectable for the price class but varies by node, and it's worth being honest about that. A published review with YABS benchmarks on two Black Friday-era servers found Geekbench 6 single-core scores of 910 on a Buffalo node versus 414 on a Dallas node, with fio 64K storage throughput between roughly 680 and 1,020 MB/s. Both machines ran older Xeon E5 server chips, and RackNerd doesn't publish CPU models per plan or location. Translation: disk and network performance are consistently fine, single-core speed is a lottery you can partially control by choosing location and checking community benchmarks for that specific node.

That's normal for this price bracket. What you're buying is KVM isolation, dedicated resources, and a 1 Gbps port at two dollars a month — the compromise is older hardware generations and variance between nodes.

## How ordering works

The flow is short:

1. Pick a plan from the specials page and add it to the cart.
2. Choose your datacenter location and operating system during checkout.
3. Pay by your preferred supported method. Deployment is automatic and near-instant after payment.
4. Log into the ctrl panel, where your root credentials appear, one-click apps install with credentials shown in-panel, and the VNC console is available if you need out-of-band access.

No coupon code is needed for the specials — the discounted price is the listed price. If you want a custom ISO, submit a ticket after deployment rather than hunting for it in the order form.

👉 [Open the RackNerd order page and pick your plan and location](https://bit.ly/RacKnerd)

## FAQ

**Do RackNerd VPS specials renew at the same price?**
Yes. The official FAQ states the specials are lifetime recurring — you renew at the rate you paid for as long as you keep the service. This is verified on the specials page itself, not just marketing copy.

**Can I get a refund if I change my mind?**
No. RackNerd's terms of service exclude refunds and money-back guarantees, including for immediate cancellations. Treat the annual payment as final and choose your plan accordingly.

**Is the VPS managed?**
No. All special-plan VPSes are unmanaged KVM servers. You get 24/7 ticket support for infrastructure issues and a full-featured control panel, but server administration is on you.

**Can I run Docker and AI applications?**
Yes, within RAM limits. Docker and Portainer run fine from 2 GB, Ollama and similar AI tools want 4 GB, and OpenClaw requires 8 GB. The one-click installers in ctrl cover the common setups, or you can bring your own stack over SSH.

**How does this compare to mainstream cheap VPS offers?**
Big-brand entry plans in recent comparisons run around $5–6/month for entry specs (CyberNews's August 2026 roundup lists Hostinger's KVM 1 at $5.84/month), and the budget-market median renewal sits near $4.88/month across 106 tracked providers. RackNerd's 2 GB special works out to about $3.00/month with no renewal increase — below both numbers — though with less polish, unmanaged support, and annual billing only.

## Before you click order

Match the plan to the job and you'll be fine: 1 GB for tunnels and learning, 2 GB for sites and Docker, 4 GB as the AI floor, 8 GB only if you specifically need it. If you need monthly billing, Windows, or managed support, this isn't your product — the regular monthly KVM line starts near $18/month, and Windows-focused providers are a better fit there.

Two last checks that take a minute and prevent the two most common regrets: confirm your preferred datacenter location is actually selectable for the plan you're buying, and remember the no-refund policy means the annual fee is committed the moment payment clears. Pick accordingly, and expect the price you see now to be the price you renew at for years.

👉 [Order the 2 GB KVM special — $35.99/year, locked for renewals](https://my.racknerd.com/aff.php?aff=11397&pid=953)
