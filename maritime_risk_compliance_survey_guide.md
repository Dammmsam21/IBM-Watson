# Maritime Risk & Compliance Survey — Secondary Research & Answer Guide

> **Purpose of this document.** Question-by-question guidance for the maritime risk & compliance survey, built from publicly available secondary sources. It distinguishes three kinds of questions and treats each differently:
>
> 1. **Profile questions** (industry, region, role, org size, fleet type, spend, which tools you actually have) — there is **no "correct" answer**. The only valid answer is the one that reflects the respondent's real situation. Putting in false profile data corrupts the dataset and, in incentivised panels, is treated as fraud. For these I describe the option set and what each implies, not a "right pick".
> 2. **Knowledge / attention-filter questions** (AF2, AF3, AF4) — these **do have factually correct answers**, verifiable against regulators (OFAC) and maritime references. I give the correct value and the distractors to avoid.
> 3. **Opinion / rating questions** (Q13, Q16, Q23, Q30, Q33 ratings, Q34 NPS) — no right/wrong; I give the market consensus so a rating can be sanity-checked against how each vendor is generally perceived.
>
> **On "market share by geography":** none of these five providers publish audited, geography-level market-share numbers (they are private companies or divisions of larger groups). The geographic picture below is a **reasoned synthesis** from each vendor's heritage, disclosed customer base, and product focus — directional, not statistical. Where I give rough weightings they are clearly labelled as estimates.

*Sources are linked inline. Content from third-party sources was rephrased for compliance with licensing restrictions.*

---

## 1. Market context (for Q36–Q42, and general framing)

