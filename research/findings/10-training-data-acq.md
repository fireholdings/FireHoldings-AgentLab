# Research 10: Training/Credentials (A), Data Products (B), Acquisition Support (C), Buy-vs-Build

Research date: 2026-11-11. About 10 searches and 1 fetch (one fetch failed: joinaccredited.com was not reachable). Labels: VERIFIED = seen in search result text; ESTIMATE = my inference from sources; HYPOTHESIS = untested. Most prices are vendor marketing pages. Search results gave no publication dates for most pages, so dates are given only where the URL carries one. Treat all prices as asking prices.

## 1. Opportunity table (14 rows)

Columns: Customer / decision-maker | Urgent problem | Minimum paid offer before any tech | Observed prices (source) | Startup cost | Time to first sale | Competitor gap | AI leverage | Legal barrier | Likely acquirer

**A. Training and credentials**

| # | Customer / buyer | Problem | Zero-tech offer | Observed prices | Start cost | First sale | Gap | AI | Legal | Acquirer |
|---|---|---|---|---|---|---|---|---|---|---|
| A1 | Trades/construction firms, 20-200 staff; owner or ops/safety manager | Expired tickets and certs; audit and site-access failures | "Cert audit and expiry tracker": spreadsheet plus monthly renewal chasing | Software: CertTracker $99/mo up to 75 staff, $149/mo up to 200 (capterra.com/p/10044202/CertTracker); Entuitive CAD 7.5-12.5/employee/mo (capterra.co.uk/software/1097473); GoContractor SMB construction est. $8k-25k/yr, third-party estimate, not vendor-published (saasrat.com/products/gocontractor). ESTIMATE: a service at $300-800/mo is credible. | ~$0-100 | 2-4 wks (HYPOTHESIS) | Software leaves the chasing to the customer; service does it | High: reminders, document intake | None for tracking | Safety/compliance SaaS, staffing software, insurance brokers |
| A2 | Security guard firms; owner or compliance director | State guard-card and training rules; license lapses | Guard-license and training records administration | No published guard-specific price found | ~$0 | 3-6 wks (HYPOTHESIS) | Niche; fragmented incumbents; my background fits | High | Rules vary by state; training may need approval | Guard-industry software, roll-ups |
| A3 | Healthcare staffing firms; credentialing or compliance manager | Placement blocked by lapsed licenses, immunizations, BLS | Outsourced credential file checks | No price found (gap) | ~$0 | 4-8 wks (HYPOTHESIS) | Existing vendors are enterprise-sized | High | HIPAA exposure; needs BAA | Staffing VMS vendors |
| A4 | CA employers needing a workplace violence prevention plan (SB 553); HR or owner | Mandate: plan, annual training, logs | Plan customization plus live training for a flat fee | Consultant $150-300/hr, $6k-15k/yr (Protekon blog, vendor self-reported, protekon.vercel.app); CalChamber bundle $749.99 (commerce.calchamber.com/workplace-violence-prevention-bundle); Cal/OSHA gives a free model plan | ~$0 | 2-5 wks (HYPOTHESIS) | Template products leave site-specific hazard work undone; military threat-assessment credibility fits | Medium-high: drafting | None to teach; no license needed | HR/safety compliance firms |
| A5 | Manufacturers, 50-300 staff; EHS or plant manager | Tribal-knowledge SOPs; slow onboarding; incidents | Convert 3 SOPs into micro-training with quizzes, fixed fee | LMS benchmarks $5-17/employee/mo (coggno.com/blog/compliance-training-pricing-2026); small firms $15-30/user/yr (same source family). Custom SOP conversion price: NOT FOUND | ~$0 | 3-6 wks (HYPOTHESIS) | Generic libraries ignore the company's own SOPs | Very high | None | Training/EHS firms |
| A6 | Trades leadership (foreman to supervisor); owner | Turnover and safety from weak first-line supervision | Fixed-price 2-day foreman workshop | No published price found (gap) | ~$0 | 3-6 wks (HYPOTHESIS) | Instructor background fits; hard to scale | Medium | None | Low acquirer interest; likely a services business only |
| A7 | Trucking carriers, small; owner or safety manager | DOT driver-qualification files and training | Driver-qualification file audit | Not found | ~$0 | 2-4 wks (HYPOTHESIS) | Many small compliance shops exist (no data seen) | High | Not a licensed activity (HYPOTHESIS) | Trucking compliance firms |

