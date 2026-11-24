# VPS Hosting Coupon: What a Discount Really Saves, Evoxt's Full Plan List From $2.99/Month, and Which Plan You Should Skip

A VPS coupon usually shaves a few dollars off the first invoice and nothing off the eleven that follow. Evoxt's price list works differently: one number per plan, no struck-through "regular" price, from $2.99/month for VM-0.5 up to $95.99/month for VM-16, with billing cycles running from monthly to three years. That makes the plan you pick the expensive decision and the coupon the small one.

Below is the full plan table, the arithmetic on what a percentage discount is genuinely worth on a $5.99 plan, the two plans most people should skip, and the numbers to check on the invoice before you pay.

> **Quick pick:** VM-1 at **$5.99/month** gets you 1 core, 2 GB RAM, 20 GB storage and 500 GB monthly transfer, with weekly offsite backup included. It is the cheapest Evoxt plan that can run a web server and a small database on the same box, and twelve months at list price comes to $71.88. 👉 [Check VM-1's price and deploy](https://bit.ly/EvoXt)

## The full Evoxt plan list

Every plan Evoxt currently publishes, in USD, billed monthly unless you pick a longer cycle at checkout.

| Plan | vCPU | RAM | Storage | Price (USD/month) | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 core | 512 MB | 5 GB | $2.99 | [ Deploy VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core | 1 GB | 10 GB | $4.99 | [ Deploy VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 core | 2 GB | 20 GB | $5.99 | [ Deploy VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores | 2 GB | 20 GB | $6.95 | [ Deploy VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 cores | 4 GB | 30 GB | $11.99 | [ Deploy VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 cores | 4 GB | 30 GB | $14.99 | [ Deploy VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 cores | 8 GB | 60 GB | $23.99 | [ Deploy VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 cores | 8 GB | 60 GB | $29.99 | [ Deploy VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 cores | 16 GB | 80 GB | $47.99 | [ Deploy VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 cores | 16 GB | 80 GB | $60.95 | [ Deploy VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 cores | 32 GB | 100 GB | $95.99 | [ Deploy VM-16](https://bit.ly/EvoXt) |

Evoxt advertises CPU boosts up to 6.0 GHz+ on these plans, and marks every one of them as including weekly offsite backup at no extra charge.

The same list with the two numbers that decide most purchases, bandwidth and annual cost:

| Plan | Monthly transfer | 12 months at list price | Typical fit |
| --- | --- | --- | --- |
| VM-0.5 | 250 GB | $35.88 | One static site, a DNS node, a single tiny service |
| VM-0.75 | 250 GB | $59.88 | One lightweight app with a small database |
| VM-1 | 500 GB | $71.88 | Web server plus database on one box |
| VM-1.5 | 500 GB | $83.40 | Same as VM-1 with a spare core for spikes |
| VM-2 | 1,000 GB | $143.88 | Several services; 4 GB is the usual ceiling |
| VM-3 | 1,000 GB | $179.88 | Build jobs and workers that need cores, not RAM |
| VM-4 | 2,000 GB | $287.88 | Bigger databases, JVM apps, 8 GB workloads |
| VM-6 | 2,000 GB | $359.88 | Same RAM as VM-4 with twice the cores |
| VM-8 | 3,000 GB | $575.88 | 16 GB and 8 cores, heavy concurrency |
| VM-12 | 3,000 GB | $731.40 | 16 cores, RAM unchanged from VM-8 |
| VM-16 | 5,000 GB | $1,151.88 | 32 GB and 16 cores |

Annual figures are list price × 12, not a prepay quote. Evoxt bills from monthly up to three years, and the total you see at checkout is the one that counts.

## What a coupon is actually worth on a $5.99 plan

Take VM-1. A 40% discount on the first invoice only drops month one to $3.59 and leaves months two through twelve at $5.99: $3.59 + $65.89 = **$69.48 for the year**, or $2.40 below list. The same 40% applied to every invoice gives $3.59 × 12 = **$43.13**, which is $28.75 below list. Identical headline number, twelve times the difference.

That is the only distinction worth checking on a coupon page: whether the discount survives renewal. Wording like "recurring" or "renews at the same price" means the lower rate repeats. A page that only says "first month" or "first term" is selling you a one-off, and on a $5.99 plan a one-off is worth about the price of a coffee.

Evoxt's own table does not show a separate first-term rate and renewal rate. Each plan carries a single price, so the lever you control is the billing cycle you select at checkout and any promo code the order form accepts. 👉 [See the full Evoxt plan table and billing options](https://bit.ly/EvoXt)

## The plan ladder: are you paying for cores or for RAM?

Evoxt raises core count faster than memory in some steps and memory faster than cores in others, and the price gap tells you which upgrades are cheap.

VM-1 to VM-1.5 costs **$0.96 more** and doubles the cores from 1 to 2, with RAM, storage and transfer unchanged. VM-2 to VM-3 costs **$3 more** and takes you from 2 cores to 4, again without touching RAM. VM-4 to VM-6 costs **$6 more** for 4 cores to 8. If your workload is CPU-bound, such as compiles, video transcodes, crawlers or game servers, those three steps are the best value in the list.

If you are short on memory instead, the ladder gets steeper. Going from 4 GB to 8 GB means VM-2 at $11.99 jumping to VM-4 at $23.99, exactly double. There is no cheap middle step, so size your RAM requirement before you order, not after.

Two plans deserve a skip:

- **VM-0.75.** At $4.99 it sits exactly $1 below VM-1, which has twice the RAM and twice the storage. Unless a dollar genuinely decides the purchase, take VM-1.
- **VM-12.** At $60.95 it doubles VM-8's cores while leaving RAM at 16 GB. If you need 32 GB, VM-16 at $95.99 is the only option, and if you don't, VM-8 already covers 8 cores and 16 GB for $13 less per month.

## What's bundled that coupon roundups leave out

Three things on Evoxt's price and product pages change the real cost, and none of them appear in a discount headline:

- **Weekly offsite backup on every plan**, including the $2.99 one. Many hosts charge extra for this or reserve it for higher tiers.
- **Extra IPv4 addresses at $3/month each.** If your project needs additional public IPs, budget for them; they are not part of the plan price.
- **Per-resource upgrades.** Evoxt lets you add individual resources to a VM without moving to a different plan, so a RAM shortfall does not force a full migration to VM-4.

The buy page also lists monitoring, firewall rules you set outside the guest, VM cloning, floating IP reassignment, a browser VNC console, and both Windows and Linux templates. 👉 [Start with the $2.99 VM-0.5 plan](https://bit.ly/EvoXt)

## Coupons for Evoxt: what you can and cannot verify

At the time of writing, Evoxt's own pricing page displays no public promo code, no banner and no countdown. Third-party coupon aggregators do list Evoxt discounts, including one page advertising "40% off" with an expiry date of 19 November 2026. None of the listings we checked prints a code value you can test, and the same aggregators state in their own guidance that most providers accept one promo code per order and that many codes are restricted to new customers.

The practical sequence is: put the plan in the cart, paste whatever code you found into the promo field, and read the invoice total. If the number does not drop, remove the code and do not pay on the assumption that it worked. A discount you cannot see on the invoice is not a discount.

## Who should not buy one of these

Evoxt's list is a set of self-serve virtual machines with a management console. If you want a host to handle updates, tune the stack and answer the phone, this is the wrong shelf, and no coupon fixes that.

The 512 MB plan deserves its own warning. Modern control panels and most one-click stacks expect more memory than that, so VM-0.5 makes sense for a static site, a DNS or VPN endpoint, or a single small service with a light footprint. If you plan to install a panel and a database, start at VM-1.

Anyone needing several public IPv4 addresses should price those in at $3/month each before comparing against another host, because a $2.99 plan with three extra IPs is a $11.99 plan.

## FAQ

**Can I stack two Evoxt coupons on one order?**
Unlikely. Coupon aggregators that track VPS hosts note that most providers permit one promotional code per transaction, and user-submitted reviews on those same sites repeat the one-code-per-order line for Evoxt. Apply both if you want, then keep whichever produces the lower total.

**Do existing customers get the same discount?**
Many VPS codes are new-customer only. Try the code on a renewal invoice and check the total; if it fails, ask support whether a manual credit is possible. Do not prepay three years on the assumption that a first-term code will keep applying.

**Will the price go up at renewal?**
Evoxt publishes one price per plan, without a separate first-term and renewal rate. Before committing to a longer cycle, open the client area and confirm the amount the next invoice will show. That is a two-minute check that removes the biggest unknown in VPS pricing.

**Is prepaying a year or three worth it?**
Only if checkout quotes a lower total than twelve monthly payments. At the list prices above, a year of VM-1 is $71.88 whether you pay monthly or annually, so the case for prepaying rests on a discount you can see on the invoice. Prepaying three years on VM-16 commits $3,455.64, which is real money to tie up for a price that may not move.

## Before you pay

Match the plan to the constraint you actually have. Running a small site or a single service? VM-0.5 at $35.88/year or VM-1 at $71.88/year, and skip everything above them. CPU-bound work on a tight budget? VM-1.5 at $6.95 is the cheapest meaningful step up. Database or JVM workloads? Go straight to VM-4 at $23.99, because there is no cheap path from 4 GB to 8 GB. Need 32 GB? VM-16 is the only door.

Then confirm two things on the order page: the invoice total after any promo code, and the amount the following invoice will show. If both match what you expected, the purchase is straightforward. 👉 [Compare Evoxt's plans and pick your billing cycle](https://bit.ly/EvoXt)
