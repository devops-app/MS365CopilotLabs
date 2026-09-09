---
layout: default
title: "Lab 06 — Sales pipeline analytics"
---

# Lab 06 — Sales pipeline analytics

| Level | Duration | Primary apps | Sample files |
| --- | --- | --- | --- |
| 300 | 35 minutes | Microsoft Excel, Microsoft 365 Copilot | `09_Sales_Pipeline` |

## Department and industry focus

Sales managing a technology (CloudWorks / SaaS) pipeline across industries and regions. Level 300 Excel work.

> ⏱️ **Timing note:** Labs 05 and 06 are both Level 300 Excel challenges. In a time-boxed class, complete one as the required activity and keep the other for self-paced practice.

## Scenario

You are preparing the monthly sales review. Leadership wants to know weighted pipeline value, which stages and segments are strongest, and where deals are at risk — and then what the quarter looks like if those risks land. Expect to move from describing the current pipeline to forecasting expected close value and testing what-if scenarios such as slipped close dates or shifted win probabilities.

## Learning objectives

- Analyze pipeline value, weighted value, and stage distribution with Copilot in Excel.
- Segment pipeline by industry, region, product, and owner.
- Distinguish committed, best-case, and at-risk pipeline, avoid double counting, and express coverage as a ratio of weighted pipeline to the period target.
- Produce a leadership-ready pipeline summary.
- Forecast expected close value from stage, probability, and close date, and test what-if scenarios such as slipped dates or shifted win probabilities.

## Exercise 1 — Pipeline summary

```text
Summarize this pipeline. Report:
- Total pipeline value and total weighted value
- Value by stage and by product
- Weighted value by industry and by region
- Win rate implied by closed-won vs closed-lost
Keep open, won, and lost as separate categories - do not combine.
```

## Exercise 2 — Segment and risk view

```text
Segment the pipeline: which industry, region, and owner carry the most
weighted value, and which deals look at risk (late stage, low probability,
or close date passed). Present as a table with evidence and clearly label
any judgement that depends on an assumption.
```

## Exercise 3 — Pipeline dashboard

```text
Create charts for value by stage, weighted value by industry, and pipeline
by region. Add a PivotTable of weighted value by owner and stage. Place
them on a new worksheet named Pipeline Dashboard.
```

## Exercise 4 — Pipeline forecast and what-if scenarios

- [ ] With the pipeline workbook open, run this prompt.

```text
Using only the columns in this workbook, forecast the value expected to
close in the current and next quarter from stage, probability, and close
date, then model three what-if scenarios:
- late-stage probabilities improved by 10 points
- every deal with a passed close date slipping one quarter
- the two largest open deals lost
For each scenario report forecast value, the change against the base case,
coverage against total open pipeline, and the assumptions behind it.
Show the columns and formulas used, keep closed-won and closed-lost out of
the forecast, and present each result as a scenario built from the mock data
rather than a prediction.
```

## Exercise 5 — Sales review briefing

```text
Create a one-page sales review for leadership: total and weighted pipeline,
strongest and weakest segments, at-risk deals, and 3 recommended actions
with owners. Separate confirmed figures from interpretation.
```

> ⚠️ **Validation:** Confirm weighted value uses probability correctly and that closed-lost is excluded from open pipeline. Correlation between owner and win rate is a hypothesis, not proof.
