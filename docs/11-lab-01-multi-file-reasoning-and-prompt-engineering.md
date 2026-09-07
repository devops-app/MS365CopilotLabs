---
layout: default
title: "Lab 01 - Multi-file reasoning and prompt engineering"
---

# Lab 01 - Multi-file reasoning and prompt engineering

| **Level** | **Duration** | **Primary apps** | **Sample files** |
|----|----|----|----|
| 200 | 25 minutes | Microsoft 365 Copilot Chat | 01_HR_Handbook, 04_Project_Charter, 07_Standup_Notes, 05_Prompt_Safety |

## Department and industry focus

Human Resources working across all six business units, supported by cross-functional and operations context. This shows how one HR question spans healthcare, financial, and manufacturing rules.

## Scenario

A new cross-department programme is spinning up. HR must synthesize the employee handbook, the cross-functional project charter, and messy operations stand-up notes into a single, source-aware picture of people impacts and actions - then stress-test the prompting technique.

## Learning objectives

- Ground Copilot Chat on multiple work files in one prompt and keep the answer traceable to each source.

- Apply a repeatable prompt pattern: role, context, goal, sources, constraints, output contract, validation.

- Force Copilot to separate evidence from assumption and flag unsupported claims.

- Iterate deliberately to improve precision rather than accepting the first answer.

### Exercise 1 - Multi-file situational brief

```
Act as an HR business partner supporting a cross-department programme.
Using /01_Mock_HR_Employee_Handbook_Extract.docx,
/04_Mock_CrossFunction_Project_Charter.docx, and
/07_Mock_Operations_Standup_Notes.docx, produce a situational brief.
Sections:
- Current state (2-3 sentences)
- Confirmed facts, each tagged with the source file name
- People and compliance impacts by business unit (note where HealthCare or
Financial rules differ)
- Assumptions or gaps NOT supported by the sources
- Top 3 risks with likelihood and impact
- Decisions required this week
Rules: do not invent owners, dates, or metrics. If a detail is missing,
write 'Not stated in sources'. Keep it under 250 words.
```

### Expected result

- Each confirmed fact cites which file it came from.

- Industry-specific differences (e.g., HealthCare privacy training) are called out, not blurred.

- No fabricated metrics, owners, or dates.

### Exercise 2 - Contrastive analysis

```
Compare the risks in the project charter with the issues in the stand-up
notes. Where do they agree, where do they diverge, and which charter risk
(if any) is already showing up in operations? Present as a 3-column table:
Theme | Charter view | Stand-up evidence.
Flag any conclusion that requires an assumption to hold.
```

### Exercise 3 - Output contract and refusal test

```
From the same sources, return a JSON array of action items. Each object:
{action, owner_or_role, department, priority(1-4), due_date_or_null,
source_file, confidence(high|medium|low)}.
Only include actions explicitly supported by a source. Do not guess dates.
Then, in plain text, list any action you were asked to invent but refused,
and explain why.
```

> **Debrief question:** Which single change to your prompt (role, source scoping, output contract, or the 'Not stated' rule) improved accuracy the most, and why?
