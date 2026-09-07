# Lab 09 - Multi-source business investigation

| **Level** | **Duration** | **Primary apps** | **Sample files** |
|----|----|----|----|
| 300 | 35 minutes | Microsoft 365 Copilot, Researcher agent | 04_Charter, 03_Campaign_Brief, 02_Contract_Notes, 08_Budget, 12_Ops_KPI |

## Department and industry focus

Strategy / programme office pulling a cross-functional readiness view together for the leadership QBR - spanning marketing, legal, finance, and operations across business units.

## Scenario

The Researcher agent performs multi-step, source-aware investigation across many files. Commission a rigorous readiness briefing that separates evidence from inference and is defensible in front of leadership.

## Learning objectives

- Frame a research question with explicit scope, sources, and an evidence standard.

- Require per-claim source attribution and an evidence-vs-assumption split.

- Direct multi-step reasoning across documents and data.

- Stress-test completeness and source coverage.

### Exercise 1 - Commission the briefing

☐ Open the Researcher agent and add the five source files listed above.

```
Act as a programme director. Research the readiness of Contoso Group for the
quarterly business review.
Sources: the project charter, the marketing campaign brief, the contract
review notes, the budget variance workbook, and the operations KPI workbook.
Produce a briefing with:
- Executive summary
- Key findings, each with the supporting source named
- Evidence vs assumptions (two clearly separated lists)
- Risks and dependencies with severity, by business unit where relevant
- Decisions required, written for leadership
- Open questions the sources cannot answer
Do not fill gaps with general knowledge; mark unknowns as unknown.
```

### Expected result

- Findings are traceable to named sources; inference is separated from fact.

- Decisions are leadership-ready, not raw notes; unknowns are explicitly listed.

### Exercise 2 - Deepen a single thread

```
Take the top risk from your briefing and investigate it end to end across
all sources: where it originates, how it shows up in the data, and which
decision could increase or reduce it. Produce a cause-effect chain with
sources.
```

### Exercise 3 - Completeness and coverage check

```
Review your own briefing for gaps. Which sources did you rely on most, which
did you barely use, and what additional evidence would materially change the
conclusions? List what a reviewer should verify first.
```

> **Validation focus:** Confirm every major finding is tied to a named source, unknowns are labelled, and the agent did not substitute general knowledge for missing programme facts.
