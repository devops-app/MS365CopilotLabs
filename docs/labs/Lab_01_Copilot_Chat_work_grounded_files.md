# Lab 01 - Explore Copilot Chat with work-grounded files

| Item | Detail |
|---|---|
| Level | 100 |
| Duration | 10 minutes |
| Apps | Microsoft 365 Copilot Chat |
| Sample files | `01_Mock_Project_Charter_Energy_Data_Platform.docx`, `05_Mock_Data_Classification_Quick_Guide.docx` |

## Scenario

You need to quickly understand a project charter and produce an executive-ready summary. You will use Copilot Chat to summarize a source file, refine the response, and convert insights into actions.

## Learning objectives

- Reference a OneDrive file in Copilot Chat.
- Use context, goal, source, and expectations in a prompt.
- Iterate on Copilot output to improve usefulness.
- Validate and structure generated content for business use.

## Exercise 1 - Summarize the project charter

- [ ] Open Microsoft 365 Copilot Chat.
- [ ] Use Work mode if available.
- [ ] Reference the project charter file from the sample data folder.
- [ ] Submit the following prompt.

```text
Summarize /01_Mock_Project_Charter_Energy_Data_Platform.docx.
Include:
- Purpose
- Business problem
- Objectives
- Major deliverables
- Top risks
- Decisions required
Use an executive briefing format.
```

### Expected result

- A concise project summary.
- Risks and decisions are separated from general background.
- The response refers to the content of the project charter rather than inventing details.

## Exercise 2 - Improve the summary for leadership

```text
Rewrite the summary for senior leadership.
Keep it under 200 words.
Use clear bullet points.
Highlight only the decisions that require management action.
```

## Exercise 3 - Create an action table

```text
Create an action table from the project charter.
Columns:
- Action
- Owner or role
- Priority
- Due date if available
- Risk if delayed
- Recommended next step
```

> **Debrief question:** Which prompt produced the most useful answer, and what changed when you specified audience, format, and decision context?

---

**Training data notice:** Synthetic mock training content only. Do not use real confidential, restricted, personal, legal, supplier-sensitive, or operational-control data in prompts. Validate Copilot outputs before sharing or acting on them.
