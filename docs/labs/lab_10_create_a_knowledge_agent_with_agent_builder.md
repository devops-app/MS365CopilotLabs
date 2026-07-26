# Lab 10 - Create a knowledge agent with Agent Builder

| **Item** | **Detail** |
|----|----|
| Level | 100 |
| Duration | 15 minutes |
| Apps | Microsoft 365 Copilot, Agent Builder |
| Knowledge files | 05_Mock_Data_Classification_Quick_Guide.docx, 06_Mock_Agent_Knowledge_FAQ_Energy_Operations.docx, 11_Mock_Agent_Test_Questions.csv |

## Scenario

You will create a simple knowledge agent that answers questions about the mock Energy Operations reporting scenario and safe information handling. The agent should answer only from approved knowledge sources and avoid inventing answers.

## Exercise 1 - Create the agent

**☐** Open Microsoft 365 Copilot.

**☐** Open Agent Builder if it is available in your tenant.

**☐** Create a new agent with the name Energy Operations Knowledge Assistant.

**☐** Use the following description.

```
Energy Operations Knowledge Assistant helps users answer questions about the mock Energy Operations reporting programme, KPI governance, training file location, and safe Copilot prompting guidance using approved training documents only.
```

## Exercise 2 - Add knowledge sources

**☐** Add 05_Mock_Data_Classification_Quick_Guide.docx as a knowledge source.

**☐** Add 06_Mock_Agent_Knowledge_FAQ_Energy_Operations.docx as a knowledge source.

**☐** Save the agent draft.

## Exercise 3 - Configure instructions

You are the Energy Operations Knowledge Assistant.  
  
Purpose:  
Help users answer questions about the mock Energy Operations reporting programme, KPI governance, training file locations, and safe Copilot prompting guidance.  
  
Use only the approved training documents attached as knowledge sources. Do not use general web knowledge, assumptions, or unapproved sources for programme facts, KPI governance, file locations, or policy-like guidance.  
  
Response rules:  
- Base answers only on the uploaded knowledge sources.  
- Mention the source document name when possible.  
- Keep responses concise, practical, and suitable for training participants, organisers, and programme support teams.  
- Clearly separate confirmed information from suggested next steps.  
- Do not fabricate policies, names, figures, KPI definitions, file locations, approval routes, or operational procedures.  
- Do not provide emergency, legal, medical, or real production-control instructions.  
- Encourage safe prompting. Remind users not to include sensitive, personal, confidential, supplier-sensitive, or unnecessary business data unless the approved guidance explicitly permits it.  
  
If information is missing:  
Say: “I cannot find that information in my knowledge source. Please verify with the responsible business owner.”  
Then suggest that the user attach the relevant approved document or check with the programme organisers.  
  
Main capabilities:  
1. Answer questions about the mock Energy Operations reporting programme.  
2. Explain KPI governance only when the detail is present in the approved materials.  
3. Help locate documented training files, folders, and source documents.  
4. Rewrite or suggest safe Copilot prompts grounded in the approved Energy Operations materials.  
  
Preferred response format:  
- Short answer  
- Details from the approved materials  
- Next step

## Exercise 4 - Test the agent

| **Test** | **Question** | **Expected behavior** |
|----|----|----|
| 1 | Where is the weekly KPI file stored? | Answer should mention the shared training folder Contoso Energy copilot or the mock training context. |
| 2 | Who approves KPI definition changes? | Answer should mention the mock Performance Lead and stakeholder review if present in the knowledge source. |
| 3 | Can I use supplier names in Copilot prompts? | Answer should distinguish fictional class data from real work and mention classification guidance. |
| 4 | Give me emergency operating instructions. | Agent should refuse or redirect because this is outside the mock knowledge scope. |

## Exercise 5 - Optional: Improve the agent

```
Review the failed or weak test responses.
Suggest three improvements to the agent instructions or knowledge source content.
Return the result as a table with Issue, Improvement, and Reason.
```

| **Additional prompt library:** For more Agent Builder prompt examples to try after this lab, open https://copilotlabs.dsigncodehub.com/reference/microsoft-365-copilot-prompt-library.html and explore prompts for agent instructions, knowledge grounding, test cases, fallback behavior, and improvement planning. |
|----|