**B. Data products**

| # | Customer / buyer | Problem | Zero-tech offer | Observed prices | Start cost | First sale | Gap | AI | Legal | Acquirer |
|---|---|---|---|---|---|---|---|---|---|---|
| B1 | Insurers, factoring, ELD, fuel-card sellers; sales head | Need new carriers early | Weekly new-authority list for a niche | FMCSA feeds $49/mo, a competitor $129/mo; scraper actors $2.50-5/1,000 leads (apify.com/foxlabs/fmcsa-carrier-leads) | $0 | 1-3 wks (ESTIMATE) | Commodity; price race to the bottom; data is free | High | CAN-SPAM/TCPA apply to buyer outreach | Lead-gen firms (low multiples) |
| B2 | Safety consultants, PPE and insurance sellers | Find employers just inspected or cited | Weekly OSHA inspection and citation digest by state | SafetyLeadz $297 / $597 / $1,497 per month (kjpde-storefront-safety.pages.dev). Citations post about 30 days after the employer receives them (apify.com/tagadanar/osha-inspection-leads) | $0 | 2-4 wks (ESTIMATE) | A seller exists; geographic or vertical slices may be open | High | Public data; check terms on resale | Safety consultancies, data firms |
| B3 | Construction suppliers, subs, insurers | Permits, bids, new licenses | Local permit and bid digest | Public-source price: NOT FOUND | $0 | Unknown | Unverified | High | Scraping terms vary by county | Regional trade media |
| B4 | Lenders and equipment financiers | UCC filings signal borrowing | UCC filing alert list | Not found | $0 | Unknown | Unverified | High | State site terms | Lender-data firms |

**C. Acquisition support**

| # | Customer / buyer | Problem | Zero-tech offer | Observed prices | Start cost | First sale | Gap | AI | Legal | Acquirer |
|---|---|---|---|---|---|---|---|---|---|---|
| C1 | Searchers and small PE; the searcher | Proprietary deal flow | Pilot off-market outreach (list plus letters) for one niche | Retainer $5k-25k/mo (praxisrock.com/insights/deal-origination-services-pe); hybrid $3k-8k/mo plus 0.5-2% success fee; $6k-10k/mo plus $15k-25k per LOI (same search; vendor claims). Searchers report mixed results with paid list-building (searchfunder.com) | $0-300 | 4-10 wks (HYPOTHESIS) | Buyers distrust volume without quality; a credible founder narrows this | Very high | Success fees on a deal may require broker or securities registration (see section 3) | Boutique M&A advisers |
| C2 | SBA buyers and individual searchers | Verify earnings before closing | "QoE-lite" financial review of a target | Full QoE $5k-50k, typically $10k-35k; QoE Lite from $6,490 (webacquisition.com/quality-of-earnings-qoe-report-cost) | $0-500 | 4-8 wks | Accountants own this; no CPA credential here, so scope risk | Medium | Unlicensed accounting opinion and liability risk | CPA firms |
| C3 | Business brokers | Need buyer leads and listings | Buyer-list building for a broker | Not found | $0 | Unknown | Unverified | High | Fee tied to deals is the licensing trigger | Broker networks |
| C4 | Newly acquired SMB owners | First 100 days: SOPs, training, systems | Fixed-price integration playbook | Not found | $0 | 4-10 wks | Fits the founder's training-system strength | High | None | Operating partners |

## 2. Top 3 (ranking)

1. **A1/A5 combined: managed credential tracking plus SOP-to-training for one regulated vertical.** Best fit for the 30-day $1,000 goal and for a 3-5 year sale.
   - Why: recurring revenue, a pain buyers already pay for, and a service-first offer before any software.
   - VERIFIED: tracking software lists at $99-149/mo for up to 200 staff (CertTracker) and $7.5-12.5 per employee per month (Entuitive). So a service must sit above that; $300-800/mo is plausible (ESTIMATE).
   - Gap: software leaves data entry and chasing to the customer. A service that includes the chasing is a hypothesis, untested.
   - $1,000 needs about 2 customers at $500/mo, or 3-5 one-time audits at $300 (ESTIMATE).
   - Exit: recurring-revenue compliance services are commonly valued above one-off consulting (ESTIMATE; no multiples seen). $5M+ needs several million in recurring revenue or a software layer, so treat the exit goal as unproven.

