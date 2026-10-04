# buy proxies: pick the right residential pricing model, compare 9Proxy plans from $15, and test before you commit

Most people searching "buy proxies" already know they need one. The hard part starts one step later, when the checkout page asks you to choose between paying per IP and paying per gigabyte and you realize those two options can differ by a factor of three on the same job.

So let's do the unglamorous part first: figure out which billing model fits your workload. Then look at what a specific provider, 9Proxy, actually charges for each model, and what you should check before handing over a card.

## The billing model matters more than the logo on the dashboard

Residential proxy pricing comes in two shapes, and picking the wrong one is the single most expensive mistake in this category.

**Per IP, unlimited bandwidth.** You buy a fixed number of residential IPs and push as much traffic through them as you want. Cost is predictable even when the pages you're loading are heavy. The catch: you're limited to the IPs you bought, and each residential IP has a natural lifespan, so IPs churn.

**Per gigabyte.** You buy a bucket of traffic and generate as many endpoints as you like. Great when each request is small and you need a fresh IP constantly. Bad when your target is a JavaScript-heavy page weighing 2 to 5 MB, because every retry is money.

A scraper hitting 100,000 heavy pages a month can burn $1,500 to $3,000 in bandwidth-only billing, which is exactly the argument 9Proxy makes for its per-IP model. If your workflow is login sessions, account management, checkout flows, or anything where page weight is unpredictable, unlimited bandwidth usually wins. If you're doing lightweight geo-checks or API polling with constant rotation, per-GB wins.

Everything else in the buying process is secondary to that call.

## Residential, datacenter, ISP, mobile: don't buy the wrong category

Before the pricing question there's a category question, and it's quick to answer.

- **Residential** — IPs on real home connections. Highest trust, slowest of the four, priced highest. The default choice for anything that gets blocked by bot detection.
- **Datacenter** — fast and cheap, hosted on server networks. Fine for scraping sites with no serious protections, and for raw speed.
- **ISP (static residential)** — hosted on servers but registered to consumer ISPs (Comcast, AT&T and similar). Combines residential-looking trust with datacenter consistency, usually sold per IP with unlimited bandwidth.
- **Mobile** — 4G/5G carrier IPs. The hardest to block and the most expensive.

9Proxy sits in the residential category, which is where most "buy proxies" traffic lands. Its pool is advertised at 20M+ residential IPs across 90+ countries, with targeting down to country, state, city, ZIP code and ISP, and both HTTP/HTTPS and SOCKS5 support. Datacenter proxies are listed as coming soon in third-party coupon pages that mirror its site, so today the residential range is the whole product.

## What you're actually buying from 9Proxy

Two residential models, with quite different plumbing:

- **Residential by IP** — fixed IP count, unlimited traffic, unused IPs never expire. Each IP lives a few hours up to about 24 hours depending on the IP. Access runs through the 9Proxy desktop app, which does local port forwarding; there's no dashboard-only path for this model.
- **Residential by GB** — buy traffic, generate unlimited endpoints, rotate per request or hold sticky sessions, authenticate with username/password or an IP whitelist. Runs entirely from the dashboard, no app required. Traffic validity is 180 days, or unlimited on Enterprise packages.

Both models use the same IP pool and the same targeting options. The GB side also supports multiple sub-users with assigned traffic, which is how agencies split bandwidth across clients, and 9Proxy's Team system puts one owner plus up to five members on a single Enterprise package with per-member traffic controls and activity logs.

