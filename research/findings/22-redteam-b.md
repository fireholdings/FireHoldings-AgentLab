# Red-team B: F3 (CMMC L1 packs), F4 (bid/SAM packages), F5 (AR follow-up)
Date: 2026-11-11. ~20 searches; search summaries only, no page fetches. Labels: VERIFIED = source seen in search result; ESTIMATE; HYPOTHESIS.

## Cross-cutting facts
- CMMC status (VERIFIED, summaries): DoD suspended Phase 2 on 2026-07-13 (it was due 2026-11-10), launched 60-day Reform Task Force; Phase 1 self-assessments, DFARS 7012, NIST 800-171 Rev 2 remain in force. Federal News Network (Oct 2026, federalnewsnetwork.com/defense-news/2026/10/rfi-offers-path-forward-for-dod-with-cmmc) says task force recommendations could restart Phase 2 with a narrower population over ~90 days; a proposal only. No new Phase 2 date found. Sources: gtlaw.com/en/insights/2026/7/..., crowell.com, wilmerhale.com 2026-07-20, jenner.com ("compliance obligations remain, as does enforcement risk").
- Small-business contractor base is shrinking: Bloomberg Gov counted 51,632 small businesses in FY2025, -4%, 14th decline in 15 years; Deltek says -49% since FY2010 though dollars hit a record ~$195B (samsearch.co/Deltek summary, 2026). A Senate Democrat report claims >6,500 small partners lost since Jan 2025 (partisan; unverified methodology).
- Late invoices are real: QuickBooks 2026: 59% of businesses have invoices 30+ days overdue (47% prior year); Xero Q1 2026 US average 9.0 days late (secondary aggregator sites).
- Free alternatives are strong: APEX Accelerators give free SAM registration help, capability statement review, and in some states bid review (e.g., Indiana) (various .edu/.gov pages, 2024-26). Free CMMC L1 SSP/policy templates exist (securityscientist.net, Secureframe L1 kit, bristol-companies.com SSP docx, 2026).

## F3: CMMC L1 / 800-171 doc packs ($1.5-5k + annual affirmation)
### Six strongest failure reasons
1. HIGH. Urgency removed. Phase 2 suspended; one CyberSheath release notes the pause is a reason for contractors to wait (VERIFIED, summary). Level 1 is already a free self-attestation with no third-party check.
2. HIGH. Free/cheap substitutes: free L1 SSP, policy and POA&M templates, Secureframe L1 kit, Overwatch L1 package $2,995 (listed $2,495/yr) (VERIFIED, search snippets). Your $1.5-5k pack sits on top of free.
3. HIGH. FCA exposure. DOJ Civil Cyber-Fraud: MORSECORP paid $4.6M (March 2025) over an inaccurate SPRS score; knowledge standard is "knowingly overstated"; 15+ settlements since Oct 2021 (Crowell, Skadden, 2025). I found NO source on consultant liability; HYPOTHESIS: a consultant who drafts the score could face "causes to be presented" theories and professional-liability claims. A solo founder with no E&O and a flat fee cannot price this.
4. HIGH. Your own tooling constraint: if any engagement touches CUI, DFARS 7012 FedRAMP-Moderate-equivalent cloud rules apply to the service provider (VERIFIED, secureframe, summit7); a consumer $20 AI plan is unusable. L1 is FCI only, so scope discipline is possible but any client with CUI becomes Level 2.
5. MEDIUM-HIGH. Credibility gap: buyers pick former-assessor/C3PAO/RPO-credentialed firms; Special Forces/NNSA program management is adjacent, not CMMC. Sales cycle for DIB suppliers is typically driven by prime flowdown deadlines; with deadlines frozen, buying slips (ESTIMATE).
6. MEDIUM. Low-ticket plus thin pool: small DIB firms budget little (PreVeil: >3 in 5 budget under $50k for CMMC, vendor survey) and many remediation costs ($10-15k) dwarf your doc pack; annual affirmation is a one-page SPRS entry few will pay a subscription for (HYPOTHESIS).

