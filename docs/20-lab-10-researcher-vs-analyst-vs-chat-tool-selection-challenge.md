---
layout: default
title: "Lab 10 — Researcher vs Analyst vs Chat: tool selection challenge"
---

# Lab 10 — Researcher vs Analyst vs Chat: tool selection challenge

| Level | Duration | Primary apps | Sample files |
| --- | --- | --- | --- |
| 200 | 20 minutes | Copilot, Researcher agent, Analyst agent | All datasets and documents |

## Department and industry focus

All departments and all six business units. Every role — HR, Legal, Marketing, Sales, Finance, Customer Service, Operations, and IT — faces the same choice between a quick answer, a researched briefing, and a calculated result, so this lab is deliberately industry-neutral and draws its examples from every other lab in the workbook.

## Scenario

Choosing the right Copilot surface is a core skill. For each question, decide whether Copilot Chat, the Researcher agent, or the Analyst agent is the best tool, justify it, and define how you would validate the answer.

## Learning objectives

- Match a business question to the right Copilot surface — Copilot Chat, the Researcher agent, or the Analyst agent.
- Justify that choice to a colleague using the nature of the task, not the tool's novelty.
- Describe how you would validate each type of answer, from a quick summary to a code-backed calculation.
- Recognise when a question needs two tools chained rather than one.

## Exercise — Decide and justify

| # | Question | Best tool | Why |
| --- | --- | --- | --- |
| 1 | Which departments are most over budget and by how much? | Analyst | Calculation and ranking over structured data with transparent logic. |
| 2 | How ready is Contoso Group for the QBR across all sources? | Researcher | Multi-source synthesis; needs attribution and evidence-vs-assumption split. |
| 3 | Rewrite this escalation update for an executive audience. | Copilot Chat | Single-step drafting from known context; no deep analysis. |
| 4 | Is CSAT worse for higher-priority tickets? | Analyst | Numeric comparison over structured data with method transparency. |
| 5 | What decisions should leadership make this quarter? | Researcher | Combines charter, risk, cost, and ops context into decisions. |
| 6 | Summarize the campaign brief into five bullets. | Copilot Chat | Quick single-source summarization; deep reasoning not required. |

Forecasting and what-if questions — for example, what full-year variance looks like if spend holds at the current run rate, or what the quarter closes at if late-stage probabilities improve — belong with the Analyst agent or Copilot in Excel, because both can show the formula, assumptions, and columns behind a projected number. Copilot Chat is the wrong surface for them: it can describe a scenario in words, but it cannot calculate one reproducibly, and no surface should be asked to project beyond the periods the source data covers.

## Reference guidance

| Tool | Best use | Validation focus |
| --- | --- | --- |
| Copilot Chat | Quick summaries, drafting, single-source questions, brainstorming. | Is the answer sufficient, or does it need deeper research or analysis? |
| Researcher | Multi-step synthesis across files and broader context. | Source coverage, evidence vs assumption, completeness. |
| Analyst | Calculations, trends, correlations, code-backed data work. | Columns, filters, joins, sample size, correlation vs causation. |

> 💬 **Debrief question:** For question 5, when would you run Analyst first to produce evidence, then hand it to Researcher to synthesize? Discuss chaining agents.
