# Lab 10 - Create a knowledge agent with Agent Builder

| Item | Detail |
|---|---|
| Level | 100 |
| Duration | 15 minutes |
| Apps | Microsoft 365 Copilot, Agent Builder |
| Knowledge files | `05_Mock_Data_Classification_Quick_Guide.docx`, `06_Mock_Agent_Knowledge_FAQ_Energy_Operations.docx`, `11_Mock_Agent_Test_Questions.csv` |

## Scenario

You will create a simple knowledge agent that answers questions about the mock Energy Operations reporting scenario and safe information handling. The agent should answer only from approved knowledge sources and avoid inventing answers.

## Exercise 1 - Create the agent

- [ ] Open Microsoft 365 Copilot.
- [ ] Open Agent Builder if it is available in your tenant.
- [ ] Create a new agent with the name **Energy Operations Knowledge Assistant**.
- [ ] Use the following description.

```text
Energy Operations Knowledge Assistant helps users answer questions about the mock Energy Operations reporting programme, KPI governance, training file location, and safe Copilot prompting guidance using approved training documents only.
```

## Exercise 2 - Add knowledge sources

- [ ] Add `05_Mock_Data_Classification_Quick_Guide.docx` as a knowledge source.
- [ ] Add `06_Mock_Agent_Knowledge_FAQ_Energy_Operations.docx` as a knowledge source.
- [ ] Save the agent draft.

## Exercise 3 - Configure instructions

```text
Answer only from the uploaded knowledge sources.
Do not fabricate policies, names, figures, or operational procedures.
If the requested information is not available, respond:
"I cannot find that information in my knowledge source. Please verify with the responsible business owner."
Do not provide emergency, legal, medical, or real production-control instructions.
Keep answers concise and cite or mention the source document when possible.
```

## Exercise 4 - Test the agent

| Test | Question | Expected behavior |
|---|---|---|
| 1 | Where is the weekly KPI file stored? | Answer should mention the shared training folder Contoso Energy copilot or the mock training context. |
| 2 | Who approves KPI definition changes? | Answer should mention the mock Performance Lead and stakeholder review if present in the knowledge source. |
| 3 | Can I use supplier names in Copilot prompts? | Answer should distinguish fictional class data from real work and mention classification guidance. |
| 4 | Give me emergency operating instructions. | Agent should refuse or redirect because this is outside the mock knowledge scope. |

## Exercise 5 - Optional: Improve the agent

```text
Review the failed or weak test responses.
Suggest three improvements to the agent instructions or knowledge source content.
Return the result as a table with Issue, Improvement, and Reason.
```

---

**Training data notice:** Synthetic mock training content only. Do not use real confidential, restricted, personal, legal, supplier-sensitive, or operational-control data in prompts. Validate Copilot outputs before sharing or acting on them.
