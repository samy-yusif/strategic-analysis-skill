---
name: "strategic-analysis"
description: "Use for a full researched strategic analysis of an existing company or a new venture from scratch, delivered as an Excel model, a Word explanation report and a summary presentation, all in English, with success solutions per framework."
---

# Strategic Analysis (Input → Matching → Decision → Direction → Implementation → Evaluation)

This skill produces a complete, research-backed strategic analysis following the Fred David strategy-formulation sequence. It works in two modes:

- **Mode N — New venture (building a company from scratch).** No company history exists. The analysis studies the industry and competitors first, designs the company's internal setup, chooses the strategy, and only then builds the vision, mission and values from the results.
- **Mode E — Existing company.** The current vision/mission are evaluated at the start; revised versions are written after the decision stage so they reflect the chosen strategy.

Every framework feeds the next one: factors are discovered, filtered, weighted, matched, turned into strategies, scored, and then converted into vision, mission, objectives, an action plan, a budget, KPIs and a business plan. Nothing in a later stage may appear from nowhere: each item must trace back to a factor from an earlier stage.

**Every framework also ends with solutions that raise the chance of success** (section 2). Diagnosis without a solution is not accepted.

## Fixed deliverables

All three deliverables are in English, and their numbers must be identical.

1. **Excel model** — the full working analysis: every framework sheet, live formulas, solutions columns. Built with the xlsx skill (section 11).
2. **Word report (.docx)** — the full written explanation of every framework: method, results, interpretation, solutions, sources. Built with the docx skill (section 12).
3. **Summary presentation** — short executive summary of findings, decision and plan (section 13). Build it from the Slides artifact type when the session lists one; otherwise use the pptx skill. If the user names a format (e.g., PowerPoint file), use that.
4. Confirm these three deliverables with the user before creating any file. Do not produce other files unless asked.
5. Build order: Excel first (source of all numbers) → Word report → presentation.

## 0. Before starting

1. Detect the mode. Ask the user only for what research cannot find:
   - Mode N: business idea / industry, target country or city, intended scale or available capital (range is fine), founders' relevant assets (experience, land, licenses, partners, technology), launch horizon.
   - Mode E: company name, country, analysis year, and any source files (audited statements, annual report, investor presentation). Audited statements beat any website.
2. Do NOT ask the user for competitors, market data or macro data. The skill finds all external data itself (section 1).
3. Build a task list with the stages below so progress is visible.
4. Mindset for gaps: never stop at "not available". State "can be done if…" and use the best proxy (peer data, industry reports, regional averages, analogous markets, management statements), labelled as a proxy.

## 1. Research rules (all external data is searched, never assumed)

- Research comes first; tables are filled only from what was found. Run many separate searches: per PESTEL category, per industry topic, per competitor. One combined search gives shallow results.
- Every factor carries: ID, Source framework, Category, Factor, Evidence (number or fact, with year), Type (O/T or S/W), Source link.
- Macro sources: World Bank (WGI, GDP, population), IMF, central bank (policy rate, inflation, FX), statistics agency, ministries and sector regulators, tax authority, investment authority (company setup, incentives, free zones), Hofstede Insights, Climate Action Tracker / IEA, trade agreement databases.
- Industry sources: market size and growth, segments, demand drivers, customer needs, price ranges, cost structure and margins, entry capital, licensing, supply chain, technology trends — from industry associations, regulators, consultancies, listed-company reports, stock exchange disclosures, credible news.
- 5 years of history; compare the home country with 3-4 benchmark countries (global leader + regional peers) so the position is relative, not absolute.
- Date-stamp all data; flag anything older than 2 years.
- Descriptions must be specific and evidenced ("Policy rate 27.25% in 2024, up from 8.25% in 2021"), never generic ("High interest rate"). A factor without evidence is not allowed into the model.

