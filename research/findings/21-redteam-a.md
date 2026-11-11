# 21 Red-team A: F1 (prequal-platform compliance) and F2 (trucking new-entrant prep)
Searched 2026-11-11, about 13 searches. Mostly search-result summaries, not full pages. Labels: VERIFIED = seen in a search result; ESTIMATE; HYPOTHESIS. Note: "VERIFIED" here means a vendor or aggregator said it, not that I confirmed the underlying fact.

## Shared findings
- ISN User Agreement (isnetworld.com/user-agreement): users must be employees or independent contractors of the subscriber; the subscriber is liable for anyone using its account; ISN may cut off access if a user is affiliated with another subscriber; ISN "does not endorse or recommend any consulting firm"; insurance brokers get a separate portal. VERIFIED (excerpts only; full text unread).
- Searches found no FMCSA or platform data on new-entrant survival or audit failure that I could verify. See F2 for the one unsourced figure.

## F1: ISNetworld / Avetta / Veriforce subcontractor service

### (a) Eight strongest failure reasons
1. **Crowded, SEO-saturated market with a $1,495 one-time anchor (HIGH).** Safety Manual Today sells a RAVS manual at $1,495 one-time (includes 10 years of updates) or $95/month, and invoices only after ISN accepts it. A $750 to $2,500 fee plus recurring revenue competes with a "pay only on pass" guarantee. VERIFIED (safetymanualtoday.com, 2026). Also present: Safety Services Company, OWYN Safety, Green Flag Safety ($300/month and up), JJ Safety and others. HYPOTHESIS: dozens of firms.
2. **Credentialed incumbents versus a founder with no safety credential or industry contacts (HIGH).** Buyers are small contractors who pick from Google and referrals. HYPOTHESIS: no CSP/CHST, no trade network, no reviews, and no case studies means a slow trust build. Winning the first 30 days with zero warm leads is unlikely.
3. **Platform-access friction (HIGH).** ISN terms limit users to employees or independent contractors, make the subscriber liable, and say ISN endorses no consultants. Logging in "as" a client is a gray area, and ISN can suspend accounts it suspects of cross-subscriber use. Veriforce and Avetta terms were not seen. VERIFIED for ISN excerpts; HYPOTHESIS for the risk to the business.
4. **Customer pays for the portal anyway and the buyer is price-anchored (MEDIUM-HIGH).** ISN contractor plan is $875/year plus $125 setup (Capterra, 2026). Avetta is quote-based, with sources citing $450 to $900/year. VERIFIED (aggregators). A subcontractor already paying about $1,000/year to the platform resists a second large fee.
5. **Platforms are adding their own help and AI (MEDIUM).** Avetta says 80+ safety professionals review programs, and it offers a dedicated onboarding consultant, the Vetify managed service, and AskAva generative AI. VERIFIED (avetta.com). This competes directly with a one-person shop and will keep moving into the service layer.
6. **Liability for wrong safety programs (MEDIUM).** Safety consulting E&O is about $2,200/year (NerdWallet/Coverdash), and general consulting averages about $662/year. Rejections are a nuisance. An injury where a negligently written program is cited in litigation is the real tail risk. VERIFIED for premiums; HYPOTHESIS for claim risk. A founder with a $0 to $1,000 budget likely cannot insure properly on day one.
7. **Recurring revenue is thin and churny (MEDIUM-HIGH).** Competitors price maintenance at $95 to $300/month. HYPOTHESIS: once approved, many contractors cancel until renewal. The work is also seasonal, tied to a hiring client's deadlines.
8. **Demand is hiring-client-driven and lumpy (MEDIUM).** Networks are large (ISN about 85,000 contractors per an aggregator; Avetta 130,000+ businesses globally; ISN's older figure was 78,000+), but each contractor must be reached individually with no legitimate shared list. ESTIMATE: low single-digit conversion on cold outreach. Aggregator counts are unreliable.

### (b) Competitor prices
| Firm | Offer | Price | Source / date |
|---|---|---|---|
| Safety Manual Today | RAVS/ISN manual | $1,495 one-time or $95/mo | safetymanualtoday.com, 2026 (summary) |
| Green Flag Safety | Portal setup and maintenance | from $300/mo | green-flag-safety.squarespace.com/pricing (summary) |
| US Tech Automations (vendor blog) | ISN implementation $2,000-$5,000; Avetta $1,500-$4,000 | unverified, interested party | ustechautomations.com, 2026 |
| Safety Services Co., OWYN, JJ Safety, First Compliance, others | Avetta/ISN program packages | not published, quote-based | owynsafety.com, safetyservicescompany.com |
| ISN platform | Contractor/supplier subscription | $875/yr + $125 setup | capterra.com, 2026 |

### (c) Abandon signals in weeks 1 to 3
- After 100 or more tailored, compliant outreach messages to contractors with a verified hiring-client requirement, fewer than 2 to 3 qualified conversations and zero paid projects.
- Prospects say "I'll just buy the $1,495 manual" or ask whether you guarantee acceptance on a pay-after-pass basis.
- A written response from ISN, Avetta or Veriforce (via a prospect's account or the contractor's own inquiry) that third-party submission violates terms.
- Prospects will not give you delegated access, or insist their own employee must log in.
- Cannot obtain E&O at an affordable price.

### (d) F1 verdict inputs
Lower regulatory/telemarketing exposure than F2, but a slow B2B sale with no network. See combined verdict.

## F2: FMCSA new-entrant audit prep

### (a) Eight strongest failure reasons
1. **Marketing environment is toxic (HIGH).** FMCSA warns that vendors contact new registrants within minutes of filing, scraping public registration data, and that complaints include pressure to enroll immediately. FMCSA says it does not use telemarketers and that using a service provider "is NOT a requirement." VERIFIED (fmcsa.dot.gov fraudulent-and-misleading-marketing page). Prospecting from the public new-registrant list puts you in the same bucket as the harassers.
2. **Saturated and cheap competition (HIGH).** Trucksafe New Entrant Bundle $325; OOIDA program $30/month plus $85 setup; J.J. Keller runs a consultant-led new-entrant program (price not seen); Fiverr gigs exist; $150 to $400/month retainers are common. VERIFIED (vendor pages, 2025-2026). Price pressure caps fees below the $750+ range.
3. **Customers have little money and churn (HIGH).** Reports say most new carriers close in year one (one blog, no percentage). Roughly 100,000+ new carrier entries per year (one trade article; ESTIMATE, unverified). HYPOTHESIS: many are single-truck owner-operators, so a $150 to $400/month retainer is hard to sustain. Retainer churn follows carrier failure.
4. **The audit is free and low-bar, so willingness to pay is low (MEDIUM-HIGH).** FMCSA conducts it at no charge within 12 months; an unsourced blog claims a 15 to 20% initial fail rate (UNVERIFIED). If few fail, buyers have little urgency; if the real rate is low, the pitch is fear-based.
5. **TCPA and mini-TCPA exposure on calls and texts (HIGH).** Courts have allowed Do Not Call suits where a number is used for mixed business and personal purposes (Shelton v. Pro Source, E.D. Pa. 2025; Ohio case). Many owner-operators use one cell phone for everything. Autodialed or prerecorded calls need consent regardless. VERIFIED (law-firm blogs); damages $500 to $1,500 per call is general knowledge, not seen in these results. Individual callers can be sued personally.
6. **Reputation spillover (MEDIUM-HIGH).** BBB shows 3 stars over 11 reviews for a registration mill (Federal Carrier Compliance Registration LLC) with complaints about deceptive pricing. Trustpilot reviewers call DOT Compliance Group a "scam company" (a reviewer's claim). Truckers Report forum threads: "New O/O beware of Foley," "New DOT# = impressive spammers." Iowa's AG acted against a firm sending FMCSA-lookalike notices. VERIFIED (summaries). Truckers are primed to distrust any unsolicited vendor.
7. **Tools commoditize the product (MEDIUM).** HYPOTHESIS: driver qualification file checklists, drug/alcohol policies and templates are free or cheap (J.J. Keller, FMCSA brochure, Trucksafe blog). Not seen directly: whether LLM tools meet the standard; likely yes for templates, no for judgment on the audit.
8. **Liability and credential gaps (MEDIUM).** A drug and alcohol program involves a DER, Clearinghouse registration and a consortium/TPA; an error can cost a carrier its authority. A solo AI-assisted founder with no trucking background likely cannot sell this credibly. HYPOTHESIS.

### (b) Competitor prices
| Firm | Offer | Price | Source / date |
|---|---|---|---|
| Trucksafe | New Entrant Bundle | $325 | trucksafe.com product page, 2025 |
| OOIDA program | DOT compliance | $30/mo + $85 setup | landline.media (summary) |
| Generic providers | New-entrant packages | $150-$400/mo | search summary of vendor pages |
| J.J. Keller | New Entrant Compliance Program | not shown (consultant-led) | jjkeller.com |
| Competitor claim | 12-24 mo contracts, $500+ setup | claim by rival | otrucking.com (hearsay) |
| Foley, DOT Compliance Group, CNS, Simplex | various | not found | no price seen |

### (c) Abandon signals in weeks 1 to 3
- Under 1 to 2% reply rate on compliant (email, mail) outreach, and no paying customer after 50 to 100 qualified contacts.
- Prospects say "I already got 10 calls" or assume you are a scam; complaints or a platform/ISP block on your outreach.
- Prospects will only pay $30 to $100 or ask for "free" help.
- Any TCPA demand letter, or legal advice that texting or calling the FMCSA list is unsafe.
- Unable to complete a driver qualification file or drug/alcohol program that a trucking expert accepts.

## Combined verdict (d)
- **$1,000 in 30 days:** neither is likely. If forced to pick, F2 is more likely to produce a first sale quickly, because the buyer is a motivated new carrier with a deadline and you can reach them by direct mail or email. But expect $150 to $325 sales and many refusals. F1 has bigger tickets but a slower, referral-driven sale and a stronger "pay after pass" competitor. HYPOTHESIS; no direct conversion data found.
- **Sellable company:** F1 is more likely, but only modestly. Contractor compliance customers last longer than failing carriers, and the market (tens of thousands of contractors per platform) is more stable. F2 has high churn, a poor reputation and no durable data or relationships, so it is hard to sell for $5M.
- **Neither reaches roughly $1M EBITDA and a $5M sale.** Both are service businesses built on hourly consulting labor with commodity pricing. At 50 clients the founder is the bottleneck; at 200 clients you need staff and QA; at 1,000 clients you are a call center with E&O exposure and platform dependence. The $5M exit assumes multiples that are hard to support for a low-margin, high-churn compliance shop with no IP. ESTIMATE/HYPOTHESIS; not evidenced in these searches.

## Gaps
Could not verify: Veriforce terms of use, new-USDOT counts and one-year survival, true audit fail rate, ISN/Avetta paid consultant lists, Reddit threads, JJ Safety and other firms' prices. Treat all prices as vendor-published and possibly stale.

Sources: safetymanualtoday.com/isnetworld-cost; capterra.com/p/145737/ISNetworld/pricing; isnetworld.com/user-agreement; avetta.com/plans and /clients/solutions/platform/ai; fmcsa.dot.gov/registration/fraudulent-and-misleading-marketing-new-fmcsa-applicants; trucksafe.com/product-page/new-entrant-bundle; jjkeller.com New Entrant Compliance Program; thetruckersreport.com forum threads; BBB Federal Carrier Compliance Registration LLC; Trustpilot DOT Compliance Group; nerdwallet.com and insureon.com E&O cost pages; natlawreview.com and jdsupra.com TCPA articles (2025).
