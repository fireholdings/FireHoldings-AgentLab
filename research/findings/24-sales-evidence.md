# 24 - Sales evidence for a 30-day, $1,000 test (research date 2026-11-11)

Method: about 22 web searches. Most results were search-engine summaries; I could not fetch pages (WebFetch was blocked for safetyservicescompany.com). Nearly all sources are vendor blogs. Labels: VERIFIED = a source appeared in results; ESTIMATE = derived or vendor-asserted with unclear method; HYPOTHESIS = my inference. Nothing below was tested.

## (a) Benchmarks

| Metric | Figure | Source (date) | Sample / definition | Bias |
|---|---|---|---|---|
| Cold email avg reply rate | 3.43% | Instantly 2026 benchmark, cited via mailshake.com/blog/cold-email-response-rate/ and cleverly.co/blog/b2b-outbound-benchmarks (2026) | Billions of sends, mostly SaaS/agency senders | Sender-tool vendor; counts auto-replies; not blue-collar. VERIFIED (secondhand) |
| Cold email reply, lower estimates | 1.4% to 2.1% | getboomerang.ai (2026); visionary-marketing.co.uk (2026); Sales.co via apollo.io (2M+ emails, 2.09%) | Varies | Vendor blogs |
| Meetings booked per email | 0.34% median; 0.3-0.6% positive replies; 0.7% per send (AutoTouch, Instantly-derived); "1-3% per 100 for well-targeted" (Cleverly) | Same pages as above | Different denominators | Agencies selling services; the 1-3% figure is the least conservative. ESTIMATE |
| Cold call connect rate | 5.4% avg, 13.3% top quartile (Gong, about 300M calls); 4.6-5.5% (Orum, 1.5M calls); 9.9% (Belkins, 175k dials, 2025) | Aggregated at prospeo.io/s/cold-calling-conversion-rate, saleshive.com (2025-26) | Mostly SDR teams on purchased lists | Dialer/data vendors; secondhand. VERIFIED (secondhand) |
| Cold call to booked meeting | 2.3% (2025), 2.7% (2026 update), 4.82% (2024) | Cognism State of Outbound 2026 (cognism.com/reports/state-of-outbound-2026) | Cognism's dataset | Data vendor that sells phone numbers |
| LinkedIn connection acceptance | 28.5%; 3.0% reply to note; 10.4% reply after acceptance; connection-note replies fell from 3.5% (May 2025) to 2.2% (Apr 2026) | Expandi, 13.2M requests (expandi.io/blog/linkedin-outreach-benchmarks, 2026) | Automation-tool users | Automation vendor. Belkins/Expandi 2025: 26.4% acceptance |
| New-domain warm-up | At least 2 weeks (Instantly); 2-4 weeks (Warmy); 4-6 weeks full volume (Instantly 2026 benchmark); about 90 days (Woodpecker) | instantly.ai/blog/warm-up-email-domain; woodpecker.co/help-center | Vendor guidance, not measured | Warm-up tool vendors profit from long warm-up. I found no Smartlead figure |

None of these cover SMB blue-collar audiences specifically. I found no such segment benchmark, so any reply rate for subcontractors or truckers is HYPOTHESIS. Plan on about 1-3% total reply and well under 1% meetings from cold email.

Deliverability: Google and Yahoo bulk-sender rules (from 2024) and Microsoft consumer mailboxes (from May 5, 2025) require SPF/DKIM/DMARC alignment at about 5,000+ messages a day; Google tightened enforcement in November 2025 (valimail.com, uriports.com, proofpoint.com; vendor summaries, official pages not seen). A solo founder sending under 50 a day is below the bulk threshold, but authentication is still sensible. HYPOTHESIS: a separate lookalike domain with 5-10 sends a day starts hurting a 30-day clock; sending 2-4 weeks late means the first emails hit around day 14-28. Cold calls, LinkedIn and direct forum conversations do not need warm-up.

## (b) Ranked prospecting channels

### Offer 1: ISNetworld / Avetta / Veriforce approval

Overall: demand is client-driven, not platform-driven. I found no 2026 mandate announcement with a contractor deadline. The only dated example was VGP Holdings (Valvoline): contractors had to join ISNetworld by April 30, 2025 (safetyservicescompany.com/blog/isnetworld-and-valvoline-2025; expired).