### 1a. Competitor discovery and profiling (mandatory, done by the skill)
1. Identify competitors by search: market-share rankings, exchange listings, industry reports, top sellers, directories, review platforms, news on new entrants.
2. Classify: direct, indirect/substitutes, recent entrants, potential entrants (regional players expanding).
3. Select 3-5 for the CPM (leader, closest direct rival, best challenger; Mode N also the most comparable recent entrant) and state why.
4. Profile each: ownership, size, revenue and growth, market share, products, pricing, locations, channels, brand position, technology, customer reviews/complaints, recent moves, strengths and weaknesses.
5. Financials: 5 years of statements for listed competitors (filings, annual reports, investor relations); for private ones disclosed figures or labelled estimates.
6. Output a Competitor Landscape sheet used in Porter, CPM, benchmarks and positioning. Competitor weaknesses found in reviews are inputs for success solutions.

## 2. Success solutions in every framework (mandatory)

Each framework sheet in the Excel has two extra columns on every factor row: **Solution / Success Lever** and **Expected Effect**. Each framework section in the Word report ends with a "Solutions to Increase Success" subsection, and the presentation summarises the top levers.

Rules:
- **Threat / Weakness / low rating** → a concrete action that reduces or neutralises it (mitigate, hedge, partner, outsource, redesign, insure, phase).
- **Opportunity / Strength / high rating** → how to exploit or protect it.
- Each solution states: action, owner (function), rough cost level (Low/Med/High, or amount if researched), time to effect, and which score it moves (e.g., "CPM rating on Delivery time 2 → 3", "IFE weakness becomes minor", "Buyer power impact High → Mid").
- Solutions are evidence-based: cite a competitor or market example that worked where possible.
- Use the "can be done if…" form for hard issues: the condition that makes it possible, then the steps.
- Per framework:
  - PESTEL: each threat → hedge or adaptation (FX → local sourcing / FX-linked pricing; high rates → pre-sales, vendor financing).
  - Porter: each strong force → lever to weaken it (switching costs, supplier contracts, differentiation).
  - CPM: each factor where the company trails the leader → gap-closing action and target rating.
  - 7S / Value chain: each misalignment or weak activity → redesign.
  - VRIO: parity resources → how to make them rare or better organised; temporary advantages → how to protect.
  - Ratios: each weak ratio → financial action and target value.
  - EFE/IFE: low response ratings → how to raise them.
  - SPACE/IE/Grand: what would move the company to a better quadrant/cell.
  - QSPM: what would strengthen the chosen strategy's weakest rows, and the fallback strategy.
- Consolidate all solutions into a **Success Levers** sheet: ID | Framework | Factor | Solution | Owner | Cost | Time | Score impact | Priority (High/Med/Low) | Linked TOWS strategy | Linked action-plan row. High-priority levers must appear in TOWS strategies or the action plan.
- Mode N: include a **Success Probability Check** — the top 5 researched reasons ventures in this industry fail, and the venture's countermeasure for each.

## 3. Stage A — Context

- Mode E: introduction (history, segments, scale, footprint, recent moves) and **evaluation of the current** vision (7 criteria: Inspiring, Paints a clear picture, Desirable, Unique, Focused, Feasible, Easy to communicate) and mission (11 components: Customer, Products/Services, Markets, Survival, Growth, Profitability, Technology, Philosophy, Self-concept, Public image, Employees), marking each present/missing with the quoted phrase. Current core values feed 7S Shared Values. Do not rewrite vision/mission yet.
- Mode N: venture brief only. No vision or mission at this stage.

## 4. Stage B — External assessment (Industry Profile → Competitor Landscape → PESTEL → Porter → CPM → IPM External → EFE)

### B0. Industry profile
Market size and 5-yr growth, forecast, segments, customer needs, price ranges, margins and cost structure, entry capital and licensing, key success factors (these feed the CPM).

