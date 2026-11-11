# 03 - AI Capabilities, Prices, Limits (as of 2026-11-11)

Labels: VERIFIED = seen on an official page this session; ESTIMATE = from secondary/aggregator sources; HYPOTHESIS = my inference.
Access caveat: openai.com, privacy.claude.com and most vendor pages other than claude.com and platform.claude.com were not reachable (network allowlist). OpenAI, Google, Microsoft, n8n/Make/Zapier figures are therefore secondary-source ESTIMATES. Anthropic HIPAA, training and consumer-terms specifics also rest on secondary coverage. Re-check these before relying on them.

## 1. Capability table

| Capability | On $20 Pro? | Needs API/infra? | Price | Key limitation | Source (date) |
|---|---|---|---|---|---|
| Chat, Projects, artifacts, file creation/code execution, Skills, connectors | Yes (Free has most, Projects capped at 5) | No | Pro $20/mo, or $17/mo billed annually ($200 upfront) - VERIFIED | One shared usage pool with 5-hour and weekly caps; exact numbers not published ("more than Free") | claude.com/pricing (2026-11-11) |
| Claude Code (terminal/IDE agent) | Yes | No, unless you build on the Agent SDK | In Pro | Draws from the same Pro cap; heavy agent runs exhaust it fast (ESTIMATE) | claude.com/pricing |
| Research (multi-source reports) | Yes | No | In Pro | Not Free. Citations must be spot-checked | claude.com/pricing |
| Claude in Chrome (browser agent) | Yes | No | In Pro | Agents are slow and error-prone on logins, CAPTCHAs and odd forms (HYPOTHESIS); needs human supervision | claude.com/pricing |
| Scheduled tasks | Yes | No | In Pro | Consumes the same cap | claude.com/pricing |
| Cowork (desktop agent) | Pricing page lists it only under Team. A June 2026 support article and news coverage say all paid plans have it, with a 5-hour-limit doubling promo that ran through 5 Aug 2026 and has ended (ESTIMATE; confirm in the desktop app) | No | Unclear on Pro | Weekly caps unchanged by the promo; pool shared with chat and Code | support.claude.com/en/articles/15400594 (via search, 2026) |
| Max / Ultra | Upgrade | No | Max $100/mo (5x Pro, incl. $100 API credits); Ultra $200/mo (10x, incl. $200 credits) - VERIFIED | Credits are for API use | claude.com/pricing |
| Team | Not Pro | No | Standard $20/seat/mo annual ($25 monthly); Premium $100/$125; 2-150 seats; up to $500/mo pooled API credits - VERIFIED | Minimum 2 seats. Gives commercial-terms data protection and admin | claude.com/pricing |
| Enterprise | No | No | $20/seat/mo annual, 20-seat minimum, plus usage at API rates; HIPAA-ready option - VERIFIED | Out of range for a solo founder | claude.com/pricing |
| Programmatic automation (batch document pipelines, webhooks, voice) | No | Yes: API / Agent SDK, billed per token | See API prices below | Needs code or no-code glue; billed separately from Pro | platform.claude.com/docs/en/about-claude/pricing (2026-11-11) |

