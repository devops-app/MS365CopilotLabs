---
layout: default
title: "How to use this workbook"
---

# How to use this workbook

This workbook teaches one set of Microsoft 365 Copilot skills through fourteen labs and a capstone, each set in a different department and a different Contoso Group business unit. A finance analyst, a legal reviewer, and a customer-service lead can each start with the lab that matches their role, then see the same prompting, grounding, and validation habits applied to healthcare, retail, manufacturing, financial services, education, and technology work. Read this section and Lab 00 first; after that the labs can be taken in any order, although the agent labs assume you have completed at least one Copilot Chat lab.

Every lab is written in a Microsoft Learn-style format: a real business scenario, sample files, learning objectives, staged exercises with production-ready prompts, expected results, and validation steps.

## Key terms used throughout

- **Copilot Chat** — the conversational surface in Microsoft 365, used in Work mode so it can reference your files.
- **Grounding** — answering only from named files or approved knowledge sources, rather than from general knowledge.
- **Output contract** — the exact format you require in the prompt, such as a table, JSON, or a fixed set of sections.
- **Agent** — a reusable assistant built in Agent Builder or Copilot Studio with its own purpose, instructions, and knowledge sources.
- **Few-shot** — including one or two worked examples in the instructions so the agent copies the tone and format you want.
- **Red-teaming** — deliberately testing an agent with unsafe, out-of-scope, or misleading prompts before it is shared.

Lab levels follow the Microsoft convention: Level 100 is foundational and needs no prior experience, Level 200 assumes you can already prompt and reference files, and Level 300 involves multi-step analysis, agent configuration, or evaluation work.

## Scope of this workbook

- **In scope:** Microsoft 365 Copilot Chat; Copilot in Word, Excel, PowerPoint, Outlook, and Teams; the Analyst and Researcher agents; and agent building with Agent Builder.
- **Out of scope, reserved for a follow-on session:** building and publishing a Copilot Studio agent; sharing agents across a tenant; Copilot in OneNote, Loop, and Pages; SharePoint agents; Copilot Search; connectors to third-party data; and tenant administration and Copilot usage analytics.

Copilot Studio appears only as a comparison point in Lab 13 and Appendix C. State this scope at the start of the session so participants know which questions the workshop will not answer.

Before the session, confirm that each participant has a Microsoft 365 Copilot licence assigned, access to Copilot Chat in Work mode, the desktop apps for Word, Excel, PowerPoint, Outlook, and Teams signed in with the same work account, the Analyst and Researcher agents and Agent Builder available in the tenant, and read access to the OneDrive folder holding the sample data. Labs 08 to 13 depend on the agents being enabled, so check this first. Where a capability is not licensed or not yet switched on, run the affected lab as a facilitated prompt-design discussion using the same scenario, and record the gap for the tenant administrator to follow up.

## The Contoso Group scenario

Contoso Group is a fictional diversified enterprise. Its six business units each represent a different industry, and eight shared departments operate across all of them:

| Business unit | Industry | Used most in |
| --- | --- | --- |
| Contoso HealthCare | Healthcare | HR compliance, Customer Service, privacy |
| Contoso Retail | Retail / e-commerce | Marketing, Sales, Customer Service |
| Contoso Manufacturing | Manufacturing | Operations, Finance, quality |
| Contoso Financial | Financial Services | Compliance, Customer Service, Finance |
| Contoso Learning | Education | Marketing, HR, project delivery |
| Contoso CloudWorks | Technology / SaaS | Sales, IT, product |

Industry coverage is deliberately uneven across the labs. Technology, Retail, Financial Services, and Manufacturing each anchor at least one lab, while Contoso HealthCare and Contoso Learning appear as context inside the HR, compliance, and safety exercises rather than owning a lab of their own. If you are running this workbook for a healthcare or education audience, keep the lab structure and swap the scenario framing: replace the Retail loyalty campaign in Lab 03 with a patient-communication or student-recruitment campaign, use the same charter and stand-up notes for a clinical or campus programme in Lab 07, and read the Contoso HealthCare and Contoso Learning rows in Appendix B before writing any prompt.