### B1. PESTEL  (Category | Factor | Type | Desc | Evidence | Source | Solution | Expected Effect)
- Political: government policies & programs, government effectiveness, control of corruption, regulatory quality, rule of law, voice & accountability, political stability (WGI percentile, 5-yr trend), taxes (CIT, VAT, withholding, property), tariffs/customs law, trade agreements, lobbying, monetary policy, sector ministry strategy, investment incentives.
- Economic: GDP growth, interest rates, inflation, FX, unemployment/labor force, disposable income, access to finance, sector demand drivers.
- Social: population and growth, density/urbanisation, age distribution, health/education spending, lifestyle trends, Hofstede's 6 dimensions (Power distance, Individualism, Uncertainty avoidance, Masculinity, Long-term orientation, Indulgence) with score and implication.
- Technology: digital strategy, innovation, R&D % GDP, automation/AI, incentives, adoption rate, industry tech.
- Environment: location, climate, environmental policy rating, sustainability vision, emissions trend, renewable targets.
- Legal: company setup and licensing, employment, consumer protection, contract, health & safety, IP, foreign ownership.
Every row has a Type; neutral cultural dimensions are marked "Context" and excluded from IPM.

### B2. Porter's Five Forces  (Force | Desc | Strength | Evidence | Type | Solution)
New entrants, suppliers, buyers, substitutes, rivalry, evidenced (concentration, switching costs, capital needs, number of competitors, price transparency). Mode N: entry barriers = what the venture must cross, and how. End with overall industry attractiveness.

### B3. CPM
- 8-12 key success factors (e.g., market share, financial position, quality, customer satisfaction, brand, technology, geographic reach, CSR, management, delivery time, global presence).
- Weights sum 1.00, same for all firms. Ratings 1-4 (1 major weakness … 4 major strength), each justified by a fact. Score = Weight × Rating.
- Mode N: rate the venture as planned at launch, honestly, plus a "target year 5" column driven by the solutions. Interpret the gaps, not just totals.

### B4. IPM External
All PESTEL + Porter + industry factors: Source | Category | Factor | Desc | Type | Occurrence | Impact | Priority. Codes 1 High, 2 Mid, 3 Low. Priority = (Occurrence − 1) × 3 + Impact (1 most critical … 9 least; Excel `=(E2-1)*3+F2`). Justify codes. Priority 1-4 → EFE (10-20 factors, balanced O/T; extend to 5 if too few).

### B5. EFE  (Type | Source | Factor | Desc | Weight | Rating | Score | Comment | Solution)
Weights sum 1.00; rating 1-4 = how well the (planned) strategy responds, for both O and T; 2.50 average.

## 5. Stage C — Internal assessment (7S → VDT → VRIO → Value Chain → Financials → Ratios → IPM Internal → IFE)

