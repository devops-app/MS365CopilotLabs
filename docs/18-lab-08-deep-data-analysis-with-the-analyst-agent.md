# Lab 08 - Deep data analysis with the Analyst agent

| **Level** | **Duration** | **Primary apps** | **Sample files** |
|----|----|----|----|
| 300 | 35 minutes | Microsoft 365 Copilot, Analyst agent | 10_Support_Tickets, 11_Marketing_Performance, 08_Finance_Budget |

## Department and industry focus

Customer Service and Marketing for Contoso Retail, joining service quality to marketing and cost data. Peer-review the agent like an analyst would.

## Scenario

The Analyst agent reasons over data step by step, writes and runs code, and explains its method. Use it for questions too complex for a single formula - joining support quality to marketing and cost - then critically review its analysis.

## Learning objectives

- Use the Analyst agent for multi-step, code-backed analysis over business datasets.

- Ask the agent to expose its assumptions, method, and the columns it used.

- Correlate across datasets (support, marketing, cost).

- Validate the agent's reasoning, not just its answer.

### Exercise 1 - Baseline profiling with method transparency

☐ Open the Analyst agent and attach 10_Mock_Customer_Support_Tickets.xlsx.

```
Analyze the support ticket log.
1. Profile the data: row counts, date range, categories, and any blanks.
2. Compute average resolution hours by priority and by business unit.
3. Compute CSAT and first-contact-resolution rate by channel.
For each result, show the steps and the columns/filters you used.
State any assumption you made (for example, how you treated open tickets).
```

### Exercise 2 - Cross-dataset correlation

☐ Attach 11_Mock_Marketing_Campaign_Performance.xlsx and 08_Mock_Finance_Budget_Variance.xlsx.

```
Explore whether business units with higher marketing spend also show higher
support ticket volume or lower CSAT. Join by business unit where possible.
Rank units by a combined 'demand-and-satisfaction' view and explain how you
built the ranking. Flag any records that could not be matched and how many
were dropped.
```

### Exercise 3 - Hypothesis test

```
Test this hypothesis: 'higher-priority tickets get worse CSAT'. Describe the
comparison you ran, report what the data shows, quantify the effect, and
state clearly whether this is correlation or evidence of causation. List
confounders you could not rule out.
```

### Exercise 4 - Peer review the analysis

```
Critique your own analysis above. Where could the result be wrong? What data
quality issues, sample-size limits, or filter choices could change the
conclusion? Return a short 'analysis risk register'.
```

| **Validation focus:** Check the columns and filters the agent used, whether unmatched records were disclosed, and whether it separated correlation from causation. Re-run one metric manually. |
|----|