## Departments covered

Eight departments are represented. Seven own a dedicated lab: HR in Lab 01, Legal and Compliance in Lab 02, Marketing in Lab 03, Customer Service in Labs 04 and 08, Finance and Accounting in Labs 05 and 12, Sales in Lab 06, and Operations and Supply Chain in Lab 07. The eighth, IT and security, is covered through the shared labs instead of a track of its own — Lab 00 for workspace and data-handling setup, Lab 11 for agent building, and Lab 13 for agent evaluation and red-teaming — so IT participants should follow the agents track. Lab 09 is written for a strategy or programme-office role and suits anyone who consolidates work from several departments. Each lab names the department and business unit it targets, so learners can jump straight to the track most relevant to their role.

## Recommended learning path

| Track | Labs | Focus |
| --- | --- | --- |
| Productivity core | Lab 00–07 | Copilot Chat, Word, PowerPoint, Outlook, Excel, Teams across departments |
| Agents core | Lab 08–11 | Analyst, Researcher, tool selection, first Agent Builder agent |
| Agents advanced | Lab 12–13 | Grounding, structured output, refusal design, red-team evaluation |
| Capstone | Capstone | Cross-department leadership briefing pack |

Delivered end to end, the labs and capstone total roughly seven and a half hours of hands-on time — closer to eight and a quarter once the daily triage exercise in Lab 04 and the forecasting and what-if exercises in Labs 05 and 06 are included — which is more than most groups absorb in one sitting. Three schedules work well. A two-hour taster covers Lab 00, one department lab chosen for the audience, and Lab 10. A full-day workshop covers Labs 00 to 07 in the morning and Labs 08 to 11 plus the capstone in the afternoon, choosing either Lab 05 or Lab 06 rather than both. A two-half-day format puts the productivity core on day one and the agents track, including Labs 12 and 13, on day two. Add about fifteen minutes per lab for debrief in a room of more than twenty people, about ten minutes to Lab 04 if you run the daily triage exercise, and about ten minutes to whichever of Labs 05 and 06 you run if you include its scenario exercise.

## Full lab index

| Lab | Title | Department / Industry | Primary app | Level | Time |
| --- | --- | --- | --- | --- | --- |
| 00 | Configure your workspace and guardrails | All | OneDrive, Chat | 100 | 10 min |
| 01 | Multi-file reasoning and prompt engineering | HR / cross-function | Copilot Chat | 200 | 25 min |
| 02 | Contract review summary and dual-audience rewrite | Legal / Technology | Word | 200 | 30 min |
| 03 | Quarterly business review briefing | Marketing / Retail | PowerPoint | 200 | 25 min |
| 04 | Customer escalation communications | Customer Service / Financial | Outlook | 200 | 35 min |
| 05 | Budget variance analysis | Finance / Manufacturing | Excel | 300 | 35 min |
| 06 | Sales pipeline analytics | Sales / Technology | Excel | 300 | 35 min |
| 07 | Cross-functional project meeting | Operations / cross-function | Teams | 200 | 30 min |
| 08 | Deep data analysis with the Analyst agent | Customer Service / Retail | Analyst agent | 300 | 35 min |
| 09 | Multi-source business investigation | Strategy / cross-function | Researcher agent | 300 | 35 min |
| 10 | Researcher vs Analyst vs Chat — tool selection | All | Copilot, agents | 200 | 20 min |
| 11 | Build a knowledge agent with Agent Builder | HR + Customer Service | Agent Builder | 200 | 30 min |
| 12 | Advanced agent — grounding, schema, refusal | Finance / Compliance | Agent Builder | 300 | 35 min |
| 13 | Agent evaluation and red-team testing | Security / governance | Agent Builder, Studio | 300 | 40 min |
| Cap | Cross-department leadership briefing pack | All | Word, Excel, PPT, Agents | 200 | 45 min |