1. New hiring-client announcements. Examples (titles only, pages unread): Vitro Flat Glass joins ISN (safetyservicescompany.com/blog/vitro-flat-glass-joins-isn, 2026-03-13); Potentia (/blog/potentia-isn, 2026-04-15); DESRI (/blog/desri-joins-isnetworld-what-contractors-need-to-know, 2026-06-25); IPX Power selected ISN, September 2026 (secondhand aggregator). Each new client creates a batch of contractors who must comply. HYPOTHESIS: most promising, because the contractors are time-pressured. Weak points: finding those contractors needs LinkedIn/search work, and the client's supplier page is the only list.
2. Competitor content and Google queries. Competitors publish "what contractors need to know" posts per client, suggesting contractors search these phrases. I could not see ad data, so ad activity is unverified. Use it as a keyword source only.
3. Reddit/forums where contractors ask for help. I found no specific thread or Facebook group in searches (the Capterra complaint that requirements are "over the top for a small company" shows the pain, capterra.com/p/145737/ISNetworld/reviews). Search Reddit directly (r/Construction, r/oilandgasworkers, r/SafetyProfessionals); unverified.
4. Upwork/Fiverr. My search returned no ISNetworld gig counts, so demand there is NOT verified.
5. Direct LinkedIn outreach to owners/safety managers of small subcontractors in the client lists above.
6. Cold calls to small subcontractors (see legal limits).
7. Insurance agents and safety-supply distributors serving subcontractors (no referral-fee evidence found for this niche).
8. Existing consultants as overflow partners. HYPOTHESIS only: large consultancies (Safety Services Company, Lancaster Safety, Safety Resources, D7, Safety By Design) sell the same service, so they may subcontract writing work.

Price anchors: ISNetworld contractor subscription about $875/yr including $125 setup (Capterra), or about $680 for 1-4 employees, $850 for 5-9, $1,410 for 10-19 (howmuchisit.org; calculator table). Avetta unpublished; third parties say $450-900/yr or about $249 setup plus $799 (erpresearch.com; billyforinsurance.com, a competitor). Consultants: OWYN self-service wizard $497; Lancaster Safety small-team tier $7,950/yr on a five-year contract (vendor pages, 2024-26). Typical program workload is 10-30 programs and about 2 weeks for ISN review (consultant blogs, VERIFIED secondhand). So a $500-$1,500 fixed fee sits between the $497 DIY tool and $7,950 full-service; that positioning is HYPOTHESIS.

### Offer 2: FMCSA new-entrant audit readiness

Overall: new carriers are already swamped with solicitations, which makes cold contact hard but proves they buy.

1. Phone/text to newly registered USDOT carriers. TruckersReport thread "New Authority. Getting solicited with 20+ calls a day" (thetruckersreport.com/truckingindustryforum/posts/13347856) and "New DOT# = Impressive spammers" (threads/new-dot-impressive-spammers.249589). Compliance firms watch FMCSA filings and call right away. Saturated, and some callers impersonate FMCSA, so you will be judged against scammers.
2. TruckersReport forum itself (answering questions under your name, no pitch). Active new-authority threads exist, e.g. "Getting your USDOT and/or MC Authority."
3. r/Truckers, r/FreightBrokers, r/CDL2Authority (redlib mirror listed). I did not view contents; vendors and MC-number sellers also use Facebook and Reddit (Overdrive, FreightWaves).
4. Authority-setup/dispatch services (Simplex Group, numeo, otrucking guides) as partners. They sell packages around $350-$650 for setup (vendor pages, VERIFIED secondhand).
5. Factoring companies. Programs pay referrers: Summar 10% of fees for the life of the account, Outgo/DAT flat fee or 10%, eCapital commission, TAFS lifetime commissions and lists compliance services as a partner type (their partner pages). These pay for sending carriers to them, not to you; use them as reciprocal partners. VERIFIED on pages, terms not read.
6. Insurance agents. Cover Whale/eCapital pays agents about $500-$1,000 per enrolled client for factoring (help.coverwhale.com). Shows agents accept referral income; a rate for a compliance referral is not known.
7. Sky Transport Solutions pays partners (dealers, repair shops) when referred customers buy permit/filing/DOT services (skytransportsolutions.com/affiliate-program.html): an actual compliance-service referral model, rate unseen.
8. LinkedIn/Facebook owner-operator groups. Not verified; no groups were found in searches.

Price anchors: audit prep estimates $0-$1,500 one-time (oxmaint.com calculator, no method); a $1,297 audit-prep product on Payhip; J.J. Keller sells a New Entrant Compliance Program (price not seen). The federal fee is $300 per authority; FMCSA's audit itself is free (third-party source; FMCSA brochure at fmcsa.dot.gov/sites/fmcsa.dot.gov/files/2023-06/FMCSA%20New%20Entrant%20Brochure.pdf lists free prep materials). Wedge risk: FMCSA gives away its own prep tools, which caps willingness to pay. FreightWaves reports about 60% of new entrants lacked a formal review early on (unverified detail).

