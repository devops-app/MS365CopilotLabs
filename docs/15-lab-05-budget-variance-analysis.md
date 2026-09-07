---
layout: default
title: "Lab 05 - Budget variance analysis"
---

# Lab 05 - Budget variance analysis

| **Level** | **Duration** | **Primary apps** | **Sample files** |
|----|----|----|----|
| 300 | 35 minutes | Microsoft Excel, Microsoft 365 Copilot | 08_Finance_Budget_Variance |

## Department and industry focus

Finance analysing spend across all business units, with Manufacturing cost pressure in focus. Level 300 Excel work.

## Scenario

Group spend is trending over budget in a few pockets. As part of the finance review you must find the overspend drivers, quantify them, and produce defensible recommendations - all validated against the workbook.

## Learning objectives

- Use Copilot in Excel to profile budget vs actual by business unit, department, and category.

- Identify the departments and categories driving variance.

- Build a dashboard and derive simple variance metrics.

- Convert findings into a prioritized action list you can defend.

### Exercise 1 - Profile the variance

☐ Open the workbook, confirm the data is an Excel table, then open Copilot in Excel.

```
Profile this budget dataset. Return:
- Total YTD budget, YTD actual, and overall variance %
- Top 5 departments by overspend (USD and %)
- Variance split by business unit and by cost category
- Which categories are most often over budget across units
- Any obvious data quality issues.
State the columns you used for each calculation.
```

### Exercise 2 - Driver and anomaly detection

```
Identify the biggest variance drivers:
- Departments more than 15% over YTD budget
- Categories with the largest absolute overspend
- Business units with the widest spread across departments
Return a table: Finding | Evidence (values/columns) | Estimated impact |
Recommended action | Confidence.
```

### Exercise 3 - Build the variance dashboard

```
Create charts for: variance % by department, actual vs budget by business
unit, and overspend by cost category. Add a PivotTable of variance by
business unit and department. Place everything on a new worksheet named
Variance Dashboard.
```

### Exercise 4 - Prioritized action list

```
Create a prioritized action table: Opportunity | Lever (reforecast /
cost control / reallocation / approval) | Estimated impact | Effort (S/M/L)
| Risk | Owner or role | Decision required. Rank by impact-to-effort.
Do not present a number unless it is visible in the data.
```

> **Validation:** Re-check totals, the overall variance %, and any single figure against the workbook. Confirm filters are not hiding rows. Do not present a recommendation unless its evidence is visible.
