# windows vps hosting: real prices compared, how to choose a plan, and when LisaHost's China-optimized RDP servers are worth it

People searching for windows vps hosting are usually after the same core thing: a Windows machine that stays online around the clock, reachable by Remote Desktop, so a trading platform, a bot, or some Windows-only piece of software keeps running whether you're connected or not. The market for that is mature and, on the surface, cheap. Current listed entry prices across five established providers — Cloudzy, Hostwinds, Contabo, InterServer, and DatabaseMart — run from **$3.48 to $14.94 per month**, and every one of them includes full RDP access.

Price alone won't decide it, though. Three things vary far more than the monthly number: what the Windows licensing situation actually is (at least one major provider ships a trial license and expects you to activate your own), what happens to the price when a promo period ends, and — the factor that rarely shows up in comparison articles — how fast the server is from *where you connect*. If you RDP in from mainland China, or your MT4/MT5 terminal needs a stable path to broker servers, route quality buys you more than an extra 4GB of RAM. That's where LisaHost enters the picture.

Here's the short version, then the details.

> **Quick pick:** If you need a Windows VPS that stays responsive from mainland China — MT4/MT5 terminals, cross-border store dashboards, or just a smooth RDP desktop — LisaHost's 4GB plan (2 vCPU, 4GB RAM, 60GB SSD, $34.99/mo) is the practical middle ground, and the 2GB plan at $19.99/mo covers lighter bot workloads. 👉 [Check LisaHost's Windows VPS plans and current prices](https://bit.ly/lisaHost) — Alipay, WeChat Pay and PayPal are accepted. If China latency means nothing to you, jump straight to the price comparison below; cheaper Western options exist.

## What "windows vps hosting" should actually include

A Windows VPS is a slice of a physical server running Windows Server, rented monthly, with Remote Desktop login and full administrator rights. Whatever brand you pick, the baseline should look the same: you can RDP in as administrator and install your own software, the operating system is licensed and ready, and your programs keep running after you disconnect.

That last part trips up first-time buyers more than anything else. Closing the RDP window on a proper Windows VPS is like walking away from a machine that stays switched on — your MT4 terminal keeps placing orders, your scraper keeps scraping. InterServer describes this behavior explicitly on its own product page, and it's standard across every provider compared here. If a seller's "Windows VPS" behaves like a session that dies when you log off, it isn't doing the one job you're paying for.

## LisaHost Windows VPS: plans and prices

LisaHost currently sells its Windows VPS line in four monthly tiers, from a 2GB entry plan at $19.99 up to a 16GB plan at $99.99, all with full administrator RDP access.

| Plan | Config | Monthly traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- |
| Windows VPS 2GB | 2 vCPU · 2GB RAM · 40GB SSD | 1 TB | $19.99 | [ Order](https://bit.ly/lisaHost) |
| Windows VPS 4GB | 2 vCPU · 4GB RAM · 60GB SSD | 2 TB | $34.99 | [ Order](https://bit.ly/lisaHost) |
| Windows VPS 8GB | 4 vCPU · 8GB RAM · 100GB SSD | 4 TB | $59.99 | [ Order](https://bit.ly/lisaHost) |
| Windows VPS 16GB | 8 vCPU · 16GB RAM · 200GB SSD | 6 TB | $99.99 | [ Order](https://bit.ly/lisaHost) |

A few practical notes that sit outside the pricing table:

- **Operating system**: Windows Server 2016, 2019 and 2022 templates at the time of writing. Pick 2022 unless you're stuck with a legacy app — its support window runs into the early 2030s.
- **Locations**: the US line runs through Los Angeles with China-optimized CN2 GIA routing; additional Asian locations are available, and the exact list changes, so check it at checkout.
- **Payment**: Alipay and WeChat Pay work alongside PayPal and cards, which is still rare in this market.
- **Refunds**: terms vary by product line. Confirm the refund policy on the order page before paying instead of assuming a money-back window exists.
- The prices shown are monthly rates; longer billing terms may shift the number, so glance at the order form before committing.

## Who LisaHost is actually for (and who should skip it)

LisaHost earns its slot in this comparison on one specific strength: connection quality to and from mainland China. Most budget US VPS traffic crosses congested public transit on the way to Chinese networks, and evening latency plus packet loss reflect that. CN2 GIA is China Telecom's premium backbone — reserved capacity, far fewer users on it, noticeably steadier round trips at peak hours — and LisaHost built its reputation on exactly these Los Angeles lines.

Why that matters in practice:

- **Trading**: an MT4/MT5 terminal sitting in Los Angeles on a CN2 GIA route gives a China-based trader a shorter, steadier path to US broker servers than a random budget datacenter. Execution quality depends on the whole route, and LisaHost is the one provider here that treats the China side of that route as the product.
- **RDP desktop from China**: if your "office computer" lives in the US and you reach it every evening from a Chinese city, peak-hour smoothness is the difference between workable and infuriating.
- **Chinese-speaking teams**: support in Chinese plus Alipay/WeChat billing removes the friction that stops a lot of buyers from even signing up with US-facing hosts.

If none of that describes you, skip LisaHost without guilt. A user in Europe or the Americas running a scraper for Western sites gains nothing from a China-optimized route and would be better served by a big-name Western host — Cloudzy, for instance, lists 13 regions, a public status page, a 4.6/5 Trustpilot score from 715+ reviewers, and a 14-day money-back guarantee with entry pricing from $3.48/mo. Specs per dollar isn't LisaHost's game; route quality is. 👉 [See LisaHost's US CN2 GIA Windows VPS options](https://bit.ly/lisaHost)

## How the big-name providers compare on real prices

On paper, entry-level Windows VPS pricing spans $3.48 to $14.94 a month. Match the specs and the picture gets more interesting — the same 4GB RAM class runs from $4.94 to $33.79 depending on who's selling it.

| Provider | Cheapest listed Windows plan | Specs | Listed price | Fine print worth knowing |
| --- | --- | --- | --- | --- |
| DatabaseMart | Express Windows | 2 cores · 4GB · 60GB SSD · 100Mbps unmetered | $4.94/mo (was $8.99) | US data centers only; Server 2025/2022/2019/2016; 99.9% uptime guarantee |
| InterServer | 2 slices | 1 core · 4GB · 80GB SSD · 4TB transfer | $10/mo | Windows needs a 2-slice minimum; managed support kicks in at 8 slices; 10Gbps shared port |
| Cloudzy | 4GB tier | 2 vCPU · 4GB DDR5 · 120GB NVMe · 5TB | $14.48/mo (50% off $28.95) | 14-day money-back; trial license or BYOL; 13 regions; 99.95% SLA |
| Hostwinds | Managed, 4GB tier | 2 CPU · 4GB · 75GB SSD · 2TB | $33.79/mo (from $51.99) | Fully managed with nightly backups; unmanaged pricing roughly halves the cost; Server 2012/2016/2019 |
| Contabo | Cloud VPS 4 | 4 vCPU · 8GB · 100GB SSD · 200 Mbit/s | €5.50/mo | Price set for the first 24 months; unlimited traffic; Server 2025/2022/2019/2016 preinstalled |

Read the fine-print column and the spread makes sense. Hostwinds charges for human beings: it's the only fully managed service in the table, and its own site says going unmanaged cuts the price roughly in half. Contabo takes the raw-spec crown — 8GB for €5.50 is the most hardware per euro in this list — but the 200 Mbit/s port is the slowest here and the price is locked for the first 24 months, then moves. Cloudzy is selling modern hardware (DDR5, NVMe-only storage, AMD EPYC) and a wide region list. DatabaseMart trades region choice and port speed for the lowest number.

### What the sticker price doesn't tell you

Four things recur in this market that most comparison tables skip:

1. **Promo-period pricing is not the price.** Contabo's €5.50 applies to the first 24 months. Hostwinds shows list price and a discounted one side by side. Cloudzy's entire table is currently 50% off. None of that is a scam, but build your month-25 budget on the renewal figure rather than the launch figure.
2. **The Windows license may or may not be in there.** Cloudzy states plainly that plans ship with a trial license or BYOL (bring your own license). Others preinstall a licensed Server image. When a $5 plan sits next to a $15 plan, check whether the difference is mostly a license.
3. **Version support windows are finite.** Server 2022 is the current long-term channel with support listed into the early 2030s; Server 2012 is legacy territory. Contabo already offers Server 2025 with hotpatching — updates without a reboot — which matters for anything that needs maximum uptime. Match the version to your software first.
4. **Traffic and port speed decide real-world feel.** DatabaseMart is unmetered but capped at 100Mbps; InterServer bundles 4TB on its 2-slice plan; Hostwinds' entry tier includes just 1TB. A media-heavy workload on a 1TB cap will hurt faster than low RAM will.

## How to choose a plan in three rules

Region first, RAM second, management level last — in that order.

**Rule 1: the route decides before the specs do.** Trading against a specific broker? Host the terminal near the broker's servers; Cloudzy markets exactly this, letting you pin a region close to your broker for lower execution latency. Users, or your own desktop, connecting from China? The CN2 GIA route is worth paying for, which puts LisaHost first. Everything else — generic US or EU workloads — any of the five Western providers will handle.

**Rule 2: buy RAM for what runs, not what might run.** Windows Server consumes around 2GB before you've launched anything. One or two trading terminals plus light automation sit comfortably in 4GB; Cloudzy's own tiering labels its 8GB tier "trading apps, small sites" and its 12GB tier "production apps, multi-user RDP", which is a fair map to copy. Don't buy 16GB "just in case" — upgrading later on a monthly plan costs you nothing but a reboot.

**Rule 3: decide who fixes it when it breaks.** Hostwinds includes full management and nightly backups using Windows shadow copy; InterServer includes managed support from 8 slices up. Everyone else assumes you're the administrator. If you've never opened Server Manager or IIS, either pay for managed or block out an evening to learn the basics — an unmanaged $5 server stays cheap until the first blue screen.

👉 [Open LisaHost's Windows VPS order page — Alipay and PayPal accepted](https://bit.ly/lisaHost)

## FAQ

**How much RAM does a Windows VPS actually need?**
2GB is the workable floor for Windows Server itself. Start at 4GB the moment anything else runs on the box — a trading terminal, a browser automation job, a small IIS site. 8GB and up is for multi-user RDP or desktop software like Office and Power BI.

**Do my programs keep running after I close the RDP window?**
Yes, and that's the entire point of the product. Your terminal, bot, or download continues on the server after you disconnect, across all the providers compared here.

**Do I have to buy a Windows license separately?**
Depends on the provider. Cloudzy ships a trial license or accepts BYOL; Contabo and Hostwinds preinstall licensed Server images; InterServer includes RDP access in the slice price. Confirm the licensing line on the order page — it's the most commonly misunderstood part of a cheap Windows VPS.

**Is a $5 Windows VPS too good to be true?**
No, but read the corners being cut. DatabaseMart's $4.94 plan is US-only at 100Mbps; Contabo's €5.50 is a first-24-months rate on a 200 Mbit/s port. For a headless bot box, those corners often don't matter. For a desktop you stare at all day, they do.

## Before you click order

Match your situation to one of these and you're done:

- **Trading or RDP from mainland China** → LisaHost's 4GB plan on the CN2 GIA line. Run a ping and an mtr from your own network to the datacenter before moving real workloads; the route is the product, so test it like one.
- **Region choice and a safety net** → Cloudzy's 14-day money-back window and 13 regions make it the lowest-risk Western option in this lineup.
- **Someone else on call** → Hostwinds' managed tier, or InterServer at 8 slices and up.

Three things to confirm on any order page before paying: the refund terms, whether the Windows license is included or trial/BYOL, and the renewal price after any promo period ends. Screenshot the checkout — future you will want the receipt. If the China route is your deciding factor, 👉 [order LisaHost's Windows VPS here](https://bit.ly/lisaHost) and treat the first month as your live latency test.