If you'd rather see the current numbers yourself before reading further, 👉 [check 9Proxy's live package pricing and sign-up here](https://bit.ly/9-Proxy).

## Every 9Proxy package, with prices

These are the list prices after the June 1, 2026 adjustment, which raised IP-based and bundle pricing while leaving GB-based packages untouched. The GB tiers were the part 9Proxy explicitly kept flat.

### Residential by IP (unlimited bandwidth per IP, unused IPs don't expire)

| Package | Total price | Effective rate | Notes | Buy |
| --- | --- | --- | --- | --- |
| 100 IPs | $24 | $0.24 / IP | Smallest entry point for the IP model | [start with 100 IPs](https://bit.ly/9-Proxy) |
| 500 IPs | $72 | $0.144 / IP | Roughly a third cheaper per unit than the 100-pack | [get the 500 IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $126 | $0.084 / IP | Bonus IPs included, biggest jump in value at the low end | [take the 1,000 + 500 IP deal](https://bit.ly/9-Proxy) |
| 2,500 IPs | $210 | $0.084 / IP | Same per-IP rate as the tier above at higher volume | [order 2,500 IPs](https://bit.ly/9-Proxy) |
| 5,000 IPs | $360 | $0.072 / IP | Entry point for continuous multi-account work | [buy the 5,000 IP package](https://bit.ly/9-Proxy) |
| 15,000 IPs | $720 | $0.048 / IP | For ongoing scraping fleets | [get 15,000 IPs](https://bit.ly/9-Proxy) |
| 25,000 IPs | $863 | $0.035 / IP | Mid-tier reseller volume | [compare the 25,000 IP tier](https://bit.ly/9-Proxy) |
| 50,000 IPs | $1,438 | $0.029 / IP | Large-scale inventory | [order 50,000 IPs](https://bit.ly/9-Proxy) |

### Business IP packages (industrial volume)

| Package | Total price | Effective rate | Notes | Buy |
| --- | --- | --- | --- | --- |
| 100,000 IPs | $2,300 | $0.023 / IP | First Business tier | [see the 100,000 IP package](https://bit.ly/9-Proxy) |
| 200,000 IPs | $4,140 | $0.021 / IP | Per-unit cost drops again | [order 200,000 IPs](https://bit.ly/9-Proxy) |
| 500,000 IPs | $8,625 | $0.018 / IP | Lowest advertised per-IP price | [buy the 500,000 IP package](https://bit.ly/9-Proxy) |

### Residential by GB (180-day traffic validity, unlimited validity on Enterprise)

| Package | Total price | Effective rate | Notes | Buy |
| --- | --- | --- | --- | --- |
| 5 GB | $15 | $3.00 / GB | Cheapest way to test the network | [start with 5 GB for $15](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $105 | $2.10 / GB | Bonus traffic included | [get the 50 + 5 GB package](https://bit.ly/9-Proxy) |
| 100 GB | $150 | $1.50 / GB | Rotating-heavy workloads start making sense here | [buy 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | $200 | $1.00 / GB | Price per GB halves versus the entry tier | [order 200 GB](https://bit.ly/9-Proxy) |
| 1,000 GB | $800 | $0.80 / GB | Steady automation volume | [get 1,000 GB](https://bit.ly/9-Proxy) |
| 2,000 GB | $1,500 | $0.75 / GB | Last tier with the 180-day clock | [buy 2,000 GB](https://bit.ly/9-Proxy) |
| 3,000 GB (Enterprise) | $2,160 | $0.72 / GB | Traffic never expires, team features included | [see the 3,000 GB Enterprise package](https://bit.ly/9-Proxy) |
| 6,000 GB (Enterprise) | $4,200 | $0.70 / GB | Always-on pipelines | [order 6,000 GB Enterprise](https://bit.ly/9-Proxy) |
| 10,000 GB (Enterprise) | $6,800 | $0.68 / GB | Lowest advertised per-GB price | [buy the 10,000 GB Enterprise package](https://bit.ly/9-Proxy) |

### Bundle packages (IPs plus traffic, 180-day traffic validity)

| Package | Total price | Notes | Buy |
| --- | --- | --- | --- |
| 100 IPs + 5 GB | $30 | Starter mix for testing both models at once | [buy the Starter bundle](https://bit.ly/9-Proxy) |
| 1,500 IPs + 50 GB | $180 | Middle bundle for mixed workloads | [get the 1,500 IPs + 50 GB bundle](https://bit.ly/9-Proxy) |
| 5,000 IPs + 500 GB | $720 | Pro bundle, checks out at a discount versus buying separately | [order the 5,000 IPs + 500 GB bundle](https://bit.ly/9-Proxy) |

The advertised floor rates, $0.018 per IP and $0.68 per GB, only exist at the very top of the two ladders. If your budget is a few hundred dollars, your real rates are $0.084 per IP or somewhere between $1.00 and $3.00 per GB.

## Which of these should you actually buy

A short, opinionated map, based on the numbers above rather than on marketing copy:

- **Testing whether the network works for your target site:** the 5 GB package at $15. Small enough that a bad fit costs you a lunch, big enough to run real requests.
- **Running accounts that need to stay logged in:** per-IP. Unlimited traffic means a session that loads a heavy dashboard 400 times doesn't cost extra.
- **Scraping with rotation and small payloads:** per-GB. You never waste money on IPs sitting idle.
- **Mixed workloads:** bundles. The Pro bundle at $720 lists $860 worth of parts with a discount applied at checkout, so the bundle math works in your favor if you'd otherwise buy both.
- **Running client work or a small team:** Enterprise GB. Validity never expires and one package can cover five members.

The gap between the 5 GB package ($3.00/GB) and the 200 GB package ($1.00/GB) is the most consequential one in the whole table. Three times the price per unit for the same product, purely because of volume. If you know you'll consume 100 GB or more, buying it in 5 GB increments is an expensive way to stay flexible.

## How the purchase actually works

1. Create an account through the sign-up page.
2. Pick a model: Residential by IP, Residential by GB, or a bundle.
3. Choose the package size from the pricing page and hit Order Now.
4. Select a payment method at checkout and enter a coupon code if you have one.
5. For GB and bundle plans, generate endpoints in the dashboard's Proxy Generator — pick authentication, choose country/state/city/ZIP/ISP, set sticky or rotating, then export as .txt, .csv, or copy the credentials straight into your tool.
6. For IP-based plans, install the desktop app and forward ports locally. This step is unavoidable for that model.

Payment options include credit card (with GPay and Alipay as alternatives), region-specific local payment methods, cryptocurrency, and balance from the 9Proxy wallet. Support runs 24/7 by email, live chat and Telegram, which matters more than it sounds — a proxy purchase that goes wrong at 2 a.m. is a wasted night of scraping.

If you already know the model you want, 👉 [the sign-up page is where the package list and current discounts live](https://bit.ly/9-Proxy).

## Discounts: what's real and what's expired

9Proxy runs frequent promotions rather than one permanent discount. Documented examples include an April 2026 GB sale where the first GB order of the month automatically generated a personal 9% coupon for the next GB order, and a Lunar New Year campaign in early 2026 with an 8% code on regular IP and GB packages, plus limited-edition large packages. Some partner programs circulate smaller codes for specific tools.

Two caveats worth internalizing. First, those specific codes have expiry dates and most of the 2026 campaigns closed already, so any list of "working 9Proxy coupons" you find that cites them is describing the past. Second, the discounts aren't universal: the April GB coupon excluded bundle packages and IP-based plans. Check what the coupon applies to before assuming it drops your total.

Rather than trust a coupon aggregator's list, apply the code in the checkout field and watch the order summary before confirming. The summary line is the only place the real number shows up.

## What third-party reviews and user reports say

Independent coverage is thin but not empty, and it's worth reading with the usual filter for affiliate incentives.

Geekflare's 2026 review walks through both pricing models and describes a live test against a Cloudflare-protected e-commerce site, treating predictable access as the strongest selling point of the per-IP model. The proxy directory ProxyLook scores 9Proxy 3.9 out of 5 and notes a 20M+ residential pool across 90+ countries. G2 carries a single 5-star review from a cloud security architect who used it for geo-region security testing, which is a sample of one, not a consensus. SourceForge-sourced reviewer comments describe clean IPs that stay unblocked and straightforward setup; Product Hunt forum comments mention stability with anti-detect browsers like Dolphin Anty and AdsPower.

There's also the opposite signal, and it would be dishonest to leave it out. Third-party trackers and a reseller blog have reported service interruptions in mid-2026, with one URL-reputation scanner referencing user complaints and a YouTube video about an outage. Those sources have their own commercial interest in steering you elsewhere, or are automated scanners reading forum noise, so treat them as a reason to buy small and verify, not as a verdict on what you'll get today.

The practical takeaway from both directions: don't put your entire quarterly budget into a single top-up on any provider on the first order. Start with the $15 GB package or the 100 IP package, run your actual target workload for a day, and scale only if the success rate holds up.

## Details that catch buyers out after payment

These come from 9Proxy's own documentation and are the kind of thing you notice too late:

- **IP-based plans require the desktop app.** Local port forwarding is the mechanism. If your workflow lives in the cloud, use GB-based proxies instead — those authenticate by username/password or IP whitelist.
- **Residential IPs are not permanent on the IP model.** Expect a few hours to about 24 hours per IP. Unused IPs don't expire, but active ones rotate out.
- **GB traffic has a 180-day clock** unless you're on an Enterprise package, where it never expires. Buying 2,000 GB you won't use in six months is a real way to lose money.
- **Pricing changed on June 1, 2026** for IP and bundle packages. Older blog posts quoting $0.015 per IP or $20 for 100 IPs are out of date.
- **The cheapest per-unit rates require the largest commitments.** $0.018 per IP means buying 500,000 IPs.

## FAQ

**Is it cheaper to buy per IP or per GB?**
Depends entirely on payload size. If your average request pulls megabytes, per-IP with unlimited bandwidth wins. If requests are small and you rotate constantly, per-GB wins because you're not paying for IPs that sit idle. 9Proxy sells both models from the same pool, so the comparison is apples to apples.

**What's the smallest purchase I can make?**
The 5 GB package at $15 is the lowest-listed entry on the GB side, and 100 IPs at $24 on the IP side. That's enough to run a real test rather than a demo.

**Can I use these proxies with anti-detect browsers?**
Yes. SOCKS5 and HTTP/HTTPS are both supported, and third-party reviews specifically mention Dolphin Anty, AdsPower and BitBrowser working without extra configuration.

**Do I need to install software?**
For GB-based proxies, no — everything runs from the dashboard. For IP-based packages, yes, the desktop app is part of how the connection is routed.

**What happens if a proxy goes offline mid-session?**
9Proxy auto-refreshes offline IPs, and third-party write-ups describe replacement within roughly 60 seconds. Retry logic in your scraper or automation tool handles the gap.

## The short version

Pick your billing model from your workload, not from a provider's marketing page. Heavy pages and long-lived sessions mean per-IP with unlimited bandwidth; light, rotating requests mean per-GB. Then test with the smallest sensible package — $15 or $24 with 9Proxy — before committing real budget, because per-unit pricing only becomes genuinely cheap at volumes most people don't reach on their first order.

👉 [See 9Proxy's current packages and start with the smallest one](https://bit.ly/9-Proxy)