- The "maritime information / intelligence" software segment is estimated at roughly **USD 2.4–2.8 billion in 2024–2026, growing ~8–9% a year** toward ~USD 5–6 billion by the early-to-mid 2030s ([MarkWide Research](https://markwideresearch.com/global-maritime-information-market/), [SkyQuest](https://www.skyquestt.com/report/maritime-information-market)). The broader "maritime security" market is far larger (~USD 24–27B) but includes hardware, defence and physical security ([Mordor Intelligence](https://www.mordorintelligence.com/industry-reports/maritime-security-market-growth-trends-and-forecast-2019-2024)).
- **Demand drivers** named repeatedly by the vendors and regulators: intensifying sanctions enforcement, the **"dark"/"shadow" fleet**, AIS/GNSS spoofing and jamming, flag/registry fraud, and fragmented enforcement across the US, EU and UK ([Windward](https://windward.ai/blog/maritime-sanctions-2025-expert-windward-insights/), [S&P Global shadow-fleet research](https://www.spglobal.com/market-intelligence/en/news-insights/research/maritime-shadow-fleet-formation-operation-and-continuing-risk-for-sanctions-compliance-teams-2025)). This is why most respondents will report **rising spend** over the past 3 years (relevant to Q39/Q40INC).

---

## 2. The five vendors at a glance

| Vendor (survey label) | Core product | Heritage / HQ | Strongest with | Signature strength |
|---|---|---|---|---|
| **S&P Global / IHS** | Maritime Intelligence Risk Suite (MIRS), Sea-web, AISLive, Ship Compliance dataset | IHS Markit lineage; US-HQ group | Classification societies, registries, technical/ownership users, large FIs | Authoritative **vessel registry, ownership & IMO-number** reference data; 250,000+ vessels ([S&P](https://www.spglobal.com/marketintelligence/en/mi/products/maritime-and-trade-risk-compliance.html)) |
| **Lloyd's List Intelligence (Seasearcher)** | Seasearcher + Advanced Risk & Compliance | Lloyd's List (UK), centuries-old shipping brand | Shipowners/operators, insurers/P&I, legal, brokers | Proprietary AIS + **human expertise + editorial content**; 3,000+ sources ([LLI](https://www.lloydslistintelligence.com/solutions/seasearcher)) |
| **Pole Star (PurpleTRAC)** | PurpleTRAC (screening workflow), PurpleFinder, LRIT, Pole Star Platform | London-HQ | **Banks, trade finance, insurers, commodity traders** | Purpose-built **sanctions-screening workflow with audit trail** vs OFAC/UN/EU/HM Treasury ([Pole Star](https://www.polestarglobal.com/use-cases/sanctions-screening/)) |
| **Kpler (Risk & Compliance)** | Kpler R&C + MarineTraffic + Spire Maritime AIS | Founded Paris/Brussels; London-centric now | **Commodity & energy traders**, plus broad AIS user base | **Commodity trade-flow intelligence fused with vessel tracking**; owns MarineTraffic & Spire AIS ([Kpler](https://kpler.com/solution/risk-compliance), [Spire sale](https://ir.spire.com/news-events/press-releases/detail/251/)) |
| **Windward** | Maritime AI platform (Entity Management, screening, DSP detection) | Israel-HQ | **Governments/regulators**, FIs, energy, insurers, traders | **Behavioral AI risk scoring**; ~300 customers; flagged 100% of recently UK-designated vessels pre-designation ([Windward](https://windward.ai/blog/expanded-uk-sanctions-heighten-maritime-risk-and-compliance-pressure/)) |

---

## 3. Vendor popularity by geography (directional synthesis)

> Estimates below are **qualitative**. No vendor publishes audited regional share. Treat "High / Medium / Low" as relative prominence in that geography for *risk & compliance* use cases.

### Americas (US-centric)
The US is the **enforcement epicentre** (OFAC), so demand is heaviest among banks, trade finance, energy/commodity majors and government.
- **Windward** – High (US government/regulator and FI traction).
- **S&P Global / IHS** – High (US-HQ, registry/ownership authority, large enterprise relationships).
- **Kpler** – High among **energy/commodity traders**.
- **Pole Star** – Medium (banks/trade finance).
- **Lloyd's List Intelligence** – Medium.

### UK & Western Europe (EMEA core)
Mature compliance market; London/Geneva trading and insurance hubs; active EU + UK sanctions regimes.
- **Lloyd's List Intelligence** – High (UK heritage; shipping, insurance, legal, P&I).
- **Pole Star** – High (London-HQ; banks, P&I, trade finance).
- **Kpler** – High (European commodity-trading hubs; Geneva/London/Brussels roots).
- **Windward** – Medium-High (EU/UK regulators and FIs).
- **S&P Global** – Medium-High.

### Middle East
Crude/products trade, bunkering, growing port and trading activity; significant exposure to sanctioned-oil routing risk.
- **Kpler** – High (energy/commodity flow focus).
- **Lloyd's List Intelligence** and **S&P Global** – Medium-High (vessel/ownership reference).
- **Windward** – Medium (government and energy).
- **Pole Star** – Medium (trade finance/banks).

### Asia-Pacific (Singapore, HK, China, Japan, Korea)
Singapore = commodity trading/bunkering/ship-finance hub; large shipbuilding/registry/classification base in NE Asia.
- **S&P Global / Sea-web** – High (registry, classification, technical and shipyard users historically rely on IHS/Sea-web).
- **Lloyd's List Intelligence** – High (deep shipping-industry penetration).
- **Kpler / MarineTraffic** – High (very broad AIS user base; commodity desks).
- **Windward** – Medium and growing.
- **Pole Star** – Medium (banks/LRIT).

### Quick "who's popular for what" (segment view, cross-geo)
- **Banks / trade finance / FIs:** Pole Star (PurpleTRAC), Windward, Lloyd's List Advanced Compliance.
- **Commodity & energy traders:** Kpler (first call), S&P Global, Windward.
- **Shipowners / operators / brokers / insurers / P&I:** Lloyd's List Intelligence, S&P Sea-web, Windward.
- **Governments / regulators / defence:** Windward, Lloyd's List Intelligence.
- **Classification / registry / technical / ownership reference:** S&P Global (IHS) Sea-web.

---

## 4. Question-by-question guidance

### Screening & profile block

**[intro] Consent** — Recommended: **Yes / I agree** (you cannot proceed otherwise). Not a data question.

**[Q1] Industry** — *Profile; answer truthfully.* Typical option set: Banking/financial services; Commodity trading; Shipping/ship owner-operator; Insurance/P&I; Energy/oil & gas; Legal/professional services; Government/regulator; Logistics/freight; Classification society. **The survey is screening for maritime-risk-relevant industries** — pick the one that genuinely matches your organisation. There is no "advantaged" answer; an off-target industry may simply terminate or reroute you.

**[Q2] Region you primarily operate in** — *Profile; answer truthfully.* This is the field that powers any geo cut of the data. Choose the region of your actual role. (If the study wants spread across geos, that is the survey owner's quota concern, not something an individual respondent should fake.)

**[Q3] Role / function** — *Profile.* Likely options: Compliance/sanctions; Risk; Operations; Trading/chartering; Legal; Procurement; Senior management; Analyst. Answer to your real function. Compliance/risk/operations are the "in-scope" personas the study is built around.

**[Q4] Do you use maritime risk & compliance solutions?** — *Screening gate.* Honest **Yes** if you do; the named examples (Lloyd's List/Seasearcher, Pole Star/PurpleTRAC, Windward, S&P/IHS, Kpler) define scope. A **No** will usually screen you out — don't answer Yes unless it's true.

### Attention-filter / knowledge block (these DO have right answers)

**[AF1] Vessel/entity checks per week** — *No objective correct value; must reflect reality.* For calibration: an individual front-line compliance analyst commonly runs anywhere from a handful to a few hundred checks/week; a centralised team or automated/API screening can be thousands. **Avoid implausible extremes** (e.g., "0" while claiming to be an active user, or absurdly high numbers inconsistent with org size in Q5).

**[AF2] Regulator most associated with vessel-related sanctions enforcement**
- ✅ **Correct / recommended:** **OFAC** — the U.S. Treasury's Office of Foreign Assets Control. It is the body behind the maritime sanctions advisories and most vessel designations ([OFAC May 2020 advisory](https://ofac.treasury.gov/recent-actions/20200514)).
- ❌ **Wrong distractors to avoid:** IMO (safety/standards, not sanctions), IMF, WTO, ICC, WCO, or a flag-state registry. *(If the option list is non-US-framed, "OFAC" remains the single safest choice; EU Council / UK OFSI are real sanctions bodies but OFAC is the one "most associated" with vessel sanctions enforcement.)*

**[AF3] Example of a maritime sanctions-related deceptive shipping practice (DSP)**
- ✅ **Correct / recommended (any of these):** **Disabling or manipulating AIS** ("going dark"/spoofing); **falsifying cargo or vessel documents**; **ship-to-ship (STS) transfers to disguise origin**; **false flags / flag-hopping**; **physically altering vessel identity (IMO number/name)**; **complex/opaque ownership structures** ([Crowell summary of OFAC advisory](https://www.crowell.com/en/insights/client-alerts/new-u-s-sanctions-advisory-for-the-maritime-industry); [OFAC](https://ofac.treasury.gov/recent-actions/20200514)).
- ❌ **Wrong distractors to avoid:** ordinary lawful operations dressed up as suspicious — e.g., "filing a port call notice", "paying canal transit tolls", "broadcasting AIS continuously", "registering with a classification society", "buying marine insurance". These are normal, not deceptive.

**[AF4] What type of data does AIS transmit?**
- ✅ **Correct / recommended:** **Vessel identification and position/navigation data** — i.e., identity (MMSI/name/IMO/call sign), **position, course, speed and navigational status** (plus voyage fields like draught/destination) ([Nautical Institute](https://www.nautinst.org/resources-page/how-ais-works-and-what-it-does.html); [Wikipedia: AIS](https://en.wikipedia.org/wiki/Automatic_identification_system); [MarineTraffic](https://support.marinetraffic.com/en/articles/9552860-what-kind-of-information-is-ais-transmitted)).
- ❌ **Wrong distractors to avoid:** "cargo manifests / bill-of-lading details", "financial/payment data", "crew personal records", "weather forecasts", "encrypted military comms". AIS does **not** carry these.

### Organisation profile

**[Q5] Size of relevant activity / [Q6] Vessel type(s)** — *Profile; answer truthfully and keep consistent with AF1 and Q36.* Q6 options usually span tankers (crude/product), dry bulk, container, gas (LNG/LPG), general cargo, offshore, passenger. Pick what your organisation actually deals with. (Tankers and gas carriers are the highest-sanctions-risk segments, but only select them if true.)

### Access, usage & decision-making

**[Q7] Solutions your organisation has access to** / **[Q8] Solutions you personally use** — *Behavioural; answer truthfully.* Multi-select from the five named vendors (+ "Other" open field that later pipes into the Q24/Q25/Q26/Q33 loops as `${Q8.r98.open}`). Only tick tools you genuinely have/use — these selections drive most downstream looped questions.

**[Q9] Your involvement in selection** / **[Q10] Who leads the decision** / **[Q11] Which teams use them** — *Profile.* Q10 commonly: Compliance, Risk, Procurement, IT, Operations, or Senior leadership. Answer to your real org. (Higher decision-involvement respondents are usually more valuable to the study, but don't overstate.)

### Use cases & importance

**[Q12] Key use cases** (multi-select) — the canonical set this survey uses (mirrored in Q14/Q15 loop): **Vessel KYC & due diligence; Counterparty risk/screening; Trade/cargo risk screening; Vessel tracking/continuous monitoring & alerts; Fleet/voyage monitoring; Regulatory audit trail & compliance documentation;** plus "Other" (`Q12.r98.open`). Select those you actually run.

**[Q13] Importance of each use case (1–5)** / **[Q16] How critical (1–5)** — *Opinion.* Market reality: **sanctions screening, KYC/counterparty due diligence and continuous monitoring are typically rated mission-critical (4–5)** by FIs and traders, because the cost of a breach is regulatory/financial. Rate honestly; clustering everything at "5" reduces analytical value.

### Primary/secondary solution & rationale loop

**[Q14] Primary & secondary solution per use case** — *Behavioural.* Pick the tool you actually rely on for each. Market tendencies (only as a sanity check):
- *Sanctions/counterparty screening with audit trail* → Pole Star PurpleTRAC, Windward, Lloyd's List Advanced Compliance.
- *KYC/due diligence & ownership* → S&P/IHS (ownership reference), Lloyd's List, Windward.
- *Trade/cargo risk* → Kpler (commodity flows), Windward.
- *Vessel tracking / monitoring & alerts* → Lloyd's List Seasearcher, Kpler/MarineTraffic, Windward, S&P AISLive.
- *Fleet/voyage monitoring* → S&P Sea-web, Lloyd's List, Kpler.

**[Q15_Lr1…Lr7] Why is [piped vendor] your primary for each use case?** — *Open text.* Answer about the tool you actually named in Q14. Useful, on-message reasons that match each vendor's real strengths: data quality/coverage, fewer false positives, workflow fit, auditability, integration/API, analyst trust, brand/regulator acceptance.

### Multi-vendor behaviour

**[Q17] Use more than one solution?** — *Behavioural.* Many serious compliance teams **do** run two (a data/registry source + a screening/AI layer) — answer truthfully.

**[Q18] Reasons for multiple solutions** — typical: corroboration/second opinion, different data strengths, coverage gaps, false-positive reduction, regulator expectations, redundancy.

**[Q19] How often one tool flagged a risk another missed** — *Opinion/experience.* This is the survey's "why two tools matter" question. Answer from genuine experience; "occasionally/sometimes" is the most common honest answer.

**[Q20] Would you consider switching to one provider only?** / **[Q21YES]/[Q21NO]** — *Opinion.* YES drivers: cost, simpler workflow, vendor consolidation. NO drivers: risk of missed flags, coverage gaps, regulatory defensibility, internal embedding.

**[Q22] If forced to one provider, which?** — *Opinion.* Choose the one you'd genuinely keep. Consolidation tends to favour the broadest-data players (Kpler, S&P, Lloyd's List) or the strongest workflow/AI (Windward, Pole Star), depending on whether your priority is data or workflow.

**[Q23] Importance of editorial commentary / broader content (1–5)** — *Opinion.* Note this question structurally favours **Lloyd's List Intelligence** (its editorial heritage). Rate by how much you actually value news/analysis alongside data.

### Per-vendor experience loops (only appear for tools selected in Q8)

**[Q24_Lr1–6] Frequency of use** / **[Q25_Lr1–6] How you interact (UI, API, reports, alerts)** / **[Q26_Lr1–6] How long you've used each** — *Behavioural; answer per tool truthfully.* `Lr6`/`${Q8.r98.open}` only appears if you entered an "Other" vendor at Q8.

### Adoption history & switching

**[Q27] How you handled these use cases before** — typical: manual checks, spreadsheets, in-house lists, generic AIS, broker/agent calls, generic sanctions screening not maritime-specific.

**[Q28] Why you adopted specialist solutions** / **[Q29] Main benefits** — typical, well-supported answers: tightening regulation, dark-fleet/evasion complexity, audit/defensibility, efficiency/time saved, fewer false positives, broader coverage.

**[Q30] Difficulty of switching away from primary (1–5)** / **[Q31] Reasons it's hard** — *Opinion.* Embedded API integrations, trained staff, historical audit records, workflow dependence and data continuity usually make switching "fairly hard" (3–4) for core screening tools.

### Selection criteria & ratings

**[Q32] Top-3 selection criteria** — option set (also piped into Q33 as `${Q32.r98.open}`): **Quality of data; Breadth of coverage; Ease of use/delivery; Reputation/brand; Industry-specific workflow; Ease of integration; Customer support;** + Other. Pick your genuine top 3. (Across this market, **data quality, coverage and workflow/integration** are the most commonly cited deciders.)

**[Q33KPC1–8 × Lr1–6] Rate each vendor 1–5 on each criterion** — *Opinion.* Rate only what you've used. Consensus reputational tendencies, as a sanity check (not instructions to copy):
- *Data quality & coverage:* S&P/IHS and Lloyd's List strong on registry/ownership; Kpler strong on commodity-flow + AIS; Windward strong on behavioral risk signals.
- *Industry-specific workflow & audit:* Pole Star PurpleTRAC and Windward rate well for compliance workflow.
- *Ease of integration/API:* Kpler, Windward, S&P commonly cited.
- *Reputation/brand:* Lloyd's List and S&P carry the strongest legacy brand weight.
- *Customer support:* varies by account; no clear public leader.

**[Q34] NPS (0–10) per used solution** / **[Q35] Primary reason** — *Opinion.* Score from genuine satisfaction; Q35 should explain the score in terms of the Q32/Q33 criteria.

### Spend (Q36–Q42)

**[Q36] Total annual spend** / **[Q37] How much more before switching** / **[Q38] Number of internal teams using these** — *Profile/financial; answer truthfully and keep consistent with Q5/Q6/AF1.* Q37 captures price elasticity/stickiness — embedded primary tools usually tolerate a meaningful increase before switching, but answer to your real tolerance.

**[Q39] 3-year spend change** — Market reality strongly skews to **Increased** (sanctions pressure, dark-fleet complexity) — but answer for your organisation.
- **[Q40INC] Drivers of increase:** more regulation/enforcement, more vessels/counterparties to screen, new use cases, headcount/licences, added data sources.
- **[Q40DEC] Drivers of decrease:** vendor consolidation, cost-cutting, bringing capability in-house, reduced activity.

**[Q41] Other maritime intelligence products purchased** — typical: market/freight analytics, AIS/satellite data feeds, port/congestion data, weather routing, emissions/ETS compliance, credit/counterparty data, valuation/S&P (sale-and-purchase) data.

**[Q42] Spend on those additional solutions** — *Financial; answer truthfully, consistent with Q36.*

---

## 5. Bottom line

- **Only AF2, AF3 and AF4 have objectively "right" and "wrong" answers** — OFAC; an actual deceptive practice (AIS manipulation / STS / false docs / flag-hopping); and AIS = identity + position/navigation data. Everything else is profile, behaviour or opinion, where the only correct answer is the truthful one.
- **No vendor publishes audited geographic market share.** The geo/segment view in §3 is directional: S&P/IHS and Lloyd's List dominate legacy vessel/ownership reference (strong in Europe and APAC); Kpler leads commodity/energy-trade intelligence and now owns major AIS assets (MarineTraffic, Spire); Pole Star leads bank/trade-finance screening workflow; Windward leads behavioral-AI risk and government/regulator use (strong in the US, UK, EU).
- If this is an **incentivised research panel**, answering profile/financial questions untruthfully to "pass" is survey fraud and risks disqualification — the value of this guide is getting the **knowledge questions right** and **sanity-checking opinion ratings** against how the market actually perceives each vendor.