### Mode E
- 7S (Structure, Systems, Style, Staff, Skills, Strategy, Shared Values) with evidence and hard/soft alignment notes.
- Value Discipline Triad (Treacy & Wiersema): Product Leadership, Customer Intimacy, Operational Excellence 0-100; leading discipline informs generic strategy.
- VRIO: not V → disadvantage; V → parity; V+R → temporary; V+R+I+O → sustained; V+R+I not O → unused. Only temporary/sustained become strengths.
- Value chain: Inbound, Operations, Outbound, Marketing & sales, Services; Firm infrastructure, Technology development, Procurement, HRM — evidenced S/W each.
- Financial statements: 5 years BS, IS, CF for company and listed competitors (Company | Statement | Item | Y1…Y5 | Avg). Source priority: audited consolidated statements (read notes on revenue recognition, unearned revenue, inventory composition) → annual report → filings → data providers. Check A = L + E; state currency and units.
- Ratios: profitability (margins, ROA, ROE), liquidity (current, quick, cash), leverage (liabilities/assets labelled correctly, interest-bearing debt/equity, equity ratio, interest coverage), activity (turnovers, DIO, DSO, DPO, CCC), growth (CAGR). Judge against competitors and trend with industry context (e.g., a developer's inventory is land/WIP, so low turnover can be structural). All by formula.

### Mode N — the planned company
- Resource inventory (founders, capital, assets, licenses, partners, technology).
- Planned 7S with gaps flagged; draft values only.
- Value Discipline choice based on resources and CPM gaps.
- VRIO on actual resources (most are parity at launch; say so).
- Planned value chain (in-house vs outsourced) with risks.
- Financial baseline: startup costs (capex, licensing, pre-opening, working capital) from researched prices; benchmark ratios from competitor statements.
- Liabilities of newness as weaknesses where evidenced: no brand, no track record, no customers, limited scale, funding constraints, unproven processes — each with a solution.

### IPM Internal and IFE (both modes)
Same IPM method; priority 1-4 → IFE; merge duplicates. IFE weights 1.00; strengths 3 (minor) or 4 (major), weaknesses 1 (major) or 2 (minor) — anything else is an error; 2.50 average.

## 6. Stage D — Matching (SWOT & TOWS → SPACE → IE → Grand → BCG / Entry options)

- SWOT/TOWS: S, W, O, T = exactly the IFE/EFE factors, numbered. SO (Maxi-Maxi), WO (Mini-Maxi), ST (Maxi-Mini), WT (Mini-Mini) strategies citing pairs ("S2,O3 – …"), concrete actions, 4-7 per quadrant; high-priority success levers reflected here.
- SPACE: FS +1…+6 (Mode N: capital and projected strength vs benchmarks), IS +1…+6, ES −1…−6 (−6 worst), CA −1…−6 (−1 best). X = CA + IS, Y = FS + ES. Aggressive (+,+), Conservative (−,+), Defensive (−,−), Competitive (+,−). Vector chart.
- IE: X = IFE, Y = EFE; 3.0-4.0 / 2.0-2.99 / 1.0-1.99. Cells I, II, IV Grow & Build; III, V, VII Hold & Maintain; VI, VIII, IX Harvest/Divest. Divisions separately (bubble = revenue share) if segment data exist.
- Grand: market growth (evidenced) vs competitive position (CPM/IFE). Q1 rapid/strong: market development, penetration, product development, forward/backward/horizontal integration, related diversification. Q2 rapid/weak: intensive strategies, horizontal integration, divestiture, liquidation. Q3 slow/weak: retrenchment, diversification, divestiture, liquidation. Q4 slow/strong: diversification, JVs. A new entrant in a growing market usually sits in Q2.
- BCG (Mode E with segment data; otherwise state why skipped). Mode N: market entry options (greenfield, franchise, JV/alliance, small acquisition, niche entry) compared on capital, speed, risk, control.
- Solutions: what would move the company to a better SPACE quadrant / IE cell / Grand quadrant.

## 7. Stage E — Decision

1. Alternatives: strategies in at least two matching tools (Mode N: plus entry options), 2-4, described with factor references.
2. QSPM: same factors and weights (each block 1.00); AS 1-4; "—" across a row when the factor doesn't affect the choice; no equal AS where it matters; TAS = W × AS; sum per strategy; one line of reasoning per non-trivial AS.
3. Sensitivity: does ranking change if the top 3 weights move ±5 points? Gap under 5% = report as close.
4. Solutions: strengthen the chosen strategy's weakest rows; name the fallback strategy and its trigger.

## 8. Stage F — Direction (built from the analysis)

1. Inputs table: target segment, core offer, markets, value discipline, main competitive advantage, opportunities seized, stakeholder priorities.
2. Vision (Mode N new; Mode E proposed): 2-3 options scored on the 7 criteria; choose and explain.
3. Mission: all 11 components, each traceable to the inputs; component check with quoted phrase.
4. Core values: 4-7, from strategy and culture findings (Hofstede, 7S gaps), with how each shows in behaviour.
5. Mode E: current vs proposed side by side with scores.
6. Shown in the Excel (Vision-Mission sheet), explained in the Word report (options, scoring, rationale), and stated on one slide in the presentation.

## 9. Stage G — Recommendations to Implementation

1. Recommendations ranked by QSPM, with factor references and phasing (year 1 vs later).
2. 3-5 SMART objectives aligned with the mission, each tied to a strategy.
3. Business-level strategy: Porter generic (cost leadership, differentiation, focus, or hybrid with stated emphasis) consistent with value discipline; cooperative strategies (alliances/JV) where relevant.
4. Action plan (Strategy | Objective | Functional objective | Responsibility | Resources | KPI | Action | Y1…Y5 budget | Total | Linked success lever): every action maps to an objective; SUM formulas by year and strategy; Gantt; budget benchmarked against size or available capital.
5. Financial projection (5 years), driver-based: volumes × prices from strategies and share targets, margins from benchmarks, working-capital days from BSC targets, action-plan spend, financing. Mode N adds startup cost table, funding plan, year-1 monthly cash flow, break-even, payback, NPV/IRR at a researched discount rate. Base and Downside cases; assumptions block with sources; balance sheet balances; projected ratios vs BSC targets. Trend functions (FORECAST.ETS) only as cross-check.
6. Risk register: top risks, probability, impact, mitigation (from success levers), trigger.

## 10. Stage H — Evaluation

Balanced Scorecard (Perspective | Objective | KPI | Baseline | Target 5-yr | Initiative) across Financial, Customer, Internal Process, Learning & Growth. Baselines from ratios or research (Mode N: launch values or benchmarks); targets match the projection; initiatives link to action-plan rows; quarterly KPI review, annual strategy review, corrective-action triggers.

## 11. Excel model (English) — build rules

- Sheet order: Brief/Profile, Industry, Competitors, PESTEL, Porter, CPM, IPM, EFE, 7S, VDT, VRIO, Value Chain, Fin Statement (E) or Startup & Benchmarks (N), Financial Ratios, IPM Internal, IFE, SWOT & TOWS, SPACE, IE, Grand, BCG / Entry Options, QSPM, Vision-Mission, Success Levers, Recommendations, Action Plan, Fin Projection, Risk Register, BSC, Sources.
- Excel tables and formulas for every score, total, priority, ratio and budget; EFE/IFE factors linked into SWOT and QSPM by reference, so a weight change updates everything downstream.
- Solution and Expected Effect columns on every framework sheet.
- Recalculate and verify no formula errors (xlsx skill).

## 12. Word report (English) — full explanation

Purpose: a reader who never opens the Excel understands what each framework is, how it was applied, what it found, what it means, and what to do about it.

For every framework section use the same structure:
1. **Purpose** — what the tool measures and why it sits at this point in the sequence (2-3 lines).
2. **Method** — scales, weights, scoring rules and data sources used.
3. **Results** — the table (full if short; key rows if long, with a pointer to the Excel sheet), plus a chart where it helps.
4. **Interpretation** — the "so what": 4-8 lines linking findings to strategy and to the next framework.
5. **Solutions to Increase Success** — the top solutions for that framework, each with owner, cost level, time and score impact.
6. **Sources** — cited inline or as footnotes.

Report outline:
- **Mode N:** Cover, table of contents, executive summary, 1. Venture brief  2. Industry profile  3. Competitor landscape  4. External assessment (PESTEL, Porter, CPM, IPM, EFE)  5. Internal assessment of the planned company (resources, 7S, value discipline, VRIO, value chain, financial baseline, IPM, IFE)  6. Matching (SWOT/TOWS, SPACE, IE, Grand, entry options)  7. Decision (alternatives, QSPM, sensitivity)  8. Vision, Mission & Values  9. Recommendations  10. Objectives  11. Business strategy  12. Implementation (action plan, Gantt, budget)  13. Financial plan (startup costs, funding, projections, break-even)  14. Risk register  15. Evaluation (BSC)  16. Success levers summary and success probability check  17. Business plan (company and legal setup, organization, products/services, market analysis, STP, 7Ps, market entry and launch roadmap, operations, resources)  18. Limitations  19. References and appendix.
- **Mode E:** Cover, table of contents, executive summary, 1. Introduction  2. Current vision & mission evaluation  3. Industry & competitor landscape  4. External assessment  5. Internal assessment (incl. financial statements and ratios)  6. Matching (incl. BCG if applicable)  7. Decision  8. Proposed vision, mission & values  9. Recommendations  10. Objectives  11. Business strategy  12. Implementation  13. Financial projection  14. Risk register  15. Evaluation (BSC)  16. Success levers summary  17. Business plan  18. Limitations  19. References and appendix.

Formatting: heading styles (so the table of contents works), numbered tables and figures with captions, page numbers, consistent number formats and units, charts inserted as images rendered from the Excel data. Body text 11-12 pt. Clear professional English, no filler.

## 13. Summary presentation (English)

Purpose: an executive grasps the whole analysis in 15-25 minutes. Summary only; detail lives in the Word report and Excel. One message per slide, written as the slide title (e.g., "Buyer power and rivalry are the main threats"), charts and compact tables instead of paragraphs, small source line on data slides.

Slide outline (about 18-22 slides; merge or split to keep each readable):
1. Title  2. Executive summary (chosen strategy, QSPM result, vision, top risk, top 3 success levers)  3. Company / venture overview  4. (Mode E) Current vision & mission verdict  5. Market size and growth  6. Competitor landscape  7. Key external findings (PESTEL + Porter heat map of top opportunities and threats)  8. CPM: where we lead and trail  9. EFE and IFE scores with the 3 most important factors each  10. Internal findings (7S, VRIO, value chain, financial health or startup baseline)  11. SWOT / TOWS highlights  12. Strategic position (SPACE, IE, Grand on one slide)  13. QSPM result and why  14. Vision, mission & values  15. Objectives and business strategy  16. Action plan timeline and budget  17. Financial outlook (Mode N: funding, break-even)  18. Balanced Scorecard targets  19. Top 10 success levers  20. Key risks and mitigations  21. Next steps

After building, render the slides and check: no text overflow, charts readable, numbers match the Excel and Word report.

## 14. Quality checklist (before delivering)

- [ ] All external data and competitors found by research, with evidence, year and source; competitor selection explained.
- [ ] Every framework has solutions on its rows and a solutions block; each solution has owner, cost level, time and score impact.
- [ ] Success Levers sheet complete; high-priority levers linked to TOWS or the action plan. Mode N has the success probability check.
- [ ] Every row has a Type; no blank descriptions; same factor has the same Type everywhere.
- [ ] IPM priorities by formula; EFE/IFE contain priority 1-4 factors (or stated exception).
- [ ] CPM, EFE, IFE, each QSPM block: weights sum to 1.00.
- [ ] IFE: strengths 3-4, weaknesses 1-2. Mode N rates the venture honestly at launch.
- [ ] SWOT = EFE + IFE exactly; QSPM uses same factors and weights.
- [ ] SPACE signs and quadrant correct; IE cell matches totals; labels say IFE/EFE correctly.
- [ ] QSPM strategies come from at least two matching tools; "—" rows used where a factor does not differentiate.
- [ ] Vision, mission and values written after the decision and traceable to the inputs table.
- [ ] Ratios recomputed from statements; balance sheet balances historically and in projections; Mode N has funding plan, break-even and cash runway.
- [ ] Objective → action → budget → KPI → BSC → projection chain complete.
- [ ] Excel, Word report and presentation all in English; numbers identical across the three.
- [ ] Word report: every framework has Purpose, Method, Results, Interpretation, Solutions, Sources; table of contents, captions and page numbers work.
- [ ] Presentation is a summary (about 18-22 slides), action titles, no slide overloaded with text.
- [ ] Limitations stated: weak data, proxies, judgment-heavy ratings, what would change the recommendation.

## 15. Delivering

After the user approves: deliver the Excel model, the Word report and the summary presentation, with a 3-5 line summary (in the user's language) of the chosen strategy, the QSPM result, the vision statement, the biggest risk and the top 3 success levers. List sources at the end.