### Competitor prices
| Competitor | Price | Source/date |
|---|---|---|
| DoD estimate for small-business L1 self-assessment + affirmation | ~$5,977/yr | DoD cost model via smithers/preveil summary, 2026 |
| Consultant-assisted L1 (vendor estimates) | $3,000-$15,000 | itsasap/summit7-type guides, 2026 (marketing) |
| Overwatch Tools L1 package | $2,995 (or $2,495/yr) | overwatchtools.com, 2026 |
| Free templates | $0 | securityscientist.net, Secureframe, Bristol, 2026 |
| Hourly CMMC consultant rates | not found | - |

### Verdict
30-day $1,000: LOW-MODERATE (ESTIMATE 15-25%). Possible only via warm referrals from existing contacts; cold outbound into a paused-deadline market is slow. Exit: POOR. Solo consultant doc packs have no recurring moat; nobody buys them at 5x. Credible path is acqui-hire or tiny asset sale only.

## F4: Bid/no-bid reviews, SAM health check, capability statements ($500-1,500)
### Six strongest failure reasons
1. HIGH. Free competition: APEX Accelerators (federally funded) do SAM registration, capability statements, sometimes bid review at no cost (VERIFIED).
2. HIGH. Scam reputation. SAM.gov is free; BBB, GSA, TINA.org, NBC News document paid "registration" firms (Federal Filing $998, GetSAMNow $299/yr); GSA: no third party should ever impersonate SAM.gov (VERIFIED). Google Ads for this category are poisoned; trust cost is high, and a solo with no references starts as a suspect.
3. HIGH. Shrinking customer base: small firms participating fell to 51,632 (-4% FY2025), spending outside 8(a) fell first time in a decade, DOGE terminations (VERIFIED, Bloomberg/Deltek summaries).
4. HIGH. AI commoditization: Sweetspot (listed from $60/mo on SourceForge), GovSignals ($39/mo on Software Advice vs $1,500/user/yr on Capterra), GovDash/Procurement Sciences custom; bid/no-bid scoring is the first thing these tools and ChatGPT do. Pricing conflicts; low-end tools undercut a $500 review.
5. MEDIUM-HIGH. Buyer behavior: small contractors lack budget; proposal consultants price mostly $2,500+ per bid up to $10k+ (vendor claims), and your product is a cheap upstream step that does not produce wins. Success fees restricted federally (summary). Customers who lose bids blame the reviewer (HYPOTHESIS).
6. MEDIUM. Subscription bid-matching competes with SAM.gov alerts (free), GovWin, HigherGov, etc. Nothing proprietary.

### Competitor prices
| Competitor | Price | Source |
|---|---|---|
| APEX Accelerator | free | state APEX sites 2024-26 |
| SAM registration helpers | $299/yr-$998 | TINA.org (undated) |
| Sweetspot | from ~$60/mo (listing) | sourceforge.net 2026 |
| GovSignals | $39/mo vs $1,500/user/yr (conflict) | softwareadvice / capterra 2026 |
| GovDash, Procurement Sciences | custom/not published | G2, samsearch 2026 |
| Proposal consultants | $2.5k+ per bid; $150-400/hr; $10k+ | ostglobalsolutions, others (marketing) |

### Verdict
30-day $1,000: MODERATE (ESTIMATE 25-35%): two to three $500 reviews from personal network is plausible. Exit: VERY POOR; compare to $1M EBITDA goal, no scale.

