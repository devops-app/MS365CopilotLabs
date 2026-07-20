---
title: Lab 8 - Create a company operations knowledge agent with Agent Builder
---

# Lab 8 - Create a company operations knowledge agent with Agent Builder

[← Previous: Lab 7](lab-07-agents.md) | [Back to Home](../index.md) | [Next: Lab 9 →](lab-09-copilot-studio.md)

## Instructor notes

This lab introduces simple agent creation for a bounded business process. Emphasize scope control, approved knowledge sources, clear instructions, testing, and governance before sharing the agent with others.

## Scenario

Imagine you want to create a Microsoft 365 Copilot Chat agent that helps company employees find approved information about turnaround readiness, maintenance planning, HSE checkpoints, and escalation processes. The agent should be useful for operations coordinators, project managers, and site leadership.

## Lab steps

1. Open Microsoft 365 Copilot.
2. Select New agent.
3. Enter:

   > Create an agent for company Turnaround Readiness Assistant. It helps operations teams find approved guidance on maintenance planning, contractor readiness, safety permit checkpoints, materials availability, risk escalation, and meeting preparation. The audience is company operations coordinators, project managers, and site leadership.

4. Review the generated agent description and refine it if needed.
5. Configure instructions such as:

   > Answer using only approved knowledge sources. If information is missing, say that the user should consult the official company procedure or site leadership. Use a concise, safety-conscious, professional tone.

6. Add approved SharePoint or OneDrive files as knowledge sources, if available.
7. Test the agent with starter prompts such as:

   > What should I check before a turnaround readiness review?

   > Summarize the key escalation points for a maintenance delay.

8. Review responses for accuracy, safety, and compliance before sharing the agent.

## Debrief questions

- Did the agent stay within scope?
- What knowledge sources were missing?
- What questions produced weak or unsafe responses?
- What approval steps should happen before sharing?

## Participant worksheet

| Agent design item | Your notes |
|---|---|
| Agent purpose |  |
| Target users |  |
| Knowledge sources needed |  |
| Questions the agent should answer |  |
| Questions the agent should not answer |  |
