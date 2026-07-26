# Lab 09 - Use built-in agents with Researcher and Analyst

| **Item** | **Detail** |
|----|----|
| Level | 100 to 200 |
| Duration | 15 minutes |
| Apps | Microsoft 365 Copilot, Researcher agent, Analyst agent |
| Sample files | 01_Mock_Project_Charter_Energy_Data_Platform.docx, 08_Mock_Procurement_Spend_Analysis.xlsx, 09_Mock_HSSE_KPI_Dashboard.xlsx, 10_Mock_Project_Cost_Schedule_Control.xlsx |

## Scenario

You need to prepare a leadership-ready research and analysis pack for the mock Energy Data Platform initiative. You will use Researcher for multi-source investigation and Analyst for structured data analysis, then compare when each built-in agent is more appropriate than standard Copilot Chat.

## Learning objectives

- Explain when to use Researcher, Analyst, and standard Copilot Chat.

- Use Researcher to produce a structured, source-aware briefing from multiple work files.

- Use Analyst to inspect spreadsheet data, identify patterns, and create data-driven recommendations.

- Validate outputs by checking source coverage, assumptions, and unsupported claims.

## Exercise 1 - Choose the right built-in agent

**☐** Open Microsoft 365 Copilot.

**☐** Open the Agents area and locate Researcher and Analyst if they are available in your tenant.

**☐** Discuss with your group which agent is best for research synthesis, spreadsheet analysis, and quick drafting.

## Exercise 2 - Use Researcher for a multi-source briefing

```
Use Researcher to prepare a leadership briefing on the mock Energy Data Platform initiative.

Use these sources:
- /01_Mock_Project_Charter_Energy_Data_Platform.docx
- /09_Mock_HSSE_KPI_Dashboard.xlsx
- /10_Mock_Project_Cost_Schedule_Control.xlsx

Create a structured briefing with:
- Executive summary
- Key findings
- Risks and dependencies
- Decisions required
- Recommended next actions

Clearly separate facts from assumptions and mention which source supports each major finding where possible.
```

### Expected result

- A structured report that combines project, HSSE, and cost context.

- Clear distinction between evidence, assumptions, and recommendations.

- Decision points are written for a leadership audience rather than as raw notes.

## Exercise 3 - Use Analyst for spreadsheet insight

```
Use Analyst to examine /08_Mock_Procurement_Spend_Analysis.xlsx.

Analyze:
- Top spend categories
- Supplier concentration
- Unusual or high-value transactions
- Possible cost-saving opportunities
- Recommended management actions

Return the answer as a table and include a short explanation of the analysis steps used.
```

## Exercise 4 - Compare Researcher, Analyst, and Copilot Chat

| **Tool** | **Best use** | **Validation focus** |
|----|----|----|
| Researcher | Multi-step research across files and broader context. | Check sources, assumptions, and completeness. |
| Analyst | Advanced analysis of tables, spreadsheets, and numerical patterns. | Check calculations, filters, chart logic, and assumptions. |
| Copilot Chat | Quick summaries, drafting, brainstorming, and follow-up questions. | Check whether the answer is sufficient for the task or needs deeper research. |

| **Additional prompt library:** For more Researcher, Analyst, and advanced Copilot prompt examples to try after this lab, open https://copilotlabs.dsigncodehub.com/reference/microsoft-365-copilot-prompt-library.html and explore prompts for multi-source research, spreadsheet analysis, assumptions, evidence checks, and management recommendations. |
|----|

| **Instructor guidance:** If Researcher or Analyst is not available, complete the lab as a prompt-design and output-review exercise using standard Copilot Chat. Emphasize source selection, validation, and deciding when deeper reasoning is required. |
|----|
