---
title: Lab 9 - Create a company knowledge-support agent in Microsoft Copilot Studio
---

# Lab 9 - Create a company knowledge-support agent in Microsoft Copilot Studio

[← Previous: Lab 8](lab-08-agent-builder.md) | [Back to Home](../index.md)

## Instructor notes

Use Copilot Studio to show more controlled agent development, including description, instructions, knowledge, testing, publishing, and lifecycle management. Reinforce that operational, safety, and emergency scenarios require strict governance and approved content.

## Scenario

In this exercise, you create a Copilot Studio agent for a company-style employee knowledge-support scenario. The agent helps users ask questions about approved operational guidance, safety reminders, service-desk routing, and training resources.

## Lab steps

1. Open Microsoft Copilot Studio.
2. Select the correct environment and solution for the lab.
3. Create a new agent using natural language.
4. Use this description:

   > Create an agent named company Operations Support Agent. The agent helps employees find training resources, maintenance readiness guidance, HSE reminders, and escalation contacts for operational support scenarios. It should respond in a professional, safety-conscious tone and avoid giving instructions beyond approved knowledge sources.

5. Add instructions:

   > Always remind users to follow official company procedures, local regulations, and site-specific safety requirements. If the question involves an emergency, direct the user to follow the official emergency response process.

6. Add an approved public website or internal knowledge source for training demonstration purposes.
7. Test the agent with prompts such as:

   > What information should I prepare before a site maintenance planning meeting?

   > How should I escalate a missing safety permit issue?

8. Publish the agent to the approved channel, such as Microsoft Teams, only after review and approval.

## Debrief questions

- What makes a Copilot Studio agent safer than an unrestricted chatbot?
- Which topics should be excluded or escalated?
- How should the agent be reviewed, maintained, and retired?

## Participant worksheet

| Copilot Studio item | Your notes |
|---|---|
| Agent description |  |
| Instructions or guardrails |  |
| Knowledge source used |  |
| Test prompt that worked well |  |
| Governance or approval requirement |  |
