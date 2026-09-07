---
layout: default
title: "Lab 02 - Contract review summary and dual-audience rewrite"
---

# Lab 02 - Contract review summary and dual-audience rewrite

| **Level** | **Duration** | **Primary apps** | **Sample files** |
|----|----|----|----|
| 200 | 30 minutes | Microsoft Word, Microsoft 365 Copilot | 02_Legal_Contract_Review_Notes, 04_Project_Charter |

## Department and industry focus

Legal & Compliance reviewing a technology (CloudWorks / SaaS) vendor agreement. The output must satisfy both lawyers and business sponsors.

## Scenario

A vendor Master Services Agreement is in review. Legal must turn raw review notes into a structured summary that a business sponsor can act on, without overstating certainty or giving binding advice.

## Learning objectives

- Draft a structured review summary from source notes using Copilot in Word.

- Rewrite for two audiences (legal and business sponsor) without losing accuracy.

- Convert negotiation points into a governance-ready table.

- Validate that the summary introduces no terms absent from the source.

### Exercise 1 - Draft the review summary

☐ Open a new Word document and start the Copilot drafting experience.

☐ Add 02_Mock_Legal_Contract_Review_Notes.docx and 04_Mock_CrossFunction_Project_Charter.docx as sources.

☐ Submit the prompt, review, Keep it if suitable, and save as Lab02_Contract_Review_Summary.docx.

```
Create a contract review summary from the linked review notes and charter.
Sections:
- Overview (what the agreement is for)
- Key issues and recommended positions
- Risk ratings (high/medium/low) with rationale
- Data-protection and regulated-industry considerations
- Open questions for the vendor
Use precise, neutral language. This is a summary, not legal advice.
Mark any missing detail as 'Not stated in source'.
```

### Exercise 2 - Dual-audience rewrite

```
Produce two versions of the Key issues section:
1. Legal version: precise, cites each clause concern and fallback position.
2. Business sponsor version: 4 sentences, plain language, focused on cost,
timeline, and decision needed.
Keep both strictly consistent with the source. Do not add new terms.
```

### Exercise 3 - Negotiation points table

```
Convert the issues into a table: Issue | Risk | Current draft position |
Recommended position | Owner | Decision required.
If a field is not in the source, write 'Not stated'.
```

> **Quality check:** Manually confirm every clause position in the summary matches the review notes and that neither audience version introduces a term the source did not state.