### API prices per million tokens (input / output) - VERIFIED, platform.claude.com pricing page
- Haiku 5.5: two tiers shown, $0.10/$0.50 and $0.50/$2.50 (long-prompt tier above 100k tokens costs more; the page's tier labels were truncated in my fetch).
- Sonnet 5.5: $2 / $10. Sonnet 5: $2 / $10. Sonnet 4.6: $3 / $15.
- Opus 5.5: $4 / $20. Opus 5 and 4.5-4.8: $5 / $25.
- Fable 5.2: $8 / $40. Fable 5 and 5.1: $10 / $50. Mythos 5.x (limited availability): same as Fable.
- Batch API: 50% off input and output. Cache hits cost about 5-10% of base input.
- Web search: $10 per 1,000 searches plus tokens. Code execution is free when combined with web search or fetch.
- HYPOTHESIS: a 50-page document (~40k tokens) read and summarized on Sonnet 5.5 costs roughly $0.10-0.15. Doing that 100 times a month is about $10-15. API cost is not the constraint; supervision time is.

## 2. Commercial use, retention and regulated data

- Outputs: secondary sources say Anthropic's terms assign output rights to the customer ("if any"; copyright in AI outputs is not guaranteed). ESTIMATE. I could not confirm that the consumer terms permit commercial client work on Pro. Read anthropic.com/legal/consumer-terms yourself before launch. The Commercial Terms (Team, Enterprise, API) clearly cover business use and state no training on customer content (ESTIMATE from secondary coverage; page effective 2025-06-17).
- Consumer plans (Free/Pro/Max): training is a user choice following the Oct 2025 policy change (anthropic.com/news/updates-to-our-consumer-terms). Retention is 30 days if you opt out of training and up to 5 years if you opt in. Sources disagree on the default, so check Settings, Privacy and turn training off. ESTIMATE.
- Team, Enterprise, API: not used for training by default. ESTIMATE.
- HIPAA/BAA: the BAA covers the first-party API (with conditions on covered models and retention) and HIPAA-ready Enterprise. It does not cover Free or Pro. Claude Code is covered only in limited cases, and Cowork reportedly is not. ESTIMATE; verify with Anthropic sales.
- FedRAMP/CUI/ITAR: Anthropic's public sector FAQ says Claude for Government is FedRAMP High and authorized for CUI. Claude models via Bedrock in AWS GovCloud are approved for FedRAMP High and DoD IL4/5. ITAR data may only go through Bedrock (IL5); Claude for Government and Vertex are not IL5. Vertex with Assured Workloads is also FedRAMP High. Anthropic notes that authorization attaches to the hosting cloud service, not the model. Source: support.claude.com/en/articles/13756069 and anthropic.com/news/claude-in-amazon-bedrock-fedramp-high (via search; VERIFIED on the headline points, but model availability dates conflict across sources).

## 3. Data-handling guidance by client data type

| Data type | Allowed on $20 Pro? | Guidance |
|---|---|---|
| Public data (filings, regulations, websites) | Yes | No restrictions. Still verify outputs. |
| Business confidential (contracts, financials, policies) | Conditional | Add a client NDA/AI-use clause and disclose AI use. Turn training off. Prefer Team ($25/seat monthly, 2 seats) or API for client files, since commercial terms exclude training by default. Redact where possible. |
| PII (employee or customer records) | Avoid on Pro | Use Team or API. Minimize and pseudonymize. Check state privacy and breach-notification obligations and sign a DPA with the client. |
| PHI | No | Only under a signed BAA: API (covered models) or HIPAA-ready Enterprise. Not Pro, not Team without a BAA. Practically: decline PHI work or de-identify first. |
| CUI / ITAR | No | Out of scope for a $1k business. Requires FedRAMP High/GovCloud environments, US-person controls and often CMMC. Decline. |

## 4. Competitors (secondary sources; ESTIMATE unless noted)

- ChatGPT Plus $20/mo. ChatGPT Business $25/user monthly or $20 annual, 2-seat minimum, Premium seat $125/$100 (annual price cut April 2026; sources: eesel.ai, appwrite.io, help.openai.com overview). Agent mode exists on paid plans, but I could not verify its limits.
- Google AI Pro about $19.99/mo, bundled with Workspace apps and Gemini. Not verified on a Google page.
- Microsoft 365 Copilot Business about $21/user/mo as an add-on, requiring a qualifying M365 license. Sources conflict.
- n8n: self-hosted community edition is free; Cloud Starter about $20-24/mo. Make: free 1,000 credits, paid from about $9/mo annual. Zapier: free 100 tasks, paid from about $20-30/mo. Sources disagree on volumes; check vendor pages.
- Voice agent platforms: I did not verify prices. Not researched within budget.
- HYPOTHESIS: Claude, ChatGPT and Gemini are interchangeable at roughly $20. Choose on data terms and tool fit. Claude's Team tier at the same $20 seat price matches ChatGPT Business.

## 5. Realistic limits

- Hallucination: models invent citations, regulation numbers and figures. I found no 2026 sanctions data in this research (searched, nothing returned). HYPOTHESIS: every client-facing citation, deadline and dollar figure needs a human check against the source. Ground outputs in the client's actual documents and require quoted passages.
- Pro caps: unpublished, shared across chat, Code, Cowork, with 5-hour and weekly resets. A solo operator running agents all day will hit them. Plan an upgrade to Max ($100) or move batch work to the API.
- Computer-use and browser agents: useful for drafts and repetitive navigation, unreliable on authenticated portals, CAPTCHAs and government sites. Treat as a supervised assistant. No reliability benchmark verified here.

## 6. Tasks: cheap now vs. still human

Dramatically cheaper (HYPOTHESIS, with human review): document summarization and comparison, first-draft policies/SOPs/manuals from templates, gap checks of a client document against a published checklist, data extraction and form pre-fill from PDFs, regulatory change monitoring and research briefs, meeting notes and correspondence drafts, spreadsheet cleanup.

Still needs human expertise: professional sign-off (licensed advice, attestation, certification), legal interpretation of ambiguous rules, accountability for filings, client relationship and judgment calls, verification of facts, anything involving PHI/CUI, and authenticated submissions to agency portals.

## 7. Cheapest credible stack and monthly cost

| Tier | Stack | Monthly |
|---|---|---|
| Start (public and business-confidential, training off) | Claude Pro $20; Make free or n8n self-hosted $0; free e-sign/invoice/storage tools (not researched) | about $20 |
| Better data protection | Claude Team Standard, 2 seats, $25 each monthly (or $20 annual) = $40-50; or Pro plus API for client files (about $5-20) | about $40-70 |
| With automation | Above plus n8n Cloud ~$20 or Make ~$9 | about $60-90 |
| PHI-capable | Not achievable under $1k setup without a BAA path (Enterprise 20-seat minimum or API-with-BAA via sales). Decline PHI. | not budgeted |

Seats and totals are ESTIMATE. Unverified: Cowork on Pro, consumer-terms commercial clause, current training default, voice agent prices.

## Sources
claude.com/pricing; platform.claude.com/docs/en/about-claude/pricing; claude.com/government; support.claude.com/en/articles/13756069; anthropic.com/news/claude-in-amazon-bedrock-fedramp-high; anthropic.com/news/updates-to-our-consumer-terms; support.claude.com/en/articles/15400594; anthropic.com/legal/commercial-terms; secondary: eesel.ai, appwrite.io, notebookcheck.net, toolradar.com, aptible.com (HIPAA), dev.to Claude HIPAA guide.
