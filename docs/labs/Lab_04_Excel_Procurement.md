---
lab:
    title: 'Lab 04: Analyze procurement spend with Copilot in Excel'
    description: 'Use Copilot in Excel to summarize procurement data, identify trends, visualize spend, and generate executive insights.'
    level: '100'
    duration: '30 minutes'
    isLab: true
    primaryTopics: 'Microsoft Excel, Microsoft 365 Copilot'
---

# Lab 04 - Analyze procurement spend with Copilot in Excel

| Item | Detail |
| --- | --- |
| Level | 100 |
| Duration | 30 minutes |
| Apps | Microsoft Excel, Microsoft 365 Copilot |
| Sample file | 08_Mock_Procurement_Spend_Analysis.xlsx |

> [!IMPORTANT]
> These labs use synthetic mock content only. Do not use real BP confidential information, employee data, supplier records, operational procedures, or restricted business data in prompts.

## Scenario

You are reviewing mock procurement spend data. You need to identify major spend categories, top suppliers, anomalies, and risks that should be escalated to management.

### Exercise 1 - Explore the dataset

- [ ] Open **08_Mock_Procurement_Spend_Analysis.xlsx** from OneDrive.
- [ ] Confirm the data is formatted as a table.
- [ ] Open Copilot from the Home tab.
- [ ] Submit the following prompt.

```text
Summarize this procurement dataset.

Identify:
- Total spend
- Top suppliers
- Major spend categories
- Highest spending business units
- Any risk flags visible in the data
```

### Exercise 2 - Create a supplier spend view

```text
Create a table showing supplier spend ranked from highest to lowest.

Include:
- Supplier
- Total spend
- Number of purchase orders
- Average invoice amount
- Risk observation
```

### Exercise 3 - Visualize category trends

```text
Create charts that show spend by category and spend by business unit.

Add the charts to a new worksheet named Procurement Dashboard.
```

### Exercise 4 - Detect anomalies and concentration risk

```text
Analyze the data for unusual spend patterns.

Look for:
- Large invoice amounts
- Supplier concentration
- Categories with unusually high spend
- Business units with repeated risk flags

Return findings in a table with recommended management actions.
```

### Exercise 5 - Draft an executive insight summary

```text
Create an executive summary of the procurement analysis.

Use this structure:
- Key findings
- Risks
- Possible savings opportunities
- Questions for Procurement
- Recommended next steps
```

