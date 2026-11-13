# justhost asia: Is It Legit, What Does $1.99 Actually Buy, and Which of the Three Shared Plans Do You Need? (Full Price Table)

JustHost has been selling hosting since 2005, and its site currently reports 379,810 customers, 80 locations across 41 countries and 52,986 active VPS. The two prices that matter most are **shared hosting from $0.005 per month** on the Economy plan and a **VPS from $1.99 per month** with unmetered traffic and a free IPv6 address. Support runs 24/7 through live chat, email and a US phone number.

For most readers the VPS line is the interesting part: root access, a data centre location you can change from the client area, and billing based on disk space rather than transfer. If all you need is a WordPress site that stays online, one of the shared plans costs less than two dollars a month. Either way, settle one thing before you pay: **VPS accounts do not include automatic backups**.

> **Quick verdict**
> - Want a server you control: **VPS from $1.99/month**, with configurable CPU, RAM and disk, KVM virtualisation, free IPv6 and unlimited traffic. IPv4 is a separate **$3.31/month**.
> - Want a website: **Optimal from $1.16/month** billed yearly covers a normal site. Maximum at **$2.30/month** is for sites that genuinely hit resource limits.
> - The gap nobody mentions: no automatic backups on VPS. Shared hosting includes them.
>
> 👉 [Check the current VPS configurations and prices](https://justhost.asia/en/services/vps?tab=software&ref=196392)

## Full plan and price table

| Plan | Best for | Starting price | Billing | Order |
| --- | --- | --- | --- | --- |
| **Maximum** (shared) | Sites with high resource and speed demands | from $2.30/mo | billed yearly | [Order the Maximum plan](https://justhost.asia/en/maximal-plan?ref=196392) |
| **Optimal** (shared) | The balance most single sites need | from $1.16/mo | billed yearly | [Order the Optimal plan](https://justhost.asia/en/optimal-plan?ref=196392) |
| **Economy** (shared) | Tiny sites and tests, per-megabyte billing | from $0.005/mo | per-megabyte billing | [Order the Economy plan](https://justhost.asia/en/econom-plan?ref=196392) |
| **VPS / VDS** | Root access, custom software, scaling | from $1.99/mo (the IPv4 + IPv6 page says from $2.91/mo) | monthly rate | [Configure a VPS](https://justhost.asia/en/services/vps?tab=software&ref=196392) |

Two notes on that table. JustHost doesn't publish a fixed spec sheet for VPS tiers; CPU cores, RAM and disk are chosen in a configurator, so there is no per-tier row to copy and the entry price is what you can compare. And the VPS entry price appears in two versions on the site: **$1.99** on the VPS service page and **$2.91** on a page describing "VPS server on IPv4 + IPv6". The difference is $0.92, while a standalone IPv4 address costs $3.31/month, so the two figures probably describe different base configurations rather than a simple IPv4 add-on. JustHost doesn't explain it. Check the configurator before you assume which one you're buying.

## Is JustHost a real company?

The site has been running under the same "here for you since 2005" line, and the "21 years in business" figure on the page lines up with that date. The numbers above (customers, locations, countries, active VPS) are self-reported, not audited, but the contact structure behind them is unusually complete for a budget host: **info@justhost.asia** for general enquiries, **support@justhost.asia** for technical issues, **finance@justhost.asia** for billing, **refunds@justhost.asia** for refunds, plus live chat and **+1 (917) 938-7088**.

The four testimonials on the shared hosting page are selected by JustHost and carry no score or third-party verification. Read them as marketing. What they consistently describe is fast setup and support staff fixing software problems, including PHP scripts on a customer's site. That is consistent with the 24/7 support claim, but it is not a sample you can draw conclusions from.

## What every VPS plan includes

The inclusions are the same across the VPS range, which makes the configurator the only real decision:

- **Unmetered traffic.** JustHost's wording is that you only pay for disk space and every plan includes unlimited traffic.
- **A free IPv6 address.** The page explicitly frames this as the budget option: no need to buy an IPv4 address.
- **Location switching at any time** from the client area, without reinstalling.
- **IP changes at any time**, also from the client area.
- **SSH access**, so git, bash scripts and file edits work as they would on any server.
- **DDoS protection** applied in layers, combining traffic monitoring with mechanisms that block attacks as they start.
- **SSD and NVMe storage** across the VPS line.
- **Free migration** from another provider: files, databases and server settings moved with no downtime, provided you hand over access to the current host.
- **Resizing without migrating.** You can add CPU cores, RAM or disk to an existing VPS, with minimal downtime.
- **Optional managed services**, priced separately from the plan.

## The thing most reviews skip: no automatic backups on VPS

The VPS FAQ answers this directly: no, JustHost does not offer automatic backups, and the suggestion is to set up your own backup server and keep copies on a separate machine.

Shared hosting works the other way. The hosting page lists backups as an included feature, says they run automatically on a schedule, and lets you change the frequency or keep copies on a separate server.

That difference changes what a $1.99 VPS really costs you. A cheap VPS with no snapshot and no automatic dump means you own the backup problem: a cron job pushing dumps to object storage, or a second small server. Neither is expensive, but it is work, and it is the step people skip until they need it. If you would rather not run that, the shared plans include backups and start at a lower price.

👉 [Compare the shared plans that include backups](https://justhost.asia/en/services/hosting?ref=196392)

## What $1.99 doesn't cover

The add-on list is where a budget VPS stops being $1.99:

| Extra | Price |
| --- | --- |
| IPv4 address | $3.31/month |
| +10 Mbps bandwidth | $2.50/month |
| Dedicated 1 Gbps bandwidth | $333.33/month |
| Sysadmin services | $9.16/hour |

Read those together and the shape of the offer becomes clear. The base plan is designed to run on IPv6 with a modest port, which is fine for a VPN endpoint, a bot, a staging box, a small API or a Git remote. Add IPv4 and you're at roughly $5.30/month before you've bought any extra speed. If your traffic needs a wider port, bandwidth becomes the line item that grows.

The sysadmin rate is the other number worth internalising: **one hour of JustHost's admin time costs more than two months of the cheapest VPS**. That is normal for hourly admin work, and it tells you what the plan assumes. This is unmanaged hosting. If you can't debug a broken PHP build or a full disk yourself, budget for the managed option or pick shared hosting instead.

👉 [Open the VPS configurator and see add-on pricing](https://justhost.asia/en/services/vps?tab=software&ref=196392)

## Shared hosting: Maximum, Optimal or Economy?

All three plans carry an identical feature list: unlimited websites, databases, FTP accounts, mailboxes and traffic, CloudLinux isolation between accounts, one-click CMS installs, a free test domain, SSH, IPv6 out of the box, a site builder that can import from other builders, and backups. Features are not how you choose here. Resources and billing model are.

**Optimal ($1.16/month, billed yearly)** is positioned as the balance for a normal website running modern software. One WordPress site with a few plugins sits here comfortably.

**Maximum ($2.30/month, billed yearly)** is positioned for sites with high resource and speed demands. The price gap is small, so the honest question is whether your site actually hits limits on Optimal. If it doesn't, the extra spend buys nothing you'll notice.

**Economy ($0.005/month)** uses per-megabyte billing. The page heading calls it "unlimited disk space" while billing per megabyte, which reads as no hard cap plus metered charges for what you use. That suits a placeholder page, a test install or a low-traffic site with almost no files. What JustHost doesn't publish in the material available here is how the per-megabyte rate maps to a real site's disk usage, so if you expect more than a few hundred megabytes, ask support for a worked example before choosing it over Optimal.

## Trial, refunds, payment methods and support

JustHost offers a free trial on **some** of its services, usually **7 to 14 days depending on the service**. During that window you can use the full feature set, or ask for a full refund. There is no separate money-back period stated beyond that, so treat the trial as your evaluation window rather than assuming a standard 30-day guarantee.

Payment methods listed on the site: bank cards (Visa, MasterCard, Mir), e-wallets such as Yandex.Money or WebMoney, and bank transfer. Auto-renewal is available.

Support is 24/7 by live chat, email and phone, and the sales-side addresses are separate from technical support, which matters when a billing problem is blocking a deployment. Upgrades happen in the control panel, and JustHost says the resource increase applies with no significant downtime.

👉 [Start with the Optimal plan at $1.16/month](https://justhost.asia/en/optimal-plan?ref=196392)

## Who should not buy JustHost

- **Anyone who needs automatic backups and won't build their own.** Take shared hosting, or budget a second server for dumps.
- **Anyone who needs IPv4 on the cheapest tier without extra cost.** It's $3.31/month on top.
- **Anyone who needs published per-tier VPS specs before ordering.** The configurator is the spec sheet; there's no PDF to compare against competitors.
- **Anyone who wants a large body of independent reviews.** What's on the site is self-selected. There's no score to lean on.
- **Anyone who needs local-language phone sales.** There's one US number plus chat and email.

## FAQ

**Can I change the server location after purchase?**
Yes. Location switching is listed as included on every VPS plan and is done from the client area at any time.

**Is traffic really unlimited?**
The volume is. What's capped is port speed: extra bandwidth is sold at $2.50/month for +10 Mbps, and a dedicated 1 Gbps port is $333.33/month. A busy site will hit the port before it hits a transfer quota.

**Do I have to buy IPv4?**
No. A free IPv6 address comes with every VPS, and JustHost frames that as the budget option. Buy IPv4 only if your users or software need it, at $3.31/month.

**Can I upgrade without migrating my data?**
Yes. Add CPU cores, RAM or disk from the panel; JustHost says changes apply with minimal downtime and no data migration.

**Do I need my own backup setup on a VPS?**
Yes. There are no automatic backups on VPS. Shared hosting includes scheduled backups with adjustable frequency.

**Does JustHost sell anything besides shared hosting and VPS?**
Yes, dedicated servers are the third product line. Pricing for them isn't published on the pages reviewed here, so ask support directly if you need bare metal.

## Which one to order

A placeholder page, a test install or a site with almost no files: **Economy at $0.005/month**, and confirm the per-megabyte maths with support first. One normal WordPress site: **Optimal at $1.16/month billed yearly**. Several sites or a site that keeps hitting resource ceilings: **Maximum at $2.30/month billed yearly**. Root access, custom software, a VPN endpoint or a box you'll resize as you grow: **VPS from $1.99/month**.

Before you pay, answer two questions. Does your project need an IPv4 address, because that's $3.31/month on top and it changes the real monthly figure. And where will your backups live, because on a VPS that answer is entirely yours.

👉 [Pick your JustHost plan and check today's pricing](https://justhost.asia/?ref=196392)
