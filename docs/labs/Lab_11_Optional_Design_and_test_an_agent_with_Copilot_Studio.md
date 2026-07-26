# Lab 11 Optional Design and test an agent with Copilot Studio

Lab 11 - Optional: Design and test an agent with Copilot Studio
Scenario
You will design a Procurement Support Agent based on a mock use case specification. The goal is to practise agent scope, knowledge grounding, test cases, fallback behavior, and governance thinking.
Exercise 1 - Review the use case
```
Summarize /07_Mock_Copilot_Studio_Use_Case_Spec.docx.

Extract:
- Agent purpose
- Intended users
- Supported scenarios
- Out-of-scope scenarios
- Knowledge requirements
- Governance requirements
```
Exercise 2 - Draft agent instructions
```
Create draft instructions for a Procurement Support Agent.

The instructions must include:
- What the agent should do
- What the agent must not do
- How to handle unsupported requests
- How to respond when source information is missing
- When to recommend escalation
```
Exercise 3 - Configure the agent in Copilot Studio
☐ Open Copilot Studio.
☐ Create a new agent named Procurement Support Agent.
☐ Use the agent purpose and instructions created in Exercise 2.
☐ Add the use case specification as a knowledge source if the environment supports file knowledge.
☐ Save the agent draft.
Exercise 4 - Run test cases
☐ Open 11_Mock_Agent_Test_Questions.csv.
☐ Run each test question against the agent.
☐ Record whether each response passed or failed.
☐ Record the issue if a response fails.
Exercise 5 - Improve the agent design
```
Based on the test results, recommend improvements to the Procurement Support Agent.

Return a table with:
- Test ID
- Weakness found
- Recommended change
- Expected benefit
```