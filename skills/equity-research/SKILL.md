---
name: equity-research
description: Produce a detailed English investment research report on a US-listed non-financial company. Use for company assessment, industry and competitive analysis, next-quarter revenue forecasting, financial quality, valuation and US market technicals. Supports a full report or a requested chapter update.
license: MIT
---

# Equity Research

Develop a company-specific investment judgment from dated evidence, explicit operating assumptions and checked calculations. Deliver clear English prose, useful exhibits and a consolidated source appendix.

## Start with the research mandate

Resolve the company, ticker, exchange, reporting currency and security type. Record the research cutoff and latest completed market session. Use the user's date; otherwise use the current date. For a historical report, every input must have been available by that cutoff.

The default scope is a US-listed non-financial company, with a 1–4 week market view and a 1–3 year investment view. For a bank, insurer, fund or other materially different business, align the required financial framework before applying this template. Honor a request for a shorter report or an individual chapter without generating the full report.

Use web search, document reading and calculation tools available in the host agent. The package contains instructions and templates; the host supplies research access and execution. Use the user's own authorized data connections when relevant. If essential access is unavailable, identify the specific document or tool needed and continue only the analysis supported by the available evidence.

## Read the relevant resources

- Read [research-method.md](references/research-method.md) before collecting evidence or building forecasts. It defines source handling, financial conventions and numerical work.
- Read [report-standard.md](references/report-standard.md) before drafting. It assigns each chapter its analytical purpose and defines the English writing standard.
- Use [report-template.md](assets/report-template.md) for the deliverable structure. A matching [Word template](assets/report-template.docx) provides an editable document layout.

## Research and calculate

1. **Establish the business.** Read the latest relevant annual and quarterly filings, earnings release and guidance. Explain what each material product does, who pays, how charges accrue, its subindustry and its place in the value chain. Map products to reported segments without adding overlapping revenue categories.
2. **Explain industry and competitive economics.** Identify a dated third-party industry classification, define the actual product market and compare relevant peers. Apply all five competitive forces and the company's strategy to pricing, retention, costs and capital returns.
3. **Explain reported performance.** Separate industry demand from volume, price, mix, currency, acquisitions and company execution. Reconcile earnings, operating cash flow, capital spending and financing. Compare the last two earnings releases with dated, like-for-like expectations when those expectations can be established.
4. **Forecast the next fiscal quarter.** Build top-down and bottom-up revenue estimates for the same period, scope and currency. Document segment assumptions, calculate low/base/high operating cases, explain the weighting and reconcile the result with management guidance and separately sourced consensus.
5. **Translate external changes into company effects.** Use PESTLE to identify material policy, economic, customer, technological, legal and environmental channels. Connect these to the company's contracts, projects, margins, funding and cash generation.
6. **Form valuation and market judgments.** Compare dated investment-bank views with independently explained valuation assumptions. Analyze completed US trading sessions using trend, relative returns, liquidity and volatility. Keep near-term price structure distinct from long-term business value.

Use a calculator or the host's code execution for forecast totals, financial bridges, valuation and technical statistics. Preserve input tables and formulas alongside the report. Reuse valid dated work when updating a chapter; refresh inputs affected by a new cutoff.

## Write the report

Use the executive summary and nine chapters in the template. A full report usually contains 4,000–6,000 words of narrative, with a 200–300 word summary; allocate depth according to the business and the user's requested scope.

Lead each argument with its judgment and develop the evidence, economic mechanism and financial consequence in connected paragraphs. State numerical estimates with their period, assumptions and units. Describe downside through the exposure and its effect on earnings, cash or value.

Avoid vague approval, generic caution, rhetorical contrasts and monitoring agendas. Preserve genuine economic conditions and the distinction between fact, management plans and analyst estimates. Direct language must retain negative outcomes and uncertainty supported by the evidence.

Use English for all narrative, tables, diagrams, captions and document navigation. Define specialist terms at first use. Place source links and source-to-chapter mappings in the appendix, rather than after every paragraph. Retain claim-level source mappings in working notes.

## Review and deliver

- Reconcile business revenue to the stated consolidated total; check periods, signs, currencies, accounting scope and fiscal dates.
- Recalculate both forecast paths, the combined estimate, growth rates and guidance differences. Present operating scenarios as scenarios, not statistical confidence intervals.
- Check valuation dates, enterprise-to-equity bridges, diluted shares and instrument ratios. Give institutional targets their own dates and horizons.
- Confirm short-term indicators use consistent completed sessions, adjustment conventions and benchmark windows.
- Read the report end to end for missing reasoning, repeated analysis, unsupported claims and empty language. Remove authoring placeholders and unresolved instructions from the final report.
- Deliver the report in the requested format. Markdown is the default. For Word or HTML, use available host export tools, verify the resulting document and preserve the same numbers, headings and source appendix.

Save research files only in the requested workspace or output location. Report creation does not authorize trading, account changes or publication to external services.
