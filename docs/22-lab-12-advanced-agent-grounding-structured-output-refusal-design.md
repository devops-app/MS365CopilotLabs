# Lab 12 - Advanced agent: grounding, structured output, refusal design

| **Level** | **Duration** | **Primary apps** | **Sample files** |
|----|----|----|----|
| 300 | 35 minutes | Microsoft 365 Copilot, Agent Builder | 06_CS_FAQ, 05_Prompt_Safety, 08_Finance_Budget, 13_Mock_Agent_Test_Questions.csv |

## Department and industry focus

Finance & Compliance - harden the Help Assistant (or build a Budget Query Assistant) so it produces consistent structured output, grounds every answer, and refuses out-of-scope or unsafe requests by design.

## Learning objectives

- Engineer instructions that force a consistent, structured response schema.

- Design grounding and refusal behaviour as explicit, testable rules.

- Add few-shot examples to steer tone and format.

- Define measurable acceptance criteria for the agent.

### Exercise 1 - Define a response schema

```
Add to the agent instructions a required response schema:
Answer: <one to three sentences>
Source: <document name or 'not found'>
Confidence: <high | medium | low>
Next step: <action or 'none'>
The agent must use this schema for every substantive answer and set Source
to 'not found' when the knowledge base does not contain the answer.
```

### Exercise 2 - Grounding and refusal rules

```
Add explicit rules:
- If a question is outside HR / customer-service / budget-query scope,
refuse briefly and state the scope.
- Never output credentials, card numbers, patient data, or personal data.
- If asked to act as an authority (approve spend, waive a control), refuse
and redirect to the responsible owner.
- If sources conflict, say so and present both with their source names.
```

### Exercise 3 - Few-shot steering

```
Add two worked examples: Example A - an in-scope FAQ answered in the schema
with a source. Example B - a missing-knowledge question answered with
Source: not found and a safe next step. Keep them short and consistent.
```

### Exercise 4 - Structured budget query

```
Using 08_Mock_Finance_Budget_Variance.xlsx as knowledge, have the agent
answer: 'Which departments need attention this month?'
Require a ranked table: Business unit | Department | Variance % | Status |
Recommended action | Source. Rank by variance. The agent must not invent
figures not present in the data.
```

### Exercise 5 - Acceptance criteria

```
Write measurable acceptance criteria, for example:
- >= 95% of in-scope answers use the schema and cite a source
- 100% of missing-knowledge answers set Source: not found
- 0 fabricated policies, figures, or personal data across the test set
- 100% refusal on out-of-scope or unsafe prompts
```

> **Validation focus:** Run the same 10 questions twice. A hardened agent should give consistent, schema-conformant answers both times. Inconsistency signals weak instructions.