## (c) Legal do/don't (general information, not legal advice; confirm with counsel)

- CAN-SPAM (applies to B2B email): do use accurate From/subject, include a physical postal address, include a working opt-out and honor it within 10 business days, and keep records. Don't buy lists of unknown origin or use deceptive headers. (Statutory basics from my background knowledge; not re-verified in this session.)
- Calls: federal TCPA restrictions on autodialed/prerecorded calls and texts to cell phones apply even to business numbers (callshaper.com 2025). Manual one-to-one calls are safer than texts or dialers. Don't text cold prospects. Do keep an internal do-not-call list.
- DNC Registry: the federal registry covers consumers, and B2B calls are largely outside it, but state rules differ.
- State mini-TCPAs: sources list Florida, Oklahoma, Washington and Maryland as having no clean B2B exemption (callshaper.com; compliancepoint.com; one source says Oklahoma exempts some B2B, so sources conflict). Florida/Oklahoma cap three calls per 24 hours on the same subject and may require registration. Texas exempts B2B unless the business opted out. Do skip FL/OK/WA/MD numbers in a 30-day test, or get counsel's view. A vendor post (Oct 2026) mentions an FCC opt-out rule effective Nov 25, 2026; unconfirmed.
- Government data: FMCSA census data is public and offered free (data.gov catalog), and trade press says calls using it are legal. I found no solicitation restriction, but I did not see the license terms; check the DOT data license. Never claim FMCSA affiliation or imply an official government notice (impersonators are the main complaint on forums). Don't promise approval or audit outcomes.
- Platforms: Reddit/Facebook rules ban self-promotion in many groups; read each group's rules; do not DM-spam.

## (d) Getting paid

- Stripe: first payout comes about 7 days after the first successful payment (support.stripe.com, VERIFIED); third parties say 7-14 days. Invoicing fee 0.4% (Starter) or 0.5% (Plus) per paid invoice, plus processing: card 2.9% + 30c; ACH Direct Debit 0.8% capped at $5 (support.stripe.com/questions/stripe-invoicing-pricing; dodopayments.com; fees vary, confirm on stripe.com). On $1,000: about $5 ACH vs about $29.30 card, before the invoice fee. New accounts may face ACH limits (about $6,000 per a secondary source) and reserves.
- Square, PayPal: not researched. Do not assume timing; HYPOTHESIS that holds on new accounts are common.
- Tactic: open the Stripe account and run one small test payment in week 1 so the 7-day clock is not waiting on the first customer. HYPOTHESIS.
- Deposits: I found no source on 50-100% upfront norms; from background practice, fixed-fee online services commonly take 50% upfront (ESTIMATE). Ask for 100% on sub-$500 jobs to limit chargeback and collection risk.
- Engagement letter: one page stating scope, deliverables, client-supplied inputs, no guarantee of approval, refund terms. Card disputes are the main risk with a stranger paying by card; ACH reduces fee and dispute exposure but returns can still occur. Not researched in detail.

## (e) Marketplaces

- Upwork: Connects at $0.15 each, 6-16 per proposal; freelancer fee 0-15% per contract; Freelancer Plus $19.99/month (jobbers.io, golance.com, upwork.com, 2026). No source gives time to first job. No ISNetworld gig counts were found, so demand is UNVERIFIED.
- Fiverr: about 20% seller fee (websiteplanet.com; sources inconsistent). Fiverr has FMCSA setup gigs (e.g. fiverr.com/josephjerr/set-up-your-usdot-mc-number-and-fmcsa-trucking-authority); prices not seen. This indicates competing low-price supply for trucking setup.
- Thumbtack: not researched.

## What cannot be known without running the test

- Real reply and meeting rates for owners of small subcontractors or new carriers; all benchmarks above come from SaaS-heavy senders.
- Whether small subcontractors pay $500-$1,500 for program writing or just buy a DIY wizard at $497 or wait for the client to extend the deadline.
- Whether any 2026 hiring client mandate has a near deadline that produces urgent buyers; I found none with a live date.
- Whether a veteran/MBA credibility angle matters to either buyer type.
- Whether new carriers, already getting 20+ calls a day, will respond to anyone, and whether free FMCSA material caps pricing.
- How long Stripe holds first payouts or reserves for this founder's account.
- Whether Upwork/Fiverr have any ISNetworld or audit-prep demand at all.
- Exact legal answers for specific states and the FMCSA data license.