## F5: First-party AR follow-up ($300-1,000/mo flat)
### Six strongest failure reasons
1. HIGH (legal, unresolved). "First-party in the client's name by an outside contractor" is NOT a safe harbor. Wyoming excludes employees of a creditor collecting in the creditor's name and collection in the creditor's true name (VERIFIED, statute summary) but its "collection" definition also covers a hired third party, so a contractor is arguable. Michigan: license required to operate a collection agency (MCL 339.904); Michigan Supreme Court (Badeen, 2014) read "collection agency" broadly; I could not confirm whether commercial claims are excluded (UNRESOLVED). New York: no state license, but NYC/Buffalo/Yonkers require local licenses (summary). Texas and Florida: no usable result (UNRESOLVED; Florida's CCA is generally consumer-focused, HYPOTHESIS). Vendor guides claim ~20 states license commercial collectors, often with bonds (Boostly/AgentCollect, marketing). Needs counsel; multistate clients make this a live risk.
2. HIGH. Cheap software does 80%: Paidnice from $19-69/mo, Chaser ~$49-259/mo (GBP 150-199 tiers), QuickBooks reminders included, Upflow quote-based (VERIFIED, conflicting listings). Your $300-1,000/mo must beat software plus an owner's 1.5 hr/week.
3. HIGH. Outcome risk without contingency: you carry effort, client cash depends on debtor; flat fee with no recovery share means churn when invoices do not get paid, and when they do, client forgets why it paid you (HYPOTHESIS).
4. HIGH. Scale ceiling: phone/email chasing is labor-hours; $300-1,000/mo with ~5-10 hrs each caps solo at ~$10k/mo (ESTIMATE). Hiring gets you into outsourced-AR firms (Ramp-listed outsourcing, Stealth Agents) competing on offshore labor.
5. MEDIUM-HIGH. AI commoditization: AI agents (AgentCollect, Gaviti, Chaser) do email/voice dunning; Boostly/AgentCollect advertise state compliance (marketing).
6. MEDIUM. Access and liability: you need client QuickBooks/bank data, the client's reputation is in your hands, and a rude message creates tortious interference/defamation claims; no consumer AI plan for client data.

### Competitor prices
| Competitor | Price | Source |
|---|---|---|
| Paidnice | $19-$69/mo (listings conflict; Essentials $69, 150 invoices) | g2.com, hackceleration 2026 |
| Chaser | $49/mo (2024, USD) to GBP 150-199/mo; Capterra $259 | getapp, fitgap 2026 |
| Upflow | not public | g2 comparison |
| Invoiced | not found | - |
| QuickBooks reminders | bundled with subscription | not priced here |
| Outsourced AR | flat $10-15 per account (one agency); no monthly dollar figure found | insidearm.com |

### Verdict
30-day $1,000: MODERATE-HIGH (ESTIMATE 35-45%) with 2-4 trades/agency friends at $300-500/mo; this is the quickest to start but the legal question must be answered first. Exit: POOR as a solo labor business; services-with-software buyers pay for recurring B2B software, not a labor roster.

## Exit evidence (all three)
- GovCon multiples: sub-$10M unclassified 6-9x EBITDA; $10-50M 8-12x; CohnReznick medians ~9.7-10.0x (2022-23); compression from 15.4x (Q4 2023) to 11.5x (Q4 2025) (broker pages, marketing). Set-aside-heavy firms discounted (HigherGov). These apply to contracting firms with contracts and staff, not to a compliance-doc shop. I found NO sale of a comparable small doc-pack or AR-chasing solo business. A $1M EBITDA at 5x = $5M requires ~$3-5M revenue at 20-30% margin (ESTIMATE): that means 150-250 customers at $20k or 400+ at $8k. None of F3/F4/F5 pricing gets there without a team.

## Service-to-product review
- No base rate found. A search turned up only anecdotes; the "90% fail" comment on Indie Hackers is unsupported (HYPOTHESIS, not data). Do not cite a number.
- Successes: Castos (productized podcast service became ~80% SaaS income); Brian Casel/Audienceops (started productized, couldn't make software math work), Tetra Insights (frontlines.io, 2026).
- Failures: discury.io summaries of agency-to-SaaS pivots: half-built product, neglected clients, founder burnout.
- What distinguishes winners (synthesis, HYPOTHESIS): the service is run on one narrow repeatable workflow with high volume; founder has software capability; the customer already pays for software; customer data flows through a system you own. F3-F5 fail the last two: your edge is judgment, your customers are not recurring software buyers, and regulated data limits what you can build with consumer AI tools. Software-enabled-service (e.g., "$14k MRR" Indie Hackers post) is the survivable form, but that is a lifestyle business, not a $5M exit.

## Overall
None clears both goals. For the 30-day goal, F5 or F4 via personal network is the fastest, F3 the most legally dangerous, F5 requires counsel on licensing first. For the $5M exit goal, none works as designed.
