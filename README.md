# cpanel reseller hosting: what plans really cost at renewal, and when a cheap VPS beats a turnkey package

Most people searching for cPanel reseller hosting want one of two things: a white-label plan they can resell under their own brand, or a cheaper way to run the same thing on infrastructure they control. Both exist, and the price gap between them is bigger than most comparison posts admit. Turnkey reseller plans currently run from about $5/month at the low end to $50–$59/month for serious capacity, while a do-it-yourself setup — a KVM VPS plus a cPanel/WHM license — can cost a fraction of that if you're willing to manage the server yourself.

This article covers both routes. It compares current entry plans from hosts that actually publish their numbers, then digs into the detail most listicles skip: renewal pricing. Depending on the host, your second year can cost the same, 80% more, or 150% more than your first. Then we'll work through when the DIY route — building your reseller business on a budget VPS from a specialist like RackNerd — makes more sense than buying a turnkey package.

> **Quick picks**
> - **Cheapest turnkey start:** Asura Hosting's Reseller 1 plan at $4.99/mo — 25 GB NVMe storage, 5 cPanel accounts, LiteSpeed and CloudLinux included, no advertised renewal hikes.
> - **Safest exit ramp:** InMotion Hosting — 90-day money-back guarantee (the longest in the reseller market), free WHMCS, from $19.99/mo.
> - **Lowest cost per client, if you're technical:** skip the reseller package. Get a RackNerd KVM VPS, attach a cPanel/WHM license, and manage the server yourself. 👉 [check RackNerd's current KVM VPS deals and cPanel license add-on pricing](https://bit.ly/my-rn)

## What cPanel reseller hosting actually gets you

A reseller plan gives you two panels instead of one. WHM (Web Host Manager) is yours: it's where you create hosting packages, spin up client accounts, set resource limits, and brand the whole experience. cPanel is what your customers log into, to manage their own files, email, and databases.

Around those two panels, a good reseller plan bundles the plumbing that turns you into a hosting company: white-label branding so clients see your name instead of your upstream provider's, private nameservers, a website builder, free SSL certificates, and billing software (WHMCS or Blesta) so you can invoice automatically. Overselling support — letting you sell more total disk than you physically have, on the assumption that clients won't use it all — is standard on plans like Asura's.

What you don't get is the server itself. The upstream provider keeps it patched and online; you never touch the command line. That's the whole value proposition of a turnkey plan, and the main thing you give up on the DIY route.

## What entry plans cost right now

The entry tier is where most people start, and the spread is wide: $4.99/month at Asura Hosting versus roughly $20/month at the bigger names. Aggregator CloudsPress, which tracked 47 cPanel reseller hosts in September 2026, puts the median entry price at $19.80/month — but the median and the best deal for you are different things if you're starting with five clients.

| Host | Entry price | Renewal | Storage | Client accounts | Worth knowing |
| --- | --- | --- | --- | --- | --- |
| Asura Hosting | $4.99/mo | no advertised hikes | 25 GB NVMe | 5 | LiteSpeed, CloudLinux, Imunify360, free migration |
| Verpex | $19.80/mo | $22.00/mo (+11%) | 50 GB NVMe | 15 | 30-day refund, 9 data centers |
| Namecheap | $19.88/mo | same price | 30 GB SSD | — | ranked #1 on CloudsPress's 2026 list, 99.99% SLA |
| ScalaHosting | $19.95/mo | same price | 50 GB SSD | 20 sites | fully managed |
| GreenGeeks | $19.95/mo | not published | 60 GB SSD | — | 300% green energy match, free WHMCS |
| InMotion Hosting | $19.99/mo | $35.99/mo (+80%) | 80 GB SSD | 25 cPanel licenses | 90-day refund, free WHMCS, 1 dedicated IP |

A few outliers deserve a mention. HostSEO lists an unlimited-storage tier at $74.95 every six months with billing software included, and GURU (UK) advertises entry plans at $1.33/month — though neither publishes renewal pricing, which should make you read the fine print twice. GreenGeeks sits at the same ~$20 mark as the big names but offsets 300% of its energy use, if that fits your brand story.

Watch the account counts, not just the storage. Asura's $4.99 plan caps you at 5 cPanel accounts; InMotion's $19.99 plan includes 25 cPanel licenses. If you already know you'll have 20+ clients, the cheapest tier is a false economy.

## Renewal prices: the line item that decides year two

Here's the detail most comparison posts skip, and it's the one that actually determines what you'll pay over a couple of years. Several hosts advertise a low first-year rate, then move you onto a higher renewal price.

The InMotion math: the R-1000N plan costs $19.99/mo in year one ($239.88), then renews at $35.99/mo ($431.88/yr) — an 80% jump. The flagship R-4000N goes from $49.99 to $109.99/mo, a $720/year difference at renewal. Verpex is steeper on its bigger plans: Reseller 30 renews at +100% ($24.50 → $49.00/mo) and Reseller 60 at +150% ($27.60 → $69.00/mo).

CloudsPress's 2026 data puts this in context: of the 47 qualifying hosts, only 11 even publish a renewal price, and the median renewal among them is $20/month. Four hosts never raise the price at all. Namecheap and ScalaHosting are the notable big names whose entry plans renew at the same rate, and Asura explicitly advertises no renewal price hikes. So the question to ask before buying anything is: what does this plan cost in month 13?

## Turnkey plan or DIY VPS: picking your route

There are only two real ways to run a cPanel hosting business, and the right one depends mostly on how comfortable you are owning server administration.

|  | Turnkey reseller plan | RackNerd VPS + cPanel license |
| --- | --- | --- |
| Who runs the server | the provider | you |
| Typical cost | roughly $5–$59/mo per plan | one cheap annual VPS + a monthly license |
| Support for your clients | server-side issues handled upstream | entirely you |
| Best for | agencies adding hosting to existing services | technical owners maximizing margin |

### Where turnkey reseller plans earn their keep

You buy a plan, the provider runs the server, and you sell. Asura bakes in LiteSpeed, CloudLinux, Imunify360 malware protection, and JetBackup; InMotion includes WHMCS free and throws in dedicated IPs; HostSEO's top tier is fully managed with end-user support. If your actual business is web design and you're adding hosting for existing clients, this is the route — your billable hours are worth more than the markup you're paying the provider.

### The RackNerd route: a KVM VPS plus a cPanel license

RackNerd's catalog centers on KVM VPS and dedicated servers rather than white-label reseller packages — data centers across the US (Los Angeles, San Jose, Dallas, and New York among them) plus Amsterdam. For this purpose that's a different deal, not a lesser one. You buy an unmanaged KVM VPS at aggressively cheap annual pricing, attach a cPanel/WHM license as an add-on, and you're the root administrator of your own small hosting company: full WHM, your own packages and limits, your own nameservers, and room to host your own sites alongside client accounts.

cPanel licenses are tiered by the number of accounts you create — from a one-account Solo license up through Premier for 100 accounts — so your cost scales with the business. Two trade-offs to be honest about. First, support covers the VPS, not your customers: when a client can't send email at midnight, that ticket lands on you. Second, replicating the managed stack (LiteSpeed, CloudLinux, automated backups) means extra licenses or open-source stand-ins, which narrows the price gap somewhat.

The economics still favor DIY for small operations, because you're paying for one VPS and one license instead of a plan whose per-client margins were set by someone else. There's also a renewal detail worth knowing: RackNerd's promo VPS deals have historically renewed at the same low price you signed up at — the opposite of the hikes described above — though it's always smart to confirm on the order page before paying. 👉 [see RackNerd's VPS locations and current promo pricing](https://bit.ly/my-rn)

This route fits you if you're comfortable in a terminal, want hosting for your own projects first and clients second, and would rather keep the margin. If the phrase "patch the kernel" makes you uneasy, buy the turnkey plan and don't look back.

## Starting a cPanel reseller hosting business, step by step

The steps diverge completely depending on which track you pick, so decide that first.

### Turnkey track

1. Size the plan by expected client count, not by storage. Five clients today means Asura's entry tier; twenty-five means InMotion's R-1000N.
2. Order, then set up private nameservers and white-label branding in WHM so clients see your brand.
3. Install billing software. WHMCS comes free with InMotion and HostSEO; Asura sells it as an optional $9.99/mo add-on (Blesta runs $2.99/mo).
4. Create your packages and prices in WHM, then onboard your first clients — both Asura and InMotion include free migration if you're moving existing sites.

### The DIY track on a RackNerd VPS

1. Pick a VPS location close to your customers — latency matters when you're selling shared hosting.
2. Order a KVM VPS sized for your expected load; annual promo deals are where the savings live.
3. Attach a cPanel/WHM license as an add-on so you get full WHM access.
4. Harden the box: install an SSL certificate on the hostname, set up a firewall, and keep the OS current.
5. Create hosting packages in WHM, point your nameservers, and set up billing.
6. Own your backups from day one — on an unmanaged VPS, that responsibility is yours.

If you're ready to start the DIY track, 👉 [grab a RackNerd KVM VPS and attach your cPanel license](https://bit.ly/my-rn).

## FAQ

### How many clients can a reseller plan handle?

Depends on the tier: Asura's entry plan allows 5 cPanel accounts and its $19.99 tier allows 35; InMotion includes 25 cPanel licenses at $19.99/mo and 100 at $49.99/mo. Overselling is enabled on plans like Asura's, so disk sold can exceed disk owned — the real ceiling is CPU allocation, which scales from 2X to 15X across Asura's tiers.

### Is cPanel reseller hosting profitable?

It can be, and the math is easy to check. InMotion's $19.99/mo plan includes 25 cPanel licenses with WHMCS free; sell 25 accounts at $5/mo each and you gross $125 against about $20 of infrastructure. The hidden cost is your time — support, migrations, and churn are your job on either track, and the DIY route swaps some of that time for a lower cost base.

### Do I need WHMCS?

No, but you'll want billing automation past a handful of clients. WHMCS is included free with InMotion and HostSEO; Asura offers it optionally at $9.99/mo, with Blesta at $2.99/mo if you'd rather pay less.

### Can I run reseller hosting on a VPS instead?

Yes — install cPanel/WHM on a VPS and you get the same account-creation machinery a reseller plan provides, plus root access. The trade is that you take on all server administration. If that sounds fair, 👉 [browse RackNerd's KVM VPS plans](https://bit.ly/my-rn) and pick a location near your customers.

### What happens if it doesn't work out?

InMotion's 90-day money-back guarantee is the longest in the reseller market; HostSEO, GreenGeeks, Namecheap, ScalaHosting, and Verpex all offer 30 days. Check whether the guarantee covers the billing term you're buying before you commit to an annual payment.

## The short version before you pay anyone

Pick by your appetite for hands-on work, not by the longest feature list:

- **Fully managed, starting small:** Asura's $4.99/mo Reseller 1 plan, with no advertised renewal hikes.
- **Long exit ramp and free billing software:** InMotion from $19.99/mo, backed by a 90-day refund.
- **Comfortable managing your own server and want the lowest cost per client:** build it yourself on a RackNerd KVM VPS with a cPanel/WHM license. 👉 [check RackNerd's current VPS deals and license pricing before you decide](https://bit.ly/my-rn)

Whatever route you take, run two checks at checkout: what the plan renews at in month 13, and how many cPanel accounts you're actually buying. Those two numbers decide whether the deal is real.
