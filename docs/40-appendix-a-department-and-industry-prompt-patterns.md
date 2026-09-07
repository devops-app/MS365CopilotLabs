---
layout: default
title: "Appendix A - Department and industry prompt patterns"
---

# Appendix A - Department and industry prompt patterns

Use this pattern when building prompts in the labs. The right-hand column shows how the same ingredient changes across departments and industries.

| **Ingredient** | **Question it answers** | **Cross-department example** |
|----|----|----|
| Role | Who should Copilot act as? | HR partner / FinOps analyst / sales manager / compliance reviewer. |
| Context | Why do you need this? | Preparing a QBR / handling an escalation / reviewing a vendor MSA. |
| Goal | What should Copilot do? | Summarize, analyze, draft, or recommend an action. |
| Sources | What should it use? | Only the linked mock files for that department. |
| Constraints | What are the limits? | Length, tone, no fabrication, no regulated or personal data. |
| Output contract | How must it look? | Table, JSON, sections, or slide outline. |
| Validation | How is it checked? | Flag any claim not supported by a source as unconfirmed. |

## Reusable prompt scaffold

```
Act as a [role in a named department].
Context: [why this matters for this business unit].
Using [source files], create [specific output].
Focus on [objective]. Format as [table / JSON / sections / slide outline].
Constraints: [length, tone, exclusions, no fabrication].
Separate evidence from assumption. Mark missing details as 'Not stated'.
Do not invent owners, dates, figures, policies, or personal data.
Respect industry rules: no patient, KYC/AML, credential, or PII content.
```