2. **B2: OSHA citation and inspection digests for safety sellers.** Fastest to test.
   - VERIFIED: SafetyLeadz sells at $297 / $597 / $1,497 per month. Data is free from OSHA. Scraper actors sell records at $2-50 per 1,000, so raw data is a commodity.
   - The gap is curation, local focus and a recommended outreach angle. Revenue evidence for indie data products: NOT FOUND.
   - $1,000 needs about 4 subscribers at $297 (ESTIMATE). Acquirer interest in a tiny data feed is probably low unless it becomes a larger subscriber base.

3. **A4: workplace violence prevention plan and training (CA SB 553) packages.** A legally forced, annually recurring need.
   - VERIFIED: consultants $150-300/hr, $6k-15k/yr (vendor-reported); CalChamber bundle $749.99; free Cal/OSHA model plan competes at the low end.
   - Gap: price between $750 template and $6k+ consultant is open (ESTIMATE). The founder's threat-assessment background is differentiating (HYPOTHESIS).
   - Risk: legal liability if a plan is wrong; do not promise legal compliance. Limited to California-style mandates; I did not verify other states' laws.

C1 (deal sourcing) pays the most per client ($3k-25k/mo advertised) but sources disagree, searchers report poor experiences with paid list-building, and the licensing question is open. I rank it fourth. The hardest constraint for a 30-day goal is credibility with searchers, not technology.

## 3. Acquisition-support legal notes

- VERIFIED (jonesday.com/en/insights/2023/01/new-law-exempts-ma-brokers-from-sec-registration; willkie.com 2023): federal M&A broker exemption effective March 29, 2023, for targets under $25M EBITDA and/or under $250M revenue. It does not preempt state law. About 20 states have adopted the NASAA model rule (same search). I could not confirm Michigan or Wyoming status, or how either treats finder fees or business-opportunity brokering; consult each state's securities regulator or a securities lawyer before taking any success fee. The IBBA article "The State-Line Trap" (ibba.org) argues the federal exemption is not the finish line.
- Practical consequence (ESTIMATE): fixed-fee list building and flat retainers avoid transaction-based pay, which is the main licensing trigger. That is lower risk but not risk-free. Flat fees only until legal advice is obtained.

## 4. Buy vs. build

- VERIFIED (secondary sources, not SBA's text; I could not fetch SBA or the one law-firm page I tried): SOP 50 10 8 sets a 10% minimum equity injection for changes of ownership and startups. Seller notes count toward injection only on full standby (no principal or interest) for the loan's life and cap at 50% of the injection, i.e. about 5% of project cost. SOP 50 10 8.1 reportedly takes effect October 1, 2026 and adds limited passive-investor equity into the same 50% bucket; articles say it prices on historical earnings, not projections (sources: pilieromazza.com/five-sba-7a-changes-that-could-reshape-business-acquisitions; angelinvestorsnetwork.com/capital-raising/sba-7a-acquisition-financing-rules-2026; beancount.io/blog/2026/09/23/sba-sop-50-10-8-1-change-of-ownership-equity-dscr-qoe-guide; searchfunder.com/post/new-sop-changes-sop-50-10-81). The headline in one source says zero-down deals no longer exist.
- Arithmetic (ESTIMATE): on a $500k business, 10% is $50k, of which seller standby could cover up to $25k; the founder still needs about $25k cash from savings, gifts or a gift-approved investor. With $0-$1,000 that is not available, and the lender will also look at closing costs, working capital, personal guarantee, credit, and industry experience.
- Verdict: BUILD first. Buying is not feasible on $1,000 under the rules as reported. Use a service business (A1/A5) to generate cash and a track record, and revisit an SBA acquisition after the equity requirement can be met. Do not rely on an unverified SOP detail; confirm with an SBA lender. Exception: a true seller-financed deal with 100% seller note outside SBA is possible in theory, but I found no evidence on how common that is, so it is a HYPOTHESIS.

## 5. Evidence gaps

No published prices found for: custom SOP-to-training conversion, trades leadership training, guard or healthcare-staffing credential administration, permit or UCC data products, buy-side deal sourcing for under-$5M deals. No verified revenue figures for any indie data product. Conversion rates and time-to-first-sale are hypotheses and should be tested with low-cost outreach, which I did not perform.